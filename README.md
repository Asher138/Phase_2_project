# Phase_2_project
The Matlab code related to the Spectral and Energy Efficiency Optimization for 5G mmWave Massive MIMO Networks

---

# Hybrid Beamforming for Energy Efficient mmWave MIMO Systems

This repository contains MATLAB code for hybrid beamforming methods, including the **Dinkelbach Method**, **PCEM**, and **Brute Force**, designed for mmWave massive MIMO systems. The code evaluates and compares these methods in terms of **spectral efficiency (SE)** and **energy efficiency (EE)**, as described in the study:

> **"Enhancing 5G: Energy Efficient Solutions for mmWave Massive MIMO Systems"**
---

## Overview

This repository implements and compares various beamforming strategies for mmWave massive MIMO systems:
1. **Dinkelbach Method**: Iterative optimization for maximizing energy efficiency using convex solvers.
2. **PCEM (Power-Controlled Energy Maximization)**: A hybrid beamforming algorithm for balancing energy and spectral efficiency.
3. **Brute Force**: A baseline method that exhaustively searches over all parameter combinations.

Key metrics include:
- **Spectral Efficiency (SE)**: Measured in bits/s/Hz.
- **Energy Efficiency (EE)**: Measured in bits/Joule.

---

## Features

- Implements **hybrid beamforming** methods for mmWave MIMO systems.
- Evaluates **energy efficiency** and **spectral efficiency** under different SNRs and configurations.
- Provides **visual comparisons** of methods (SE vs. SNR, EE vs. SNR).
- All results are reproducible and align with the data in the associated research paper.

---

## Requirements

1. **MATLAB** (R2021a or newer is recommended)
2. **CVX Toolbox** (required for the Dinkelbach Method)
   - Download CVX: [http://cvxr.com/cvx/](http://cvxr.com/cvx/)
3. Git (for cloning this repository)


## Notes

1. **CVX Dependency**:  
   The **Dinkelbach Method** requires the CVX toolbox for convex optimization. If CVX is not installed, the script will fail.  

2. **Reproducibility**:  
   All data and results are aligned with the research paper, ensuring reproducibility of findings.

3. **Performance Note**:  
   The Dinkelbach Method may exhibit slower runtimes compared to brute force due to the reliance on CVX, which is not parallelized in MATLAB.

---
## Contact

For questions, suggestions, or issues, please contact:
- Email: s2038732@ed.ac.uk

