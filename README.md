<p align="center">
  <img src="logo.png" alt="Project Logo" width="200"/>
</p>

<h1 align="center">SpectralRelay: A Ghost Hunting Device</h1>

SpectralRelay is a software-defined radio (SDR)-based tool designed for scanning and analyzing radio frequencies. Originally envisioned for paranormal investigations, this project is a versatile solution capable of sweeping through different frequency ranges, processing live radio signals, and converting them into audible formats. Users will be able to listen to real-time audio feed and analyze logged data for further analysis.

## Table of Contents
- [How It Works](#how-it-works)
- [Features](#features)
- [Hardware](#hardware)
- [Usage](#usage)
- [License](#license)

---
## How It Works

The concept behind Spectral Relay is based on the theory that spirits or ghosts may communicate through radio frequencies. This theory suggests that when a spirit chooses to speak, its voice can be heard on any frequency the device is tuned to.

Spectral Relay continuously sweeps through FM, AM, and other frequency ranges to detect such occurrences. If a voice is heard consistently across multiple frequencies during a sweep, it is interpreted as a potential spirit communication.

All audio is recorded, allowing for detailed analysis at a later time. Additionally, the specific frequencies over which the voice is detected are logged, enabling users to identify patterns or correlations that may emerge in spirit communications.

---

## Features

### Dual Confirmation Mechanism
The device confirms the presence of a spirit through two simultaneous criteria:
1. **Touch Detection**:
   - The TTP223B Capacitive Touch Sensor detects physical contact.
2. **Temperature Anomaly**:
   - The two front DHT22 sensors register a temperature colder than the environmental temperature recorded by the back DHT22 sensor.

This dual confirmation system helps minimize false positives and ensures reliable detection.

---

## Hardware

### Parts List
- 3x DHT22 Sensors
- 1x 9V Battery
- 1x 9V Battery Case
- 1x TTP223B Capacitive Touch Sensor
- 1x Arduino Nano
- 2x Green LEDs
- 2x 220 Ohm Resistors

### Hardware Setup
![alt text](https://github.com/MBarc/Ghost-Hunting-PhantomSense/blob/main/PhantomSenseDiagram.png)
---

## Usage
1. Power on the device.
2. Monitor the green LEDs on the device. You have a positive reading when both LEDs are lit up.

---

## License
This project is licensed under the [MIT License](LICENSE).
