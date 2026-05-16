# CAN Based Automotive Dashboard System

## Overview
The CAN Based Automotive Dashboard System is an embedded systems project developed to simulate and monitor vehicle parameters using the CAN (Controller Area Network) communication protocol. The system enables reliable communication between multiple electronic control units (ECUs) and displays real-time vehicle information such as speed, temperature, fuel level, and engine status on a dashboard interface.

The project demonstrates the implementation of CAN protocol in automotive applications using microcontrollers and peripheral interfacing techniques. It provides a compact and efficient solution for real-time vehicle monitoring and communication.

---

## Features

- Real-time monitoring of vehicle parameters
- CAN bus communication between nodes
- Dashboard display for live data visualization
- Fast and reliable data transmission
- Sensor data acquisition and processing
- Fault detection and status indication
- Menu-driven user interaction
- Efficient embedded system design

---

## Hardware Components

- PIC Microcontroller / CAN Supported Microcontroller
- MCP2551 CAN Transceiver
- CLCD / LCD Display
- Temperature Sensor
- Fuel Level Sensor
- Push Buttons / Keypad
- UART Interface
- Power Supply Circuit

---

## Software & Technologies

### Programming Language
- Embedded C

### Communication Protocols
- CAN Protocol
- UART

### Concepts Used
- CAN Message Framing
- Embedded Communication Systems
- Peripheral Interfacing
- Real-Time Data Processing
- State Machine Design

---

## Functionalities

### Vehicle Parameter Monitoring
Displays:
- Vehicle Speed
- Engine Temperature
- Fuel Level
- Engine Status

### CAN Communication
- Transmits sensor data between nodes
- Receives and decodes CAN messages
- Ensures reliable real-time communication

### Dashboard Display
- Continuously updates vehicle information
- Provides status monitoring and alerts

### Serial Monitoring
- Sends data through UART for debugging and analysis

---

## Project Workflow

1. Read sensor values from input modules
2. Process data using microcontroller
3. Frame data into CAN messages
4. Transmit messages through CAN bus
5. Receive and decode CAN messages
6. Display vehicle parameters on LCD
7. Send diagnostic data via UART

---

## Key Learnings

- Understanding of CAN protocol architecture
- CAN message transmission and reception
- Real-time embedded system implementation
- Sensor interfacing and data processing
- UART communication and debugging
- Embedded automotive application development

---

## Future Improvements

- Integration with IoT cloud platforms
- GPS-based vehicle tracking
- Touchscreen dashboard interface
- Wireless diagnostics system
- Advanced fault detection and analytics

---

## Author

Developed as part of Embedded Systems and Automotive Communication training.
