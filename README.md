# Air-Ground-Collaborative-Intelligent-Firefighting-System

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/Platform-Jetson%20Orin%20Nano%20Super-brightgreen)](https://www.nvidia.com/)
[![ROS2](https://img.shields.io/badge/ROS2-Humble-blue)](https://docs.ros.org/en/humble/)

## About
An air‑ground cooperative firefighting robot designed for autonomous operation in GNSS‑denied environments. The system consists of a ground unmanned vehicle (UGV) with omnidirectional base, 6‑DOF manipulator, multi‑sensor suite (RGB‑D, LiDAR, microphone array, gas sensors), and an onboard NVIDIA Jetson Orin Nano Super edge AI compute module. An aerial scout drone provides video streaming and telemetry. The goal is zero‑human‑intervention fire suppression with a four‑level safety interlock.

An air‑ground cooperative firefighting robot designed for autonomous operation in GNSS‑denied environments. Built under the following constraints: **[ABET](https://www.abet.org) capstone standards**, **[FCC](https://www.fcc.gov)/[CE](https://ec.europa.eu/growth/single-market/ce-marking_en) electromagnetic compliance**, and a **[$1500 total BOM budget](docs/BOM.md)**.

## Technologies

- **Compute**: NVIDIA Jetson Orin Nano Super (67 TOPS INT8, 15W)
- **MCUs**: STM32F407VET6 ×2 (FreeRTOS, 1kHz control loops)
- **AI Framework**: Ollama-DeepSeek, YOLOv8
- **ROS**: ROS 2 Humble
- **Communication**: Protobuf‑UART, 5.8 GHz WiFi Module, 915 MHz LoRa Module
- **Sensors**: Astra RGB‑D, Leishen M10P LiDAR, M260C mic array, MQ‑2/MQ‑5

## License

MIT License. See [LICENSE](LICENSE) for details.

Vendor‑supplied firmware and drivers retain their original licenses.

## Acknowledgments
- Lafayette College ECE Department
- NVIDIA Jetson Edge AI Program
- WHEELTEC
- ROS and open‑source community

 ## ChangeLogs
See [CHANGELOG.md](CHANGELOG.md) for version history.
