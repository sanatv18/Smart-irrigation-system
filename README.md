# Smart Irrigation System with Soil Moisture Monitoring and WiFi-Based Control

## Overview

The Smart Irrigation System is an IoT-enabled agricultural automation solution designed to optimize water usage through real-time soil moisture monitoring and automated irrigation control. The system utilizes an ESP32 microcontroller operating in WiFi Access Point (AP) mode, allowing users to monitor and control irrigation through a local web dashboard without requiring internet connectivity.

The system integrates multiple sensors, including a capacitive soil moisture sensor, DHT11 temperature and humidity sensor, and YFS201 flow sensor, to provide intelligent irrigation decisions and efficient water management.

---

## Features

* Automated irrigation based on soil moisture levels
* ESP32 WiFi Access Point (AP) mode operation
* Real-time monitoring through onboard web dashboard
* Soil moisture sensing
* Temperature and humidity monitoring using DHT11
* Water flow measurement using YFS201 flow sensor
* Relay-controlled solenoid valve actuation
* Offline operation without internet dependency
* Low-cost and scalable architecture

---

## Hardware Components

* ESP32 Development Board
* Capacitive Soil Moisture Sensor
* DHT11 Temperature & Humidity Sensor
* YFS201 Water Flow Sensor
* Relay Module
* Solenoid Valve
* LCD Display
* Water Reservoir
* Power Supply

---

## Software & Tools

* Arduino IDE
* ESP32 WiFi Library
* Embedded C/C++
* EasyEDA (Circuit Design)
* HTML/CSS Web Dashboard

---

## System Architecture

```text
Soil Moisture Sensor
          │
DHT11 Sensor ──► ESP32 Controller ◄── YFS201 Flow Sensor
          │
          ▼
    Relay Module
          │
          ▼
    Solenoid Valve
          │
          ▼
   Irrigation Control

ESP32 AP Mode
          │
          ▼
 Local Web Dashboard
```

---

## Working Principle

1. The soil moisture sensor continuously monitors soil conditions.
2. The ESP32 processes sensor readings and compares them with predefined thresholds.
3. When moisture levels fall below the threshold, the relay activates the solenoid valve.
4. Water flow is monitored using the YFS201 flow sensor.
5. Temperature and humidity data are collected through the DHT11 sensor.
6. Users can view sensor data and control irrigation using the ESP32-hosted web dashboard.
7. Once the desired moisture level is reached, irrigation is automatically stopped.

---

## Applications

* Agriculture and Farming
* Home and Terrace Gardens
* Greenhouses and Nurseries
* Urban Landscaping
* Horticulture Research
* Rural and Remote Agricultural Areas
* IoT and Embedded Systems Education Projects

---

## Experimental Results

The system was tested under multiple environmental and soil conditions.

### Key Results

* Soil moisture monitoring accuracy within ±3%
* Flow sensor accuracy within ±5%
* Relay and solenoid valve response time of 200–300 ms
* Reliable ESP32 AP-mode connectivity
* Water savings of approximately 30–45% compared to manual irrigation
* Stable long-term operation without false triggering

---

## Technical Advancements

* Offline WiFi AP-mode operation
* Multi-sensor fusion (Moisture + DHT11 + Flow Sensor)
* Onboard ESP32 Web Server
* Real-time monitoring without cloud dependency
* Compact and low-cost implementation

---

## Future Improvements

* Mobile application integration
* Cloud-based analytics dashboard
* Weather forecast integration
* Machine learning-based irrigation scheduling
* Solar-powered operation
* Multi-zone irrigation support

---

## Project Team

**Sanat Vasisht**
24BEC0411

Department of Electronics and Communication Engineering

Vellore Institute of Technology (VIT)

---

## License

This project is developed for academic, educational, and research purposes.
