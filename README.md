# Quadcopter UAV – ArduPilot-Based Aerial Robotics Platform

This repository documents the design and implementation of a quadcopter unmanned aerial vehicle (UAV) developed for autonomous navigation and first-person view (FPV) control. The system is based on the ArduPilot open-source autopilot software and is equipped with a stable hardware platform suitable for research, experimentation, and educational use.

## System Overview

The quadcopter integrates essential flight control, communication, and vision systems to enable both manual and autonomous operation. It features brushless propulsion, a remote radio link, LiPo-based power supply, and real-time video transmission.

## Hardware Specifications

- **Flight Controller**: ArduPilot-compatible flight controller  
- **Motors**: 920 KV brushless motors (4 units)  
- **Electronic Speed Controllers (ESCs)**: 30A ESCs  
- **Propellers**: 10-inch propellers  
- **Battery**: 3-cell LiPo battery  
- **Radio System**: FlySky FS-i6 transmitter with iA6B receiver  
- **FPV System**: Fixed onboard FPV camera with 5.8 GHz video transmitter  
- **Frame**: X-configuration quadcopter frame  
- **Power Distribution**: Central PDB integrated into frame design  

## Software Architecture

- **Autopilot Firmware**: ArduPilot  
- **Ground Control Software**: Mission Planner or QGroundControl  
- **Flight Modes**: Manual, Stabilize, Alt Hold, Loiter, and Auto  
- **Radio Communication**: 6-channel telemetry via FlySky FS-i6  
- **Video Transmission**: Analog FPV feed to ground-based receiver  
