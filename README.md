# Grizzly V-Core: Custom Rat Rig V-Core 3.1 Hybrid

![Grizzly V-Core Project](./images/vcore-grizzly.jpg)

## 🚀 Project Overview
The **Grizzly V-Core** is a comprehensive hardware redesign and modding project based on the open-source **Rat Rig V-Core 3.1**. This hybrid version was engineered to bridge the gap between the V-Core 3.1 and the V-Core 4.

This project demonstrates advanced skills in **Mechanical CAD Design**, **Open-Source Hardware Adaptation**, and **Precision Engineering**.

## 📁 Project Resources & CAD Data
Due to the high detail and file size (78 MB+), the full assembly STEP and 3MF files are hosted on Printables to ensure easy version access and community interaction.

| Resource | Link |
| :--- | :--- |
| **Full CAD Assembly (STEP)** | [➔ Download from Printables](https://www.printables.com/model/1163879-grizzly-v-core-modded-rat-rig-v-core-31-hybrid) |
| **Bill of Materials (BOM)** | Integrated within the CAD model (Full Component Tree) |
| **Slicer Profiles (Orca)** | [➔ View Profiles](./slicer-profiles) |
| **Klipper Configuration** | [➔ View Config Folder](./config) |

## 🛠 Key Features & Modifications
The "Grizzly" edition introduces over 15 specific enhancements designed for performance and reliability:

* **01: CPAP CNC** – Custom part cooling solution. [View Mod on Printables](https://www.printables.com/model/965843-cpap-part-cooling-fan-for-rat-rig-v-core-31)
* **02: Hybrid Gantry** – Redesigned gantry to accommodate hybrid kinematics.
* **03: Printhead** – Specialized CNC-optimized printhead. [View Mod on Printables](https://www.printables.com/model/965777-grizzly-cnc-printhead-for-ratrig-v-core-31)
* **04: Motor Mounts** – Machined out of aluminium and powder coated. Features integrated bearings for perfect pulley alignment and decoupled motors to reduce vibrations.
* **05: Belt Tensioners** – Inspired by V-Core 4, machined from aluminium for maximum rigidity.
* **06: Lead Screw Guides** – Redesigned to fit the new tensioner system.
* **07: Side Covers** – Integrated dual-fan panels for active CoreXY motor cooling.
* **08: Y-Endstop** – Custom mount adapted for the new gantry geometry.
* **10: RSCS (Remote Static Cooling System)** – Sketched solution for high-flow PLA cooling.
* **11: Integrated Filter** – Custom carbon pellet cartridge utilizing the CPAP intake for air filtration.
* **12: Wago Holder** – Clean electronics mounting for Wago 221 connectors.
* **13: Drag Chain Holder** – Optimized cable management for the heated bed.
* **14: Grizzly LED Holder** – Custom integrated lighting solution.
* **15: Camera Mount** – Dedicated holder for OV5648 webcams.

> **Technical Note:** Instead of standard heat-set inserts, this design consistently utilizes [Threaded Inserts](https://de.aliexpress.com/item/1005006217825443.html) for enhanced mechanical strength.

*Disclaimer: Please be aware that even though it worked for me, doesn't mean that every model works for you. The model of the printer is, by far, neither finished nor perfect.*

## 💻 Software & Control (Klipper)
The Grizzly V-Core is powered by **Klipper Firmware**. My custom configuration emphasizes precision and workflow automation:

* **Custom Macros:** Optimized routines for automated leveling, filament handling, and safety checks.
* **Hybrid Kinematics:** Fine-tuned motion planning specifically for this hybrid frame geometry.
* **Advanced Tuning:** Implementation of Input Shaping and Pressure Advance to maximize print quality at high speeds.
* **Orca Slicer Profiles:** Fine-tuned profiles for various materials (ASA, PC, CF-Nylon), optimized for the Grizzly's specific cooling and speed capabilities.

## 🔧 Technical Stack
* **Base Frame:** Rat Rig V-Core 3.1 (Remix)
* **Design Software:** Fusion 360
* **Manufacturing Focus:** CNC Machining & FDM Printing
* **Firmware Environment:** Optimized for Klipper

## 🌍 External Links
👉 [Grizzly V-Core on Printables](https://www.printables.com/model/1163879-grizzly-v-core-modded-rat-rig-v-core-31-hybrid)

---

### ⚖️ License
This project is licensed under the **MIT License**.
*(Note: As this is a remix of the Rat Rig V-Core, please respect the original open-source contributions of the Rat Rig team.)*
