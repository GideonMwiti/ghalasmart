# 🌾 Ghala-Smart: Autonomous Off-Grid Grain Preservation System

![Project Status](https://img.shields.io/badge/Status-Hackathon%20Prototype-orange)
![Category](https://img.shields.io/badge/Category-IoT%20%26%20AgriTech-success)

## 📌 Project Overview
[cite_start]**Ghala-Smart** is a youth-led grassroots engineering solution developed under Sericsoft Innovations Ltd. by a Kisii University team[cite: 149, 151, 158]. [cite_start]It is an intelligent, off-grid IoT monitoring and active-ventilation system that upgrades any standard grain silo into a "smart storage" unit[cite: 159].

## 🚀 The Problem & Solution
* [cite_start]**The Problem:** Small-scale farmers in rural Kenya lose up to 30% of their maize to post-harvest rot and aflatoxin contamination because traditional silos offer no early warning systems[cite: 153, 154].
* [cite_start]**The Solution:** An automated intervention system that continuously monitors the internal microclimate and activates ventilation to prevent spoilage, operating independently of internet access and reliable electricity[cite: 156, 160].

## 🛠️ Technical Architecture & Hardware
[cite_start]The system is built on a robust, locally serviceable hardware stack[cite: 162]:
* [cite_start]**The Senses (Sensors):** A DHT22 sensor tracks internal temperature and humidity, an MQ-135 gas sensor detects early fermentation gases, and an HC-SR04 ultrasonic sensor measures grain inventory levels[cite: 163, 164].
* [cite_start]**The Brain (Processing):** An ESP32 microcontroller processes the sensor data locally in real-time[cite: 166].
* [cite_start]**The Muscle (Actuation):** A 5V Relay triggers an active ventilation fan to expel moisture if safe thresholds are breached[cite: 167].
* [cite_start]**The Voice (Offline Communication):** A SIM800L GSM Module sends direct SMS alerts to the farmer's feature phone (e.g., "Alert: High Humidity detected. Fan activated.")[cite: 169].
* [cite_start]**Off-Grid Power:** Operates via a scalable solar architecture, currently utilizing a 10,000mAh lithium-ion system with a TP4056 charge controller[cite: 170, 171].

## 📂 Repository Contents
* **`CONCEPT_NOTE_GHALA_SMART.pdf`**: Full project proposal and architectural breakdown.
* **`ghala_smart_demo.jpeg`**: Visual documentation of the Phase 1 Hardware Prototype.
* **`ghala_smart_components.jpeg`**: Breakdown of the hardware components used.

---
*Developed by [Gideon Mwiti](https://github.com/GideonMwiti) - Project Coordinator & Technical Lead*
