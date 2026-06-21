# Onboarding Guide

Welcome to the Rupin hardware team. This page gets you set up and oriented quickly.

---

## What is Rupin?

Rupin is a home automation product line. The hardware consists of PCBs that handle touch input, fan speed control, and WiFi-based control — all designed to work together as a system.

See the [System Architecture](architecture/index.md) for how the boards connect.

---

## Tools You Need

| Tool | Purpose | Download |
|------|---------|---------|
| KiCad 8.x | Open and edit PCB designs | [kicad.org](https://www.kicad.org) |
| Git | Version control | [git-scm.com](https://git-scm.com) |
| A web browser | View iBOM files | — |

---

## Getting the Hardware Files

```bash
git clone https://github.com/Otomator-Technologies/rupin-hardware.git
```

Each product lives in its own folder, versioned by release:

```
rupin-hardware/
├── RP-TS1H16A/
│   ├── RP-TS1H16A v3.0.0/
│   └── RP-TS1H16A v3.0.1/    ← latest
├── RP-TS2S10A/
│   └── ...
└── ...
```

---

## Opening a Project in KiCad

1. Open KiCad
2. File → Open Project
3. Navigate to `RP-XXXX/RP-XXXX vX.X.X/`
4. Select the `.kicad_pro` file

---

## Understanding the Output Files

All production-ready files are in `Outputs/production/` inside each version folder:

| File | What it is |
|------|-----------|
| `*_GERBER.zip` | Send to PCB manufacturer for fabrication |
| `*_BOM.csv` | Bill of materials for component procurement |
| `*_iBOM.html` | Open in browser — interactive assembly reference |
| `*_POS.csv` | Pick & place file for SMT assembly |
| `*_SCH.pdf` | Schematic PDF for reference |
| `*.step` | 3D model for mechanical fit check |

---

## Getting a Production Release

Go to [rupin-hardware releases](https://github.com/Otomator-Technologies/rupin-hardware/releases) and download the `PRODUCT-VERSION-production.zip` for the board you need. It contains everything the manufacturer requires.

---

## Where to Find Things

| Topic | Where to look |
|-------|--------------|
| How boards connect | [System Architecture](architecture/index.md) |
| Board-level details | [Boards](boards/index.md) |
| Component selection rules | [Design Guidelines](guidelines/index.md) |
| Power / signal calculations | [Calculations](calculations/index.md) |
