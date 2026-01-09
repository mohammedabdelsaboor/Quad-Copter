# Quadcopter UAV – ArduPilot-Based Aerial Robotics Platform

This repository documents the design and implementation of a quadcopter unmanned aerial vehicle (UAV) developed for autonomous navigation and first-person view (FPV) control.  
The system is based on the ArduPilot open-source autopilot platform and is designed as a stable and modular aerial robotics platform suitable for research, experimentation, and educational applications.

---

## System Overview

The quadcopter integrates flight control, propulsion, communication, and video systems to support both manual and autonomous flight modes.  
It utilizes a brushless motor propulsion system, electronic speed controllers, LiPo-based power supply, and real-time FPV video transmission.

The platform supports autonomous mission execution, waypoint navigation, and stabilized manual flight using ground control software.

---

## Hardware Specifications

### Core Flight Hardware

| Component | Specification |
|---------|---------------|
| Flight Controller | ArduPilot-compatible controller (ArduPilot 2.8) |
| Frame | X-configuration quadcopter frame |
| Motors | 920 KV brushless motors (4 units) |
| ESCs | 30A electronic speed controllers |
| Propellers | 10-inch propellers |
| Power Distribution | Integrated power distribution board (PDB) |

---

### Power System

| Component | Specification |
|---------|---------------|
| Battery Type | Lithium Polymer (LiPo) |
| Battery Rating | 3S LiPo |
| Battery Capacity | 5200 mAh |
| Nominal Voltage | 11.1 V |
| Power Delivery | Centralized PDB |

---

### Communication and Control

| Component | Specification |
|---------|---------------|
| Radio Transmitter | FlySky FS-i6 |
| Receiver | FlySky iA6B |
| Channels | 6-channel radio link |
| Telemetry | RC-based control and monitoring |

---

### FPV and Vision System

| Component | Specification |
|---------|---------------|
| Camera | Fixed onboard FPV camera |
| Video Transmitter | 5.8 GHz analog VTX |
| Video Feed | Real-time analog transmission |
| Ground Station | FPV receiver and display |

---

## Software Architecture

| Software Component | Description |
|------------------|-------------|
| Autopilot Firmware | ArduPilot |
| Ground Control Station | Mission Planner / QGroundControl |
| Configuration | PID tuning, sensor calibration, flight modes |
| Telemetry | Real-time flight data and monitoring |

---

## Supported Flight Modes

| Mode | Description |
|----|-------------|
| Manual | Direct pilot control |
| Stabilize | Attitude-stabilized flight |
| Alt Hold | Automatic altitude control |
| Loiter | GPS-based position hold |
| Auto | Fully autonomous mission execution |

---

## Final Notes

This quadcopter UAV serves as a practical and scalable aerial robotics platform that combines embedded systems, control theory, and real-world flight dynamics.  
It is well-suited for both academic experimentation and hands-on UAV development using the ArduPilot ecosystem.
