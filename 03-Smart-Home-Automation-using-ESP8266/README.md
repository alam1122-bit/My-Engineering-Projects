# Smart Home Automation using ESP8266

## Overview
This project focuses on building a customizable, IoT-based **Smart Home Automation System** designed to control household appliances both locally and remotely. The system allows users to switch 4 AC appliances (bulbs) on or off using physical wall switches as well as a mobile app connected via Wi-Fi.

---

## Key Features
* **Dual Control Mechanism:** Operate appliances seamlessly using traditional physical switches or a mobile application.
* **4-Channel Appliance Control:** Manage up to 4 independent electrical loads/bulbs safely via optocoupler-isolated relay channels.
* **Local Wi-Fi Network Integration:** Direct control over local Wi-Fi with static IP assignment for low latency and reliable operation.
* **Status Synchronization:** Real-time state management between physical switch toggles and mobile app inputs.

---

## Hardware Components
* **Microcontroller:** ESP32 / ESP8266 / Arduino
* **Relay Module:** 4-Channel Relay Module (with optocoupler isolation)
* **Switches:** 4 Manual Push/Toggle Switches
* **Appliances:** 4 AC Light Bulbs & Lamp Holders
* **Networking:** TP-Link / Home Wi-Fi Router
* **Power Supply:** 5V/12V DC Adapter for Microcontroller and Relay board

---

## Software & Tools
* **Development Environment:** Arduino IDE / VS Code (PlatformIO)
* **Programming Language:** C / C++ (Embedded C)
* **Protocols:** HTTP REST API / WebSockets / MQTT over Wi-Fi (802.11 b/g/n)
* **Circuit Design & Simulation:** Proteus Design Suite / Fritzing

---
