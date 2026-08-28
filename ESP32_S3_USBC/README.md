# ⚡ ESP32-S3 USB-C Hardware Board Design

## 📌 Project Overview

This project features a custom **4-layer PCB design** for the **ESP32-S3 Mini** microcontroller with a native **USB-C** interface, developed in **Altium Designer**. 

All schematic symbols, PCB footprints, stackup configurations, and 3D component models were built from scratch and assembled following design practices from **Robert Feranec's** hardware design tutorials.

---

### 🛠 Key Specifications

| Parameter | Details |
| :--- | :--- |
| **CAD Tool** | Altium Designer |
| **Microcontroller** | ESP32-S3 Mini |
| **PCB Layer Count** | 4 Layers (Signal - GND - PWR - Signal) |
| **Connector Type** | USB Type-C (USB 2.0 High-Speed) |
| **Library Assets** | Custom Symbols, Footprints & 3D STEP Models |
| **Impedance Control** | $90\,\Omega$ Differential Traces for USB ($D+/D-$) |

---

## 📁 Repository Structure

```text
ESP32/
├── ESP32-S3.PrjPcb      # Altium Main Project File
├── Schematic.SchDoc     # Circuit Schematic Document
└── PCB_Layout.PcbDoc    # 4-Layer PCB Board Layout
