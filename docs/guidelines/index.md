# Design Guidelines

Standards and rules followed across all Rupin PCB designs.

---

## PCB Design Rules

_Add KiCad DRC rules, clearances, track widths used across the product line._

| Parameter | Value | Notes |
|-----------|-------|-------|
| Min track width | _add_ | Signal |
| Min track width | _add_ | Power |
| Min clearance | _add_ | |
| Min via drill | _add_ | |
| Copper pour | _add_ | GND / Power planes |

---

## Component Selection

### MCUs
_Describe the MCU family standardized across products (STM32G030 series) and rationale._

### Touch ICs
_Describe approved touch ICs, sensitivity settings, electrode design rules._

### Relays
_Describe relay selection criteria — coil voltage, contact rating, footprint standard._

### Power Supply
_Describe SMPS / LDO topology standards, derating rules, approved parts._

---

## Schematic Conventions

_Describe how schematics are organized: sheet hierarchy, net naming, power symbols, annotation style._

---

## Footprint & 3D Model Rules

_Describe footprint sourcing (common/lib vs KiCad standard), courtyard rules, 3D model requirements._

---

## Silkscreen & Fabrication

_Describe silkscreen requirements: version marking, logo placement, reference designator rules._

---

## Design Review Checklist

- [ ] DRC passes with zero errors
- [ ] All footprints have 3D models
- [ ] Version number on silkscreen
- [ ] Power nets verified (correct polarity, no floating pins)
- [ ] Mains isolation clearance checked
- [ ] BOM exported and verified
- [ ] Gerbers reviewed in Gerber viewer before release
