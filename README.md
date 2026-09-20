# Analog CMOS Amplifier & OTA Design in Cadence

## Overview
This repository documents a series of analog CMOS circuit design and simulation studies completed as part of the Advanced CMOS Technology coursework during my Engineering Doctorate at Eindhoven University of Technology (TU/e).

The work progresses from a self-biased common-source amplifier to a two-stage current-mirror operational transconductance amplifier (OTA), and finally to a fully differential OTA with common-mode feedback (CMFB). The designs explore transistor-level circuit design, gain and bandwidth optimization, frequency and transient response, stability and compensation, distortion analysis, and PVT performance.

The project was developed using Cadence for circuit design and simulation, with emphasis on understanding the trade-offs between gain, bandwidth, stability, linearity, and power consumption in analog CMOS circuits.

## Design Studies
### 1. Common-Source Amplifier

Designed and simulated a self-biased common-source CMOS amplifier in Cadence Virtuoso. The design was evaluated for gain, bandwidth, transient response, slew rate, and harmonic distortion.

**Design targets:**
- Low-frequency gain ≥ 30 dB
- 3 dB bandwidth ≈ 10 MHz
- Load capacitance: 100 fF
- Source resistance: 10 Ω
- SDR target: ≥ 40 dB for a 10 mV peak-to-peak input at 1 MHz

**Selected results:**
- Low-frequency gain: ≈ 30 dB
- 3 dB bandwidth: ≈ 11.5 MHz
- Slew rate: ≈ 1.04 V/ns
- HD2: ≈ 35.48 dB
- HD3: ≈ 32.13 dB
- SDR: ≈ 30.48 dB

#### Circuit Schematic

![Common-source amplifier schematic](common-source-amplifier/figures/schematic.png)

*Transistor-level implementation of the self-biased common-source amplifier in Cadence Virtuoso.*

#### Frequency Response

![Common-source amplifier frequency response](common-source-amplifier/figures/frequency-response.png)

*AC simulation showing approximately 30 dB low-frequency gain and the 3 dB bandwidth near 11.5 MHz.*

#### Transient Response

![Common-source amplifier transient response](common-source-amplifier/figures/transient-response.png)

*Time-domain simulation used to evaluate the amplifier response to a sinusoidal input.*

#### Slew-Rate Analysis

![Common-source amplifier slew-rate analysis](common-source-amplifier/figures/slew-rate.png)

*Step-response simulation used to evaluate large-signal settling behavior and slew rate.*

#### Distortion Analysis

![Common-source amplifier distortion analysis](common-source-amplifier/figures/distortion-analysis.png)

*Frequency-domain analysis of the fundamental and harmonic components used to evaluate distortion performance.*
### 2. Current-Mirror OTA
### 3. Fully Differential OTA with CMFB

## Design & Simulation Workflow

## Tools & Methods

## Key Results

## Repository Structure

## Academic Context
