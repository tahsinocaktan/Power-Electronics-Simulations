# Power Electronics Circuit (2023-2024/ELK 331)

## Overview

This repository contains MATLAB/Simulink models for two assignments related to Power Electronics Circuits (ELK331) from Istanbul Technical University - 2023-2024 Fall Semester. The assignments cover the simulation of rectifiers, choppers, and inverters, using Simscape -> Electrical -> Specialized Power Systems toolbox

## Assignments

### **1. Power Electronics Circuits Assignment 1**

**Topics Covered:**

- **Three-Phase Controlled Full-Wave Rectifier** feeding a resistive load
- **Single-Phase AC Chopper** feeding an RL load

**Simulink Models Include:**

- Waveform analysis of input/output voltages and currents
- Computation of RMS and average values for voltages and currents
- Calculation of ripple factor and form factor for output voltage
- Use of **powergui** block for proper simulation setup

### **2. Power Electronics Circuits - Assignment 2**

**Topics Covered:**

- **Buck-Boost Converter** operating at 40 kHz
- **Single-Phase Half-Bridge Square-Wave Inverter** feeding R and RL loads

**Simulink Models Include:**

- Selection of appropriate MOSFET with datasheet verification
- Duty cycle variation and impact on voltage/current waveforms
- Switching frequency effect on inverter performance
- Total Harmonic Distortion (THD) analysis

## How to Use

1. Open MATLAB and navigate to the repository folder.
2. Run `assignment1.slx` for **rectifier and AC chopper simulations**.
3. Run `assignment2.slx` for **buck-boost converter and inverter simulations**.

## Dependencies

- MATLAB/Simulink (Recommended version: 2021b or later)
- Simscape Electrical Toolbox
- Power Systems Specialized Library

---

This repository provides MATLAB/Simulink implementations for fundamental power electronics circuits. Contributions and improvements are welcome!


