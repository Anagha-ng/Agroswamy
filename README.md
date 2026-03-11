# 🌱 Agroswamy

**IoT-Based Smart Agriculture Monitoring System**

## Overview

Agroswamy is a small-scale **IoT-based agriculture monitoring system** that collects real-time environmental and soil data to support better farming decisions. The system integrates soil sensors, a weather monitoring station, crop imaging using a camera mounted on an RC vehicle, and a basic automated irrigation mechanism.

Sensor data is processed using an **ESP32 microcontroller** and uploaded to a cloud platform (ThingSpeak) where it can be monitored remotely.

The project demonstrates how **IoT systems can be applied to agriculture for monitoring soil conditions, observing environmental changes, and automating irrigation.**

---

## System Features

### Soil Condition Monitoring

The system measures important soil parameters using sensors such as:

* Soil moisture
* Soil temperature
* Nutrient level (depending on available sensors)

These readings help determine when irrigation may be required.

---

### Weather Monitoring Station

A simple weather monitoring setup is included to observe environmental conditions affecting crop growth.

Typical parameters monitored include:

* Temperature
* Humidity
* Ambient environmental conditions

This information helps correlate soil conditions with surrounding weather patterns.

---

### Crop Health Imaging

A small **RC vehicle with a mounted camera** is used to capture images of crops from ground level. This provides a simple way to visually inspect plant conditions and identify potential issues such as pests or disease.

---

### Automated Irrigation

The system includes a basic automated irrigation mechanism:

* Soil moisture is continuously monitored
* When moisture falls below a defined threshold, irrigation can be triggered
* A relay module controls the water pump or valve

This approach helps demonstrate **sensor-based irrigation control**.

---

### Cloud Data Monitoring

Sensor readings are sent to the **ThingSpeak IoT platform** where data can be:

* Stored
* Visualized through graphs
* Accessed remotely

This allows users to observe farm conditions without being physically present.

---

## System Workflow

1. Sensors collect soil and environmental data.
2. The ESP32 reads and processes the sensor values.
3. Data is transmitted to the ThingSpeak cloud platform.
4. If soil moisture drops below a threshold, the irrigation system can be activated.
5. The RC vehicle can be used to capture crop images for manual inspection.

---

## Hardware Components

| Component             | Purpose                                      |
| --------------------- | -------------------------------------------- |
| ESP32 Microcontroller | Central processing and IoT connectivity      |
| Soil Moisture Sensor  | Detects soil water content                   |
| Temperature Sensor    | Monitors soil/environment temperature        |
| Weather Sensors       | Monitor surrounding environmental conditions |
| Camera Module         | Crop imaging                                 |
| RC Car Platform       | Ground-level crop monitoring                 |
| Relay Module          | Controls irrigation pump                     |
| Water Pump / Valve    | Irrigation actuation                         |

---

## Software & Tools

* **Embedded C / Arduino IDE** – firmware development
* **ThingSpeak** – cloud data logging and visualization
* **ESP32 WiFi connectivity** – IoT communication
---

## Project Goal

The goal of this project is to explore how **sensor networks, IoT communication, and basic automation** can be combined to support monitoring and decision-making in agriculture.

---

## Author

**Anagha NG**
