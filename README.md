# ESP32-Smart-Intercom-Door-Openeㄐ

This project implements a smart intercom door opener using an ESP32 and a relay module.  
The ESP32 controls the relay to simulate pressing the original intercom unlock button, allowing the door to be opened remotely through WiFi.

## Overview

Many apartment intercom systems use a simple physical button to trigger the door unlock circuit.  
In this project, a relay is connected in parallel with the original unlock switch.  
When the ESP32 receives a command, it activates the relay for a short time, just like pressing the button manually.

## Features

- ESP32-based WiFi control
- Relay-based button simulation
- Keeps the original intercom button functional
- Uses external 5V power supply for stable operation

## Hardware

- ESP32 development board
- 5V relay module
- Apartment intercom board
- 5V USB power supply


## System Architecture
<img width="503" height="662" alt="image" src="https://github.com/user-attachments/assets/77763957-2055-49e6-9374-36cafb7fb7f9" />
