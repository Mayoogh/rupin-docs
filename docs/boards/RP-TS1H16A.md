# RP-TS1H16A — 1-Channel Touch Switch

## Overview

_Describe the board's purpose and where it is installed (e.g. single gang wall box, controls one light/load)._

---

## Specifications

| Parameter | Value |
|-----------|-------|
| Channels | 1 |
| Input | Mains (_add voltage_) |
| MCU | STM32G030F6P6 |
| Touch IC | TTP223-BA6 |
| Relay | _add relay part_ |
| PCB Size | _add dimensions_ mm |
| Connector | _add type_ |

---

## Schematic

[Download Schematic PDF (v3.0.1)](https://github.com/Otomator-Technologies/rupin-hardware/releases/tag/RP-TS1H16A-v3.0.1)

_Embed key schematic sections here as images, or describe the functional blocks below._

### Functional Blocks

- **Power supply** — _describe SMPS / LDO topology_
- **Touch sensing** — TTP223 capacitive touch IC → MCU GPIO
- **MCU** — STM32G030F6P6, _describe firmware role_
- **Relay driver** — _describe driver circuit and relay specs_
- **Communication** — _describe how it talks to the controller_

---

## Design Notes

_Add design decisions, constraints, and rationale here. Examples:_

- _Why this relay was chosen over alternatives_
- _Touch sensitivity tuning_
- _Any layout-critical nets_

---

## Known Issues & Fixes

| Version | Issue | Fix |
|---------|-------|-----|
| v3.0.0 | VDD & GND pin sequence error | Fixed in v3.0.1 |

---

## Version History

| Version | Changes | Release |
|---------|---------|---------|
| v3.0.1 | Fixed VDD & GND pin sequence | [RP-TS1H16A-v3.0.1](https://github.com/Otomator-Technologies/rupin-hardware/releases/tag/RP-TS1H16A-v3.0.1) |
| v3.0.0 | Initial release | [RP-TS1H16A-v3.0.0](https://github.com/Otomator-Technologies/rupin-hardware/releases/tag/RP-TS1H16A-v3.0.0) |
