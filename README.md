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

The concept behind SpectralRelay is based on the theory that spirits or ghosts may communicate through radio frequencies. This theory suggests that when a spirit chooses to speak, its voice can be heard on any frequency the device is tuned to.

SpectralRelay continuously sweeps through FM, AM, and other frequency ranges to detect such occurrences. If a voice is heard consistently across multiple frequencies during a sweep, it is interpreted as a potential spirit communication.

All audio is recorded, allowing for detailed analysis at a later time. Additionally, the specific frequencies over which the voice is detected are logged, enabling users to identify patterns or correlations that may emerge in spirit communications.

---

## Features

- Frequency Scanning: Configurable start, stop, and sweep speed parameters for frequency range scanning.
- Real-Time Playback: Converts and plays SDR signals as audio in real-time.
- Signal Processing: High-performance processing pipeline for turning SDR samples into magnitude-based audio signals.
- Event Logging: Logs scanned frequencies and potential anomalies for later review.
- Recorded Sessions: Audio produced by the SpectralRelay is recorded for further analysis at a later time.

---

## Hardware

### Parts List
- 1x Raspberry Pi 3b+
- 1x Speaker with 3.5mm Audio Jack
- 1x RTL2832U
- 1x R820T2
- 2x 18650 batteries

### Hardware Setup
![alt text](https://github.com/MBarc/Ghost-Hunting-PhantomSense/blob/main/PhantomSenseDiagram.png)
---

## Usage
1. Power on the device.
2. Monitor the green LEDs on the device. You have a positive reading when both LEDs are lit up.

---

## License
This project is licensed under the [MIT License](LICENSE).
