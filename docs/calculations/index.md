# Calculations

Engineering calculations referenced in the Rupin hardware designs.

---

## Power Supply

### SMPS Output Voltage

_Add resistor divider calculation for feedback voltage._

$$V_{out} = V_{ref} \times \left(1 + \frac{R_1}{R_2}\right)$$

_Example: add component values and result here._

---

### LDO Dropout & Heat Dissipation

$$P_{dissipated} = (V_{in} - V_{out}) \times I_{load}$$

_Add values per board._

---

## Touch Electrode

### Sensitivity & CS Pin Capacitance

_Describe electrode area, trace length, parasitic capacitance, and TTP223 sensitivity adjustment._

---

## Relay Driver

### Base Resistor Calculation

$$R_B = \frac{V_{GPIO} - V_{BE}}{I_B} = \frac{V_{GPIO} - 0.7}{I_C / h_{FE}}$$

_Add coil current, transistor hFE, and computed RB per board._

---

## Fan Speed Control

### Capacitor Switching (if applicable)

_Describe how capacitor values are selected for each fan speed step. Add calculation or reference._

---

## Mains Isolation

_Add creepage and clearance calculations for mains-connected boards, referencing the applicable standard (IEC 60950 / IEC 62368)._

| Parameter | Required | Achieved | Standard |
|-----------|----------|----------|---------|
| Creepage | _add_ mm | _add_ mm | _add_ |
| Clearance | _add_ mm | _add_ mm | _add_ |
