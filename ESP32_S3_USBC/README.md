# ⚡ ESP32-S3 USB-C Hardware Board Design

A compact, 4-layer custom PCB design for the **ESP32-S3** microcontroller featuring native USB-C support, onboard power regulation, and optimized RF ground plane.

---

## 🛠 Project Highlights
* **CAD Tool:** Altium Designer
* **Layer Count:** 4 Layers (Signal - GND - PWR - Signal)
* **USB Interface:** USB 2.0 High-Speed with $90\,\Omega$ differential routing
* **Power Supply:** $5\text{V}$ VBUS to $3.3\text{V}$ LDO regulator

---

## 📁 Repository Structure
```text
├── Schematics/         # Altium Schematic Documents (.SchDoc)
├── PCB_Layout/         # 4-Layer PCB File (.PcbDoc)
└── Outputs/            # Gerber Files, NC Drill & BOM
