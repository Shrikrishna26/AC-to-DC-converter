# 12V AC to DC Converter (PCB Design)

This project demonstrates the design and implementation of a simple **AC to DC converter** along with its **PCB layout using KiCad**.

The circuit converts **12V AC input to DC output** using a bridge rectifier and smoothing capacitor. It is a basic but fundamental power electronics circuit commonly used in small embedded systems and electronic devices.

---

## Project Overview

The converter consists of:

- **Bridge Rectifier** using 4 diodes (1N4148)
- **Filter Capacitor (1000µF)** to reduce ripple voltage
- **LED Indicator** to show power output
- **Current limiting resistor**
- **Screw terminals** for AC input and DC output

---

## Circuit Working Principle

1. The **AC input** is applied through the input screw terminal.
2. Four diodes form a **full-wave bridge rectifier**, converting AC to pulsating DC.
3. The **electrolytic capacitor (1000µF)** smooths the waveform by reducing ripple.
4. An **LED with resistor** acts as a power indicator.
5. The final output is obtained at the DC output terminal.

---

## Tools Used

- **KiCad** – Schematic design and PCB layout
- **KiCad 3D Viewer** – PCB visualization

---

## Project Images

### Circuit Schematic
![Circuit Schematic](AC-DC%20converter%20Schematics.png)

### Routing Layout
![PCB 3D Layout](AC-DC%20Converter%20layout.png)

### Final PCB Design
![PCB Design](AC-DC%20converter%20PCB%20design.png)
## Repository Structure
