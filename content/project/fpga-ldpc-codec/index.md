---
title: "FPGA-Based LDPC Encoder/Decoder with UVM Verification"
summary: "Designed and verified FPGA-based LDPC codec and AWGN channel module for 5G NR forward error correction, developed for SAGE Microelectronics."
tags:
  - FPGA
  - LDPC
  - 5G NR
  - UVM
  - SystemVerilog
  - Forward Error Correction
date: "2023-06-01"

image:
  caption: ""
  focal_point: Smart
  preview_only: false

links:
  - icon: microchip
    icon_pack: fas
    name: SAGE Microelectronics
    url: "#"
---

## Overview

As part of a collaboration with **SAGE Microelectronics** at **Tecnológico de Monterrey**, I designed and verified FPGA-based modules for **5G NR forward error correction (FEC)**, including an LDPC encoder, decoder, and an additive white Gaussian noise (AWGN) channel emulator for hardware-in-the-loop testing.

## Key Contributions

- Designed an **LDPC encoder** supporting 5G NR base graph configurations (BG1/BG2) with configurable code rates and lifting sizes, optimized for throughput on Altera/Intel FPGA platforms.
- Implemented a **layered min-sum LDPC decoder** architecture with early termination, balancing decoding performance against hardware resource utilization.
- Developed an **FPGA-based AWGN generator** module using the Box-Muller method in fixed-point arithmetic, enabling real-time channel emulation for BER testing without external instrumentation.
- Built a complete **UVM (Universal Verification Methodology)** testbench environment in SystemVerilog for functional coverage-driven verification of all codec modules, including scoreboard comparison against golden reference models.

## Tools & Technologies

SystemVerilog, UVM, VHDL, Quartus Prime, ModelSim, MATLAB (golden reference and BER analysis), Intel/Altera Cyclone FPGA.

## Impact

This project delivered production-quality IP blocks for 5G NR physical layer processing, demonstrating the full RTL-to-verification pipeline from specification through coverage closure.
