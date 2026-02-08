# 🐻 Grizzly V-Core: A 3.1 to 4.0 Hybrid Journey

![Grizzly V-Core Project](images/vcore-grizzly.gif)

## 🚀 What is the "Grizzly"?
The **Grizzly V-Core** started as a standard **Rat Rig V-Core 3.1**, but I wanted to push it further. This hybrid build bridges the gap between the 3.1 and the new V-Core 4, mixing custom CNC-machined parts with optimized open-source designs. 

It’s my personal take on making a V-Core even more rigid, reliable, and "overbuilt."

## 🛠 Features & My Mods
I’ve added or redesigned over 15 parts for this build. The goal was simple: more metal, better cooling, and cleaner wire management.

* **CNC Aluminum Parts:** The motor mounts and belt tensioners (inspired by V-Core 4) are machined from aluminium and powder-coated. They feature integrated bearings for better pulley alignment and decoupled motor mounts to keep vibrations down.
* **The Grizzly Printhead:** A custom CNC-optimized toolhead designed for high-flow printing. [Check it out on Printables](https://www.printables.com/model/965777-grizzly-cnc-printhead-for-ratrig-v-core-31).
* **CPAP Part Cooling:** Because you can never have enough air for fast PLA prints. [View Mod](https://www.printables.com/model/965843-cpap-part-cooling-fan-for-rat-rig-v-core-31).
* **Hybrid Gantry:** Adjusted geometry to fit the new tensioners and lead screw guides.
* **Active Cooling:** Side panels with dual fans to keep the CoreXY motors cool during long, fast prints.
* **Carbon Filtration:** A custom cartridge that uses the CPAP intake air to filter fumes through active carbon pellets.
* **Workshop Ready:** Integrated LED lighting, camera mounts for remote monitoring, and proper Wago/drag chain holders for a clean electronics bay.

> **Maker Note:** I’m a big fan of [Threaded Inserts](https://de.aliexpress.com/item/1005006217825443.html) instead of standard heated ones—they just feel way more solid for these kinds of mechanical loads.

## 📁 Files & Resources
Since the full assembly is quite heavy (78 MB+), I host the STEP and 3MF files over on Printables so the community can easily grab updates.

| Resource | Link |
| :--- | :--- |
| **Full CAD Model** | [➔ Printables Project Page](https://www.printables.com/model/1163879-grizzly-v-core-modded-rat-rig-v-core-31-hybrid) |
| **Klipper Config** | [➔ My printer.cfg & Macros](./config) |
| **Slicer Profiles** | [➔ Orca Slicer Presets](./slicer-profiles) |

## 💻 Software Setup
I'm running **Klipper** with a custom RatOS base. 
* **Tuning:** I've spent a lot of time fine-tuning Input Shaper and Pressure Advance to get the best out of the rigid frame.
* **Automation:** Added custom macros for automated leveling (Euclid Probe) and safety checks.
* **Materials:** The Orca profiles are dialed in for ASA, PC, and CF-Nylon—basically everything that needs a solid, enclosed machine.

*Disclaimer: This is a hobby project. It works great for me, but it's "never finished." Use the files as a base for your own mods, but double-check your tolerances!*

---
### ⚖️ License
Licensed under **MIT**. 
Respect to the **Rat Rig Team** for their amazing open-source foundation.
