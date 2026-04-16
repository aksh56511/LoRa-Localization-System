# LoRa Localization System

This project implements a LoRa-based localization system using RSSI and directional antenna scanning.

## 📡 Overview
The system detects the direction of a signal source using RSSI values from a LoRa module. A servo motor rotates the antenna, and multiple readings are used for triangulation.

## ⚙️ Components
- STM32 Microcontroller
- LoRa SX1276 Module
- Servo Motor
- Capacitors & Resistors

## 🧠 Working
- LoRa receives signal strength (RSSI)
- STM32 processes data
- Servo rotates antenna (PWM control)
- MATLAB estimates location using triangulation

## 🖥️ Tools Used
- KiCad (PCB Design)
- MATLAB (Simulation)

## 📊 Output
- RSSI vs Angle graph
- Estimated beacon position
- PCB layout

## 📷 Project Images
![PCB](Images/pcb.png)
![Schematic](Images/schematic.png)

## 👨‍💻 Author
Aksh
