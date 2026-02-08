# 🐻 Grizzly V-Core: A 3.1 to 4.0 Hybrid Journey

![Grizzly V-Core Project](images/vcore-grizzly.gif)

## 🚀 What is the "Grizzly"?
The **Grizzly V-Core** is a comprehensive hardware redesign and modding project based on the open-source **Rat Rig V-Core 3.1**. This hybrid version was engineered to bridge the gap between the V-Core 3.1 and the V-Core 4. 

## 🛠 Features & My Mods
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

> **Maker Note:** I’m a big fan of [Threaded Inserts](https://de.aliexpress.com/item/1005006217825443.html) instead of standard heated ones—they just feel way more solid for these kinds of mechanical loads.

## 📁 Files & Resources
Since the full assembly is quite heavy (78 MB+), I host the STEP and 3MF files over on Printables so the community can easily grab updates.

| Resource | Link |
| :--- | :--- |
| **Full CAD Model** | [➔ Printables Project Page](https://www.printables.com/model/1163879-grizzly-v-core-modded-rat-rig-v-core-31-hybrid) |
| **Bill of Materials (BOM)** | Integrated within the CAD model (Full Component Tree) |
| **Klipper Config** | [➔ My printer.cfg & Macros](./config) |
| **Slicer Profiles** | [➔ Orca Slicer Presets](./slicer-profiles) |

## 💻 Software Setup
I'm running **Klipper** with a custom RatOS base. 
* **Tuning:** I've spent a lot of time fine-tuning Input Shaper and Pressure Advance to get the best out of the rigid frame.
* **Automation:** Added custom macros for automated leveling (Euclid Probe) and safety checks.
* **Materials:** The Orca profiles are dialed in for ASA, PC, and CF-Nylon—basically everything that needs a solid, enclosed machine.
  
## 🔧 Technical Stack
* **Base Frame:** Rat Rig V-Core 3.1 (Remix)
* **Design Software:** Fusion 360
* **Manufacturing Focus:** CNC Machining, Powder coating & FDM Printing
* **Firmware Environment:** Optimized for Klipper
*Disclaimer: Please be aware that even though it worked for me, doesn't mean that every model works for you. The model of the printer is, by far, neither finished nor perfect.*

---
### ⚖️ License
Licensed under **MIT**. 
Respect to the **Rat Rig Team** for their amazing open-source foundation.
