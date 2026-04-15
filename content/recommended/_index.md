---
title: Recommended Resources
subtitle: Books, tools, and courses for RF, FPGA, and DSP work
summary: Curated resources I use and recommend for digital predistortion, FPGA design, and RF systems.
type: page
---

Below are resources I have personally used throughout my research and professional career. These have been instrumental in my work on digital predistortion, FPGA design, and RF systems.

---

## Books

### RF & Power Amplifiers

- **RF Power Amplifiers for Wireless Communications** — *Steve C. Cripps* — The definitive reference for PA design and linearization. Essential for anyone working on DPD.
- **Microwave Engineering** — *David M. Pozar* — Comprehensive coverage of RF/microwave fundamentals, transmission lines, and network analysis.
- **RF Power Amplifier Behavioral Modeling** — *Fadhel M. Ghannouchi & Oualid Hammi* — Directly relevant to Volterra, memory polynomial, and NARMA modeling techniques.

### FPGA & Digital Design

- **RTL Hardware Design Using VHDL** — *Pong P. Chu* — Excellent practical guide for synthesizable VHDL, from basics to advanced FSM design.
- **FPGA Prototyping by VHDL Examples** — *Pong P. Chu* — Hands-on projects that bridge theory and implementation.
- **Digital Design and Computer Architecture** — *Harris & Harris* — Clear introduction to digital design principles and processor architecture.

### Signal Processing

- **Understanding Digital Signal Processing** — *Richard G. Lyons* — The most accessible DSP reference, covers fixed-point arithmetic essential for FPGA work.
- **Digital Signal Processing: Principles, Algorithms and Applications** — *Proakis & Manolakis* — In-depth theoretical treatment of DSP fundamentals.

---

## Software & Tools

| Tool | Use Case | Link |
|---|---|---|
| **MATLAB** | PA modeling, DPD algorithm development, fixed-point simulation | [mathworks.com](https://www.mathworks.com/) |
| **Intel Quartus Prime** | FPGA synthesis, place & route, timing analysis | [intel.com](https://www.intel.com/content/www/us/en/products/details/fpga/development-tools/quartus-prime.html) |
| **ModelSim / QuestaSim** | HDL simulation and verification | [siemens.com](https://eda.sw.siemens.com/en-US/ic/modelsim/) |
| **Keysight ADS** | RF circuit simulation, load-pull, system-level design | [keysight.com](https://www.keysight.com/us/en/products/software/pathwave-design-software/pathwave-advanced-design-system.html) |
| **Python + NumPy/SciPy** | Signal processing, data analysis, automation | [python.org](https://www.python.org/) |
| **Git + GitHub** | Version control for HDL and research code | [github.com](https://github.com/) |

---

## Online Courses & Learning

- **FPGA Design for Embedded Systems** (Coursera, University of Colorado) — Solid introduction to FPGA design flow and HDL coding.
- **DSP Specialization** (Coursera, EPFL) — Rigorous treatment of digital signal processing with practical MATLAB exercises.
- **RF and Millimeter-Wave Circuit Design** (edX) — Covers high-frequency circuit design principles.

---

## FPGA Development Boards

For researchers and students getting started with FPGA prototyping:

| Board | Description | Best For |
|---|---|---|
| **Intel DE10-Nano** | Affordable Cyclone V SoC, ARM + FPGA | DSP and embedded Linux projects |
| **Xilinx/AMD Zybo Z7** | Zynq-7000 SoC with dual-core ARM | HW/SW co-design |
| **Lattice iCE40** | Ultra-low-cost, open-source toolchain support | Learning digital design fundamentals |

---

*Some links on this page are affiliate links. If you purchase through them, I may receive a small commission at no extra cost to you. I only recommend products I have personally used and trust.*
