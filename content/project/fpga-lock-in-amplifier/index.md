---
title: "FPGA-Based Digital Lock-In Amplifier with Signal Enhancement"
summary: "Designed and verified an FPGA-based lock-in amplifier system with comprehensive noise analysis, published in IEEE Embedded Systems Letters and Sensors."
tags:
  - FPGA
  - Lock-In Amplifier
  - VHDL
  - Signal Processing
  - UVM Verification
date: "2025-01-01"

image:
  caption: ""
  focal_point: Smart
  preview_only: false

links:
  - icon: newspaper
    icon_pack: fas
    name: IEEE ESL Paper
    url: https://doi.org/10.1109/LES.2024.3415651
  - icon: newspaper
    icon_pack: fas
    name: Sensors Review Paper
    url: https://doi.org/10.3390/s25020584
---

## Overview

Developed a fully digital **lock-in amplifier (LIA)** system implemented on FPGA, targeting advanced measurement applications where extracting weak signals buried in noise is critical. This project resulted in two peer-reviewed publications.

![Figure 8](images/sensors-25-lockamp-f8.png)
*Figure 8 — from Galaviz et al., Sensors 25(2), 584 (2025).*

![Figure 10](images/sensors-25-lockamp-f10.png)
*Figure 10 — from Galaviz et al., Sensors 25(2), 584 (2025).*

![Figure 11](images/sensors-25-lockamp-f11.png)
*Figure 11 — from Galaviz et al., Sensors 25(2), 584 (2025).*

## Key Contributions

- Designed the complete **digital signal processing pipeline** in VHDL: reference signal generation, phase-sensitive detection, and configurable low-pass filtering stages for in-phase (I) and quadrature (Q) outputs.
- Developed a **reliable verification methodology** combining simulation-based functional verification with quantitative noise analysis, characterizing SNR performance across operating conditions.
- Published a **comprehensive review** of FPGA-based LIA architectures for measurement applications (Sensors, 2025), covering design strategies, signal enhancement techniques, and implementation tradeoffs.
- Published the **verification and noise analysis methodology** in IEEE Embedded Systems Letters (2024), providing a reproducible framework for FPGA-based instrumentation design.

## Tools & Technologies

VHDL, Quartus Prime, ModelSim, MATLAB (fixed-point analysis and noise characterization), UVM-based testbenches.

## Impact

Lock-in amplifiers are essential instruments in spectroscopy, materials characterization, and sensor readout. This FPGA-based approach enables real-time, low-latency operation suitable for embedded measurement systems where commercial benchtop LIAs are impractical.
