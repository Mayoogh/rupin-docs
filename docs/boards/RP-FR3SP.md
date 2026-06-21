# RP-FR3SP — Fan Regulator (3-Speed)

## Overview

_Describe the board's purpose — controls a ceiling fan at 3 speeds, installed in a wall box or behind a switch plate._

---

## Specifications

| Parameter | Value |
|-----------|-------|
| Speeds | 3 |
| Input | Mains (_add voltage_) |
| MCU | STM32G030K6T6TR |
| Speed Control | _add method: capacitor switching / triac / relay_ |
| PCB Size | _add dimensions_ mm |
| Connector | _add type_ |

---

## Schematic

[Download Schematic PDF (v3.0.1)](https://github.com/Otomator-Technologies/rupin-hardware/releases/tag/RP-FR3SP-v3.0.1)

### Functional Blocks

- **Power supply** — _describe SMPS / LDO topology_
- **Touch sensing** — _describe speed selection input_
- **MCU** — STM32G030K6T6TR, _describe firmware role_
- **Speed switching** — _describe relay / capacitor / triac topology for 3-speed control_
- **Communication** — _describe how it talks to the controller_

---

## Design Notes

_Add design decisions here. Examples:_

- _Speed switching method choice and tradeoffs_
- _Capacitor values for each speed step_
- _Thermal considerations_

---

## Known Issues & Fixes

| Version | Issue | Fix |
|---------|-------|-----|
| v3.0.0 | TP224 touch IC replaced | Replaced with TT223 in v3.0.1 |

---

## Version History

| Version | Changes | Release |
|---------|---------|---------|
| v3.0.1 | Replaced TP224 with TT223, cleanup | [RP-FR3SP-v3.0.1](https://github.com/Otomator-Technologies/rupin-hardware/releases/tag/RP-FR3SP-v3.0.1) |
| v3.0.0 | Initial release | [RP-FR3SP-v3.0.0](https://github.com/Otomator-Technologies/rupin-hardware/releases/tag/RP-FR3SP-v3.0.0) |
