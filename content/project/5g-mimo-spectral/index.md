---
title: "Spectral Optimization and DPD for 5G Massive MIMO Systems"
summary: "Developed spectral modeling and digital predistortion algorithms for multi-antenna 5G systems, optimizing linearity and spectral efficiency under CONACyT research grant."
tags:
  - 5G
  - Massive MIMO
  - Digital Predistortion
  - Spectral Efficiency
  - Machine Learning
date: "2022-10-01"

image:
  caption: ""
  focal_point: Smart
  preview_only: false

links:
  - icon: newspaper
    icon_pack: fas
    name: Sensors 2022 Paper
    url: https://doi.org/10.3390/s22197461
  - icon: newspaper
    icon_pack: fas
    name: ISCAS 2022 Paper
    url: https://doi.org/10.1109/ISCAS48785.2022.9937863
  - icon: book
    icon_pack: fas
    name: CRC Press Book Chapter
    url: https://doi.org/10.1201/9781003385615
---

## Overview

During my postdoctoral tenure at **Tecnológico de Monterrey** (2018–2026), supported by a **CONACyT research fellowship**, I led the development of DPD algorithms and spectral modeling techniques for **5G massive MIMO transmitter arrays**, where per-antenna PA nonlinearity and crosstalk effects degrade system-level spectral efficiency.

## Key Contributions

- Developed **surrogate behavioral models** for PA linearization under high sparse data conditions, comparing polynomial, spline, and machine learning approaches (regression trees, random forests, CNNs) for wideband nonlinear modeling.
- Designed **DPD algorithms optimized for massive MIMO architectures**, addressing the challenge of scaling linearization across large antenna arrays while managing computational complexity.
- Performed system-level spectral efficiency analysis quantifying the impact of PA nonlinearity on massive MIMO capacity, beam pattern distortion, and adjacent channel interference.
- Published results in **Sensors** (2022), **IEEE ISCAS** (2022), and contributed a **book chapter** to *Machine Learning for Complex and Unmanned Systems* (CRC Press, Taylor & Francis, 2024).
- **Advised 3 M.Sc. students** and served on Ph.D. thesis committees related to this research line.

## Tools & Technologies

MATLAB, Python (scikit-learn, TensorFlow), Keysight ADS, RF measurement testbed, statistical modeling frameworks.

## Impact

This work bridges classical RF linearization theory with modern machine learning, demonstrating that data-driven surrogate models can match or exceed conventional polynomial DPD approaches — particularly in scenarios with limited or irregularly sampled training data, which is common in multi-band and multi-antenna deployments.
