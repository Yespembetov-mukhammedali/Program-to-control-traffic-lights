#3-Phase Traffic Light Control System via FBD & HMI Visualization

An industrial-grade automation project implementing a sequential 3-phase traffic light control system (Red, Yellow, Green) using **Function Block Diagram (FBD)** logic compliant with the **IEC 61131-3** standard. The system features a fully integrated **HMI (Human-Machine Interface)** dashboard for real-time monitoring and simulation.

---

## 📌 Project Overview

This repository contains the complete implementation of a classic traffic control algorithm designed for PLCs (Programmable Logic Controllers). Instead of basic scripting, the control loop utilizes dedicated cascading hardware timers to ensure robust, deterministic, and safe state transitions.

### Key Features:
* **Deterministic Logic:** Engineered using FBD networks for clear, scannable data flows.
* **Cascading Timer Architecture:** Three synchronized timers managing the precise execution duration of each light phase.
* **HMI Dynamic Visualization:** Live operational dashboard mapped directly to the controller's I/O image table for real-time diagnostics.
* **IEC 61131-3 Compliant:** Built adhering to global industrial automation standards.
