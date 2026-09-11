# TSH82 Configurable Dual Op-Amp Evaluation Board

A compact, 2-layer configurable analog evaluation board designed in KiCad for the STMicroelectronics TSH82 wideband dual operational amplifier.

---

## 3D Board View
![3D PCB Render](PCB_3d.png)

## Schematic Diagram
[View Complete Schematic PDF](TSH82_opamp_board.pdf)

---

## Technical Specifications
- **Core IC:** STMicroelectronics TSH82 (Dual Op-Amp, SOIC-8)
- **Board Dimensions:** 50.0 mm × 30.0 mm
- **Layers:** 2-layer FR4 (1.6 mm thickness)
- **Power Topology:** Single-supply (VCC/GND) with an onboard precision VCC/2 virtual ground reference (VREF)
- **Decoupling:** Dual-stage bulk (10 µF electrolytic) + high-frequency ceramic (0.1 µF MLCC)
- **Reconfigurability:** 10 onboard solder jumpers (JP1–JP10) to toggle between inverting, non-inverting, AC-coupled, and DC-coupled amplification stages
- **I/O Interface:** 1×9 pin vertical header (2.54 mm / 100 mil pitch) breaking out all channel inputs, outputs, and power rails

---

## Connector Pinout (J1)
| Pin # | Net Name | Function |
| :---: | :---: | :--- |
| 1 | VCC | DC Supply Input |
| 2 | GND | Common Ground |
| 3 | VREF | Mid-rail Virtual Ground (VCC/2) |
| 4 | -IN1 | Channel 1 Inverting Input |
| 5 | OUT1 | Channel 1 Output |
| 6 | +IN1 | Channel 1 Non-Inverting Input |
| 7 | -IN2 | Channel 2 Inverting Input |
| 8 | +IN2 | Channel 2 Non-Inverting Input |
| 9 | OUT2 | Channel 2 Output |