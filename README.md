# Analog CMOS Amplifier & OTA Design in Cadence

## Overview
This repository documents a series of analog CMOS circuit design and simulation studies completed as part of the Advanced CMOS Technology coursework during my Engineering Doctorate at Eindhoven University of Technology (TU/e).

The work progresses from a self-biased common-source amplifier to a two-stage current-mirror operational transconductance amplifier (OTA), and finally to a fully differential OTA with common-mode feedback (CMFB). The designs explore transistor-level circuit design, gain and bandwidth optimization, frequency and transient response, stability and compensation, distortion analysis, and PVT performance.

The project was developed using Cadence for circuit design and simulation, with emphasis on understanding the trade-offs between gain, bandwidth, stability, linearity, and power consumption in analog CMOS circuits.

## Design Studies
### 1. Common-Source Amplifier

Designed and simulated a common-source CMOS amplifier using an NMOS transistor, PMOS active load, and self-biasing feedback. The design targeted a low-frequency gain of at least 30 dB and a 3 dB bandwidth of 10 MHz while driving a 100 fF capacitive load.

The PMOS active load was used to provide high output impedance, while resistive feedback established the DC operating point. Transistor dimensions were adjusted to balance gain, bandwidth, linearity, and power consumption.

**Key analyses:**
- AC analysis and Bode-plot verification
- Transient response and settling behavior
- Slew-rate calculation
- Harmonic distortion analysis (HD2 and HD3)
- Signal-to-distortion ratio (SDR)
- Noise and SNDR analysis

**Selected results:**
- Low-frequency gain: **30 dB**
- 3 dB bandwidth: **11 MHz**
- Calculated slew rate: **1.0384 V/ns**
- HD2: **35.48 dB**
- HD3: **32.13 dB**
- SDR: **30.48 dB**
### 2. Current-Mirror OTA
### 3. Fully Differential OTA with CMFB

## Design & Simulation Workflow

## Tools & Methods

## Key Results

## Repository Structure

## Academic Context
