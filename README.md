# Embedded Sensor-Based Floor Height Estimation System

An embedded system for estimating building floor height using an **ADXL335 MEMS accelerometer**. The project combines analog signal conditioning, **ATmega32**-based data acquisition, and **MATLAB** signal processing to estimate vertical displacement(Height) through numerical integration of acceleration data.

---

## Overview

This project demonstrates the complete workflow of an embedded measurement system, from sensor data acquisition to signal processing and height estimation. Acceleration data recorded during elevator motion is calibrated, filtered, and processed to calculate velocity and displacement, enabling estimation of the height between two building floors.

The project was developed as part of the **Maritime Systems Laboratory** in the **Master of Science in Embedded System Design** program at **Hochschule Bremerhaven, Germany**.

---

## Features

- ADXL335 MEMS accelerometer-based acceleration measurement
- Analog signal conditioning circuit
- Offset compensation and amplification
- Second-order active low-pass filter
- ATmega32 microcontroller-based data acquisition
- ADC sampling and UART serial communication
- MATLAB-based signal processing
- Butterworth low-pass filtering
- Offset and drift compensation
- Numerical integration for velocity estimation
- Numerical integration for displacement estimation
- Building floor height estimation

---

## Hardware

- ADXL335 MEMS Accelerometer
- ATmega32 Microcontroller
- TS272 Dual Operational Amplifier
- Analog Signal Conditioning Circuit
- Low-Pass Active Filter
- Laboratory Power Supply

---

## Software

- MATLAB
- Embedded C
- UART Communication
- ADC
- Signal Processing

---

## Methodology

Acceleration Measurement
        │
        ▼
Signal Conditioning
(Amplification + Low-Pass Filter)
        │
        ▼
ATmega32 ADC Data Acquisition
        │
        ▼
UART Data Transmission
        │
        ▼
MATLAB Signal Processing
(Calibration + Filtering + Drift Correction)
        │
        ▼
Velocity Estimation
(Numerical Integration)
        │
        ▼
Displacement Estimation
(Second Numerical Integration)
        │
        ▼
Building Floor Height Estimation
---

## Results

The developed system successfully estimated the height between the second and third floors of the T-Building at Hochschule Bremerhaven.

**Estimated Floor Height:** **3.94 m**

---


## Technologies

- Embedded Systems
- Embedded C
- MATLAB
- Signal Processing
- Analog Circuit Design
- ADC
- UART
- MEMS Sensors
- Numerical Integration
- Digital Filtering

---



