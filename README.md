# Web-Based Oil Lamp Ignition System 🔥

## Overview
This project is a web-controlled real oil lamp ignition system using ESP32, Arduino Mega, and a 16-channel relay module.

The system allows users to ignite oil lamps remotely through a web interface.

## How it works

1. User sends command from website
2. Website updates MySQL database
3. ESP32 reads database via LAN connection
4. ESP32 sends signal to Arduino Mega via I2C
5. Arduino Mega activates relay channel
6. Relay completes ignition circuit
7. Oil lamp lights with real fire

## Hardware Used

- ESP32
- Arduino Mega
- 16 Channel Relay Module
- 12V Power Supply
- Ignition System
- LAN Connection

## Features

- Remote ignition via website
- LAN based communication
- Database controlled triggering
- Safe relay isolation
- Scalable up to 16 lamps

## Folder Structure

- esp32 → ESP32 source code
- arduino_mega → Arduino code
- website → Web control system
- database → SQL database
- docs → diagrams

## Author

Heshan Kavinda  
YouTube: Techie_Heshan
