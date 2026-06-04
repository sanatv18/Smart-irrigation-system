# ESP32-Integrated Smart Irrigation System With Soil Moisture Regulation

## Overview

This project presents a smart irrigation system built using the ESP32 microcontroller for automated and efficient water management. The system continuously monitors soil moisture, temperature, humidity, and water flow, enabling intelligent irrigation decisions with minimal human intervention.

Unlike many cloud-dependent irrigation systems, this solution operates in ESP32 Access Point (AP) mode, allowing users to monitor and control irrigation through a local web dashboard without requiring internet connectivity.

## Patent Information

This project is associated with a published patent application.

**Title:** ESP32-Integrated Smart Irrigation System With Soil Moisture Regulation

**Inventors:**
- Dr. Kathirvelan J
- Ankit Agrawal
- Sanat Vasisht
- Garv Khullar

**Institution:** Vellore Institute of Technology (VIT), Vellore :contentReference[oaicite:1]{index=1}

## Key Features

- Automated irrigation based on soil moisture levels
- ESP32 Wi-Fi Access Point (AP) mode
- Local web dashboard for monitoring and control
- Capacitive soil moisture sensing
- DHT11 temperature and humidity monitoring
- YF-S201 water flow monitoring
- Relay-controlled solenoid valve automation
- Real-time sensor data visualization
- Internet-independent operation
- Low-cost and scalable architecture

## Hardware Components

- ESP32 Development Board
- Capacitive Soil Moisture Sensor
- DHT11 Temperature & Humidity Sensor
- YF-S201 Flow Sensor
- Relay Module
- Solenoid Valve
- Power Supply Unit

## System Architecture

Sensors:
- Soil Moisture Sensor
- DHT11 Temperature & Humidity Sensor
- YF-S201 Flow Sensor

Controller:
- ESP32 Microcontroller

Actuation:
- Relay Module
- Solenoid Valve

Interface:
- ESP32 Hosted Web Dashboard

## Working Principle

1. Soil moisture is continuously monitored.
2. Sensor data is processed by the ESP32.
3. When moisture falls below the predefined threshold:
   - Relay activates.
   - Solenoid valve opens.
4. Water flow is monitored using the YF-S201 sensor.
5. Irrigation automatically stops once the desired moisture level is reached.
6. Users can monitor all parameters through the local ESP32 web interface.

## Applications

- Smart Agriculture
- Precision Farming
- Greenhouses
- Nurseries
- Home Gardens
- Terrace Farming
- Urban Landscaping
- Agricultural Research

## Experimental Results

The developed prototype demonstrated:

- Soil moisture detection accuracy within ±3%
- Flow measurement accuracy within ±5%
- Relay response time of 200–300 ms
- Water savings of approximately 30–45%
- Reliable operation without internet connectivity

## Repository Structure

```
├── Source_Code/
├── Hardware_Design/
├── Documentation/
├── Images/
├── Simulation_Results/
└── README.md
```

## Intellectual Property Notice

This repository contains material related to a published patent application.

The source code, schematics, documentation, and project materials are provided for educational and research purposes only.

Publication of this repository does not grant any license or permission to commercially exploit patented claims associated with this invention.

## Authors

- Dr. Kathirvelan J
- Ankit Agrawal
- Sanat Vasisht
- Garv Khullar

## License

For academic and research use only.

Please contact the inventors and/or VIT before commercial implementation.
