---

# Gyroscope Operation and Data Analysis

This repository contains code and analysis for operating a laser-based gyroscope and conducting measurements related to cavity resonances and rotation rates.

## Overview

### Task A: Operation of the Gyroscope
- **Cavity Resonance Measurement**: Set up the laser and AOM driver, scan for resonances, and analyze the cavity's free-spectral-range (FSR) and perimeter.
- **Error Signal Generation**: Create and record error signals for cavity locking, estimate the slope of the PDH error signal, and adjust the PID parameters for stability.
- **Cavity Finesse Measurement**: Measure the finesse using the cavity ring-down technique.

### Task B: Scale Factor Measurement
- Measure rotation rates using a rotary encoder and analyze the Sagnac beat signal. Calculate the scale factor by comparing rotation rates and Sagnac frequency.

### Task C: Allan Deviation
- Measure the Sagnac frequency over time and calculate Allan deviation to evaluate the gyroscope’s sensitivity.

### Task D: Measuring Earth's Rotation Rate
- Estimate the gyroscope's lock-in threshold and propose a measurement strategy using dithering.

## Setup and Usage
### Requirements:
- Python 3.x, NumPy, SciPy, Matplotlib, Picoscope API.

### Running the Code:
1. Set up the experimental apparatus and acquire the relevant data.
2. Use the provided Python scripts for data analysis.
3. Follow the Jupyter notebooks for step-by-step instructions.

## Acknowledgements
This work was conducted under the guidance of Prof. Dr. Simon Stellmer as part of the Matter & Light for Quantum Computing (ML4Q) excellence cluster.

---
