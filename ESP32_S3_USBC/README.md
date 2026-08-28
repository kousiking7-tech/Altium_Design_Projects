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
ESP32-S3-Mini-USB-C/
│
├── 📁 3D/                              # 3D STEP models for PCB components
├── 📁 Docs/                            # Project datasheets, documentation & reference files
├── 📁 Image/                           # Project screenshots & 3D render images
├── 📁 Project Logs for esp32-s3 mini/  # Altium design history & compilation logs
├── 📁 Project Outputs for esp32-s3 mini/# Gerber files, NC Drill & Manufacturing outputs
│
├── 📄 esp32 with USBC.PcbDoc           # 4-Layer PCB Board Layout file
├── 📄 esp32 with USBC.SchDoc           # Circuit Schematic file
├── 📄 Job.OutJob                       # Altium Output Job configuration file
├── 📄 Pcblib.PcbLib                    # Custom PCB Footprint Library
├── 📄 Schlib.SchLib                    # Custom Schematic Symbol Library
│
├── 📄 esp32-s3 mini.PrjPcb             # Main Altium Project File
├── 📄 esp32-s3 mini.PrjPcbStructure    # Altium Project Structure Metadata
└── 📄 README.md                        # Project documentation & overview
```

## 🎓 Acknowledgments & References

This hardware design was created by following the expert hardware engineering tutorials provided by **Robert Feranec**. 

* **Instructor:** Robert Feranec (Hardware Design Engineer & Educator)
* **YouTube Channel:** [FEDEVEL Educational / Robert Feranec](https://www.youtube.com/watch?v=KWIzhbQaZZk)
* **Topics Covered:** Altium Designer workflows, 4-layer PCB stackup planning, custom component footprint creation, and USB differential pair routing.
