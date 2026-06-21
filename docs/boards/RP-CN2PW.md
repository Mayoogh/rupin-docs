# RP-CN2PW — 2-Channel WiFi Controller

## Overview

_Describe the board's role — the WiFi bridge between the mobile app / cloud and the load-side boards (touch switches, fan regulator). Controls 2 channels._

---

## Specifications

| Parameter | Value |
|-----------|-------|
| Channels | 2 |
| WiFi Module | ESP32-WROOM-32D |
| MCU | STM32G030C8T6 |
| Input | _add supply voltage_ |
| PCB Size | _add dimensions_ mm |
| Connector | _add type_ |

---

## Schematic

[Download Schematic PDF (v3.0.1)](https://github.com/Otomator-Technologies/rupin-hardware/releases/tag/RP-CN2PW-v3.0.1)

### Functional Blocks

- **Power supply** — _describe power input and regulation_
- **ESP32-WROOM-32D** — WiFi connectivity, cloud/app communication
- **STM32G030C8T6** — _describe role: local control, communication with load boards_
- **ESP32 ↔ STM32 interface** — _describe: UART / SPI / I2C_
- **Load board interface** — _describe: how it communicates to TS / FR boards_

---

## Design Notes

_Add design decisions here. Examples:_

- _Why dual-MCU architecture (ESP32 + STM32) vs single chip_
- _WiFi antenna placement considerations_
- _Power sequencing requirements_

---

## Known Issues & Fixes

| Version | Issue | Fix |
|---------|-------|-----|
| v3.0.0 | APS05-05 pin error | Fixed in v3.0.1 |

---

## Version History

| Version | Changes | Release |
|---------|---------|---------|
| v3.0.1 | Fixed APS05-05 pin error | [RP-CN2PW-v3.0.1](https://github.com/Otomator-Technologies/rupin-hardware/releases/tag/RP-CN2PW-v3.0.1) |
| v3.0.0 | Initial release | [RP-CN2PW-v3.0.0](https://github.com/Otomator-Technologies/rupin-hardware/releases/tag/RP-CN2PW-v3.0.0) |
