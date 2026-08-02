# Car Parking System

A localized capacity tracking and status visualization system programmed on a **Siemens S7-1200 (CPU 1215C)** using **TIA Portal**. 

### 🚗 Project Highlights
* **Capacity Tracking:** Implemented an Up/Down Counter (`CTUD`) to continuously monitor entry and exit proximity sensors, tracking real-time available spaces within a 10-car lot.
* **State-Based Visual Indicators:** Designed distinct threshold logic using comparators to actuate facility traffic lights based on lot capacity: Empty (0 Cars) = Green Light, Partially Full (1-9 Cars) = Yellow Light, Full (10 Cars) = Red Light.
* **Access Control Limits:** Configured interlocking logic tied to the "Full" status to strictly manage entry permissions when the lot reaches absolute maximum capacity.

### 📂 Repository Files
* **Ladder_Logic.pdf:** PDF export of the Main OB1 ladder logic, featuring the CTUD counters.
* **HMI_Screenshots:** Visual layout of the WinCC Runtime interface.
* **Car_Parking_System_Archive.zap15:** Raw TIA Portal V15 archive file.
