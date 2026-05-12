# ATMEGA8-PCB



# ATmega8 KSC — 2-Layer PCB
 
A compact 2-layer PCB (~62×62mm) designed around the **ATmega8** 8-bit AVR microcontroller by Atmel/Microchip. Gerber files were generated with **PADS 9.4.1** in RS-274-X format and are ready for fabrication.
 
---
 
## 📐 Board Specifications
 
| Property | Value |
|---|---|
| Board Size | ~62mm × 62mm |
| Layers | 2 (Top + Bottom Copper) |
| PCB Format | RS-274-X Gerber |
| Design Tool | PADS 9.4.1 |
| Units | Metric (mm) |
| Mounting Holes | 4 × 3.5mm (corners) |
 
---
 
## 🧠 Microcontroller
 
**ATmega8** (Atmel/Microchip AVR)
- 8KB Flash, 1KB SRAM, 512B EEPROM
- 23 programmable I/O pins
- SPI, I2C, UART interfaces
- 10-bit ADC (6 channels)
- ISP/ICSP in-system programmable
---
 
## 📁 Gerber File Index
 
| File | Layer | Description |
|---|---|---|
| `TOP-PATTERN.pho` | Top Copper | Top-side traces, pads, vias |
| `BOTTOM-PATTERN.pho` | Bottom Copper | Bottom-side traces and pads |
| `TOP-MASK.pho` | Top Solder Mask | Pad openings for soldering |
| `BOTTOM-MASK.pho` | Bottom Solder Mask | Bottom pad openings |
| `TOP-SILK.pho` | Top Silkscreen | Component outlines & reference designators |
| `ssb002029.pho` | Bottom Silkscreen | Bottom-side labels and outlines |
| `NC-DRILL.drl` | NC Drill | Machine-readable drill coordinates |
| `DRILL.pho` | Drill Drawing | Visual drill chart/legend |
 
---
 
## 🔩 Drill Summary
 
| Tool | Diameter | Qty | Purpose |
|---|---|---|---|
| T1 | 0.30 mm | 160 | Vias (inter-layer connections) |
| T2 | 0.50 mm | 16 | Small signal pins |
| T3 | 0.70 mm | 2 | Through-hole pins |
| T4 | 0.75 mm | 2 | Through-hole pins |
| T5 | 0.80 mm | 2 | Through-hole pins |
| T6 | 1.00 mm | 53 | Standard component leads |
| T7 | 3.50 mm | 4 | Mechanical mounting holes (non-plated) |
| **Total** | | **239** | |
 
---
 
## 🧩 On-Board Components 
 
- ATmega8 DIP-28 or TQFP-32 MCU
- ISP/ICSP 6-pin or 10-pin programming header
- Power supply circuitry (voltage regulator, decoupling capacitors)
- Crystal oscillator for clock source
- I/O connectors / breakout headers
- Passive components (resistors, capacitors)
---
 
## 🏭 Fabrication
 
These Gerber files can be sent directly to any standard PCB fab house:
 
| Setting | Value |
|---|---|
| Layers | 2 |
| Board thickness | 1.6mm |
| Min hole size | 0.3mm |
| Surface finish | HASL or ENIG |
| Solder mask | Both sides |
| Silkscreen | Both sides |
 
---
 



## Layer view 
![L1](https://github.com/user-attachments/assets/4c93dd34-5e6f-4c24-82a0-e4bfa052f5de)
![캡처](https://github.com/user-attachments/assets/575606f8-981a-4fff-b1c9-0df3a62027f1)


## Schematics
![atmega8-ksc](https://github.com/user-attachments/assets/8d663d8e-b84b-41b7-b994-f353bf1e2334)


## Drawings

![1](https://github.com/user-attachments/assets/fecffbdd-9a35-49ca-909a-b982a7d10efb)
![5](https://github.com/user-attachments/assets/4186bf3c-0590-44d1-a6de-c8131ac87ebe)
![4](https://github.com/user-attachments/assets/dee71586-dab7-4c6a-8ab4-457864e824a4)
![3](https://github.com/user-attachments/assets/d98c0ad1-8154-48e5-88ca-accbe568238f)
![8](https://github.com/user-attachments/assets/c0b7f7b9-162b-4574-9903-b2d9c6415d68)
![2](https://github.com/user-attachments/assets/8fcaaa15-3137-4419-9853-245397914e67)
![7](https://github.com/user-attachments/assets/2ef4467a-939d-4206-95df-1c789b5edf64)


## 📜 License
 
This project is open hardware. Feel free to use, modify, and manufacture.
