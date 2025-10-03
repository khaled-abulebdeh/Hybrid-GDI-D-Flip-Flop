# GDI D Flip-Flop: Ultra-Low-Power Digital Design 💡

## Project Overview

This project focuses on the design, simulation, and comprehensive analysis of a highly efficient, low-power **Master-Slave D Flip-Flop (DFF)**. The design leverages the **Gate Diffusion Input (GDI)** logic technique to minimize power consumption, reduce transistor count, and decrease propagation delay compared to conventional **CMOS** designs.

The culminating result is a novel, robust **12-Transistor Hybrid GDI D-Flip-Flop** specifically optimized for modern sub-20nm fabrication processes.

## Key Features and Novelty

The primary contribution of this work is the **Channel Length Engineering** technique applied to ensure circuit robustness on advanced nodes.

* **Hybrid Architecture:** Combines **GDI multiplexers** for low transistor count with **CMOS inverters** to guarantee a full-swing output and improve stability.
* **Process Node:** Implementation targeting a **16nm High-Performance (HP) CMOS process**.
* **Robustness Solution:** Mitigated short-channel effects, which caused failure at the minimum channel length (16nm), by strategically increasing the channel length to **22nm** while remaining on the 16nm HP process.
* **Transistor Count:** Achieved with a low count of **12 transistors**.

## Design and Implementation

### Logic Technique
The **Gate Diffusion Input (GDI)** technique is utilized to create complex logic with fewer transistors, inherently reducing dynamic power consumption and area.

### Design Tools and Flow
The complete design, simulation, and verification flow followed these steps:

1.  **Schematic & Layout:** Designed using **Electric EDA** (Electric tools).
2.  **Functional Simulation:** Performed using **LTspice** to verify correct logic operation.
3.  **Post-Layout Verification:** Conducted **DRC/LVS** (Design Rule Check / Layout vs. Schematic) and parasitic extraction.
4.  **Performance Analysis:** Post-layout simulations measured power, delay, and area metrics.

### Performance Results

The optimized GDI DFF design demonstrated significant performance improvements over the standard CMOS baseline:

| Metric | Improvement over Standard CMOS |
| :--- | :--- |
| **Power Consumption** | **99.5% Reduction** |
| **Area** | **94.3% Reduction** |
| **Robustness** | Ensured stable, robust operation in the 16nm process through channel length engineering. |

## Documentation and Deliverables

The complete project is summarized in a technical paper drafted in **IEEE format**, suitable for journal submission or academic assessment.

* **Final Technical Paper:** `Robust_12_Transistor_Hybrid_GDI_D_Flip_Flop_in_16nm_CMOS_via_Channel_Length_Engineering.pdf`
* **Project Outline:** `Ic_Project_Second_semester_2024.pdf`
* **Deliverables:** Transistor-level schematic and layout files, simulation results (waveforms, power, delay), and comparative charts/tables.

---

## Contributors

* Khaled Abu Lebdeh
* Amir Al-Rashayda
* Mohammad Shashaa
