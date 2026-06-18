# Integration of Weight Monitoring and Micro Weather Monitoring for Indirect Solar Dehydration Using Raspberry Pi

## Overview

This project presents an IoT-based monitoring system for an indirect solar dehydrator. The system continuously monitors environmental conditions and product weight during the drying process using Raspberry Pi. Real-time data is collected from multiple sensors and transmitted to cloud platforms using MQTT for remote monitoring and analysis.

The primary objective is to improve drying efficiency, reduce post-harvest losses, and maintain product quality through intelligent monitoring and data-driven decision making.

---

## Problem Statement

Traditional open-sun drying methods suffer from:

- Contamination and quality degradation
- Uneven drying
- Dependence on weather conditions
- Lack of real-time monitoring
- Manual observation and inaccurate moisture tracking

This project addresses these challenges through an integrated monitoring solution.

---

## Objectives

- Monitor temperature and humidity in real time
- Measure solar radiation levels
- Monitor wind speed and wind direction
- Track product weight loss using load cells
- Transmit sensor data to cloud platforms
- Enable remote monitoring and visualization
- Improve drying efficiency and product quality

---

## System Architecture

Sensors
↓
RS485 Communication
↓
Modbus Protocol
↓
Raspberry Pi
↓
MQTT Protocol
↓
Cloud Platform (ThingSpeak / AWS)

---

## Hardware Components

### Environmental Monitoring

- Temperature & Humidity Sensor (SHT31)
- Wind Speed Sensor
- Wind Direction Sensor
- Rain Gauge Sensor
- Solar Radiation Sensor

### Weight Monitoring

- Load Cell
- HX711 Amplifier Module

### Processing & Communication

- Raspberry Pi
- RS485 Communication Module
- ESP8266 (Validation Testing)

### Power System

- Multi-Output Power Board
- XL6009 DC-DC Converter

### Drying System

- Indirect Solar Collector
- Drying Chamber
- Forced Air Blower
- Drying Trays

---

## Software & Technologies

### Programming

- Python
- Embedded C

### Communication Protocols

- MQTT
- Modbus
- RS485

### Cloud Platforms

- ThingSpeak
- AWS

### Development Tools

- VS Code
- Arduino IDE

---

## Features

- Real-time environmental monitoring
- Continuous weight monitoring
- Cloud-based visualization
- MQTT-based data transmission
- Remote monitoring
- Drying performance analysis
- Data logging and storage
- Scalable architecture

---

## Experimental Setup

The indirect solar dehydrator consists of:

- Solar air collector
- Drying chamber with multiple trays
- Forced airflow blower
- Environmental monitoring station
- Raspberry Pi based monitoring system

Carrot slices were used as the sample product for dehydration experiments.

---

## Results

### Key Observations

- Continuous reduction in weight confirmed moisture removal.
- Higher temperatures increased drying rates.
- High humidity reduced drying efficiency.
- Uniform drying achieved through controlled airflow.
- Improved product quality compared to traditional drying methods.

### Project Achievements

- Real-time monitoring system successfully developed.
- Cloud-based monitoring implemented.
- More than 90,000 sensor samples collected.
- Efficient moisture tracking using load-cell monitoring.
- Improved drying efficiency and reliability.

---

## Applications

### Agriculture

- Vegetable drying
- Fruit dehydration
- Grain preservation

### Export Industry

- USA
- Europe
- UAE
- Saudi Arabia

### Remote Areas

- Rural farming communities
- Cold and hill regions
- Areas with limited storage facilities

---

## Future Scope

- Automatic drying control system
- AI-based drying prediction
- Mobile application integration
- Solar-powered standalone operation
- Advanced analytics and machine learning

---

## Repository Structure

```
Solar-Dehydrator-RPi/
│
├── README.md
├── docs/
├── images/
├── hardware/
├── software/
├── data/
├── reports/
└── presentations/
```

---

## Team Members

- M. Narendra
- B. Hemanth Kumar
- I. Dilip Kumar
- P. Kamakshi Prasad

### Guide

Dr. P. Murugapandiyan

Department of Electronics and Communication Engineering

Anil Neerukonda Institute of Technology and Sciences (ANITS)

---

## License

This project is developed for academic and research purposes.
