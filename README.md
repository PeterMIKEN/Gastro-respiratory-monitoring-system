# Gastro-Respiratory Monitoring System

## Overview

A prototype biomedical monitoring system designed to simultaneously
acquire, process and visualize gastrointestinal and respiratory signals
using multimodal sensing, embedded processing and wireless communication.

The system integrates:

- Piezoelectric sensing for gastrointestinal activity
- Resistive sensing for respiratory movement
- Analog signal conditioning
- ESP32-based signal acquisition and processing
- MATLAB-based signal modelling and analysis
- Wi-Fi/UDP communication
- Web-based real-time visualization
- Gastro-respiratory signal correlation analysis

## Research Objective

The project investigates the feasibility of simultaneously monitoring
gastrointestinal and respiratory activity using a low-cost embedded
biomedical instrumentation architecture.

## System Architecture

<img width="1201" height="659" alt="block diagram" src="https://github.com/user-attachments/assets/e8990aa4-a862-4688-85c2-b7a206e60664" />


## Hardware

- ESP32
- Piezoelectric sensor
- Resistive respiratory sensor
- LM358 signal-conditioning circuitry
- Supporting passive components

## Software

- MATLAB
- ESP32 firmware
- Web interface
- JavaScript/Chart.js
- WebSocket communication

## Signal Processing

The project uses MATLAB to model physiological signals and investigate
filtering and signal-conditioning requirements before implementation
on the embedded platform.

## Results

<img width="700" height="627" alt="simulated signals" src="https://github.com/user-attachments/assets/59e1cc32-b28c-4404-b495-d5fd1c4e00b4" />
<img width="1844" height="736" alt="correlation graph" src="https://github.com/user-attachments/assets/eb2b960e-d2d2-4ee3-9bf3-8e548ba199e4" />
<img width="1575" height="814" alt="dashboard" src="https://github.com/user-attachments/assets/39a76bf9-1d4f-4afc-b81b-24f751a8e7d0" />


## Validation Status

The prototype was evaluated using simulated physiological signals.
Clinical validation using human physiological data was outside the
scope of the current prototype.

## Research Publication

DOI: https://doi.org/10.5281/zenodo.22914361

## Author

**Miken Peter Changera**

Biomedical Engineer

Kenya

## Repository Contents

- Project report
- MATLAB models
- Embedded firmware
- Hardware documentation
- Signal-processing material
- Results
