# Smart Alert and Indication System using STM32

## Overview

This project demonstrates a Smart Alert and Indication System developed using the STM32F401RE microcontroller. The system monitors three push-button inputs and performs different output actions using an LED, buzzer, relay, and a common cathode 7-segment display.

The project was developed using STM32CubeMX for peripheral configuration, STM32CubeIDE for firmware development, Embedded C with STM32 HAL libraries, and Proteus for simulation.

---

## Features

- GPIO Input and Output Control
- Push Button Interface
- LED Control
- Buzzer Control
- Relay Interface
- Common Cathode 7-Segment Display
- Software Debouncing
- Polling-Based GPIO Programming

---

## System Operation

| Switch | Output | Display |
|---------|--------|----------|
| Switch 1 | LED ON | 1 |
| Switch 2 | Buzzer ON | 2 |
| Switch 3 | Relay ON | 3 |
| No Switch | All Outputs OFF | Blank |

---

## Hardware Components

- STM32 Nucleo F401RE
- Push Buttons (3)
- LED
- Buzzer
- Relay
- BC547 Transistor
- 1N4007 Flyback Diode
- Common Cathode 7-Segment Display
- 220Ω, 1kΩ and 10kΩ Resistors
- Breadboard and Jumper Wires

---

## Software Used

- STM32CubeMX
- STM32CubeIDE
- Embedded C
- STM32 HAL Drivers
- Proteus Design Suite

---

## GPIO Configuration

### Inputs

- PA0 → Switch 1
- PA1 → Switch 2
- PA4 → Switch 3

### Outputs

- PB0 → LED
- PB1 → Buzzer
- PB2 → Relay

### 7-Segment Display

- PC0 → Segment A
- PC1 → Segment B
- PC2 → Segment C
- PC3 → Segment D
- PC4 → Segment E
- PC5 → Segment F
- PC6 → Segment G

---

## Learning Outcomes

- STM32 GPIO Configuration
- STM32 HAL Programming
- Digital Input Reading
- Digital Output Control
- 7-Segment Display Interfacing
- Relay Driving Circuit
- Embedded C Programming
- Proteus Simulation
- Hardware and Software Debugging

---

## Challenges Faced

- Configuring GPIO correctly in STM32CubeMX
- Understanding Common Cathode 7-Segment logic
- Debugging incorrect digit display due to segment wiring
- Interfacing a relay safely using a transistor and flyback diode
- Learning systematic debugging instead of assuming the software was incorrect

---

## Future Improvements

- Interrupt-based button handling
- LCD or OLED display integration
- UART debugging messages
- RTOS implementation
- IoT-based monitoring using ESP32
- Mobile application integration

---

## Author

Om Gajanan Sapdhare

Electronics and Telecommunication Engineering Student

Interested in Embedded Systems, Automotive Electronics, IoT, and Firmware Development.
---

## Project Structure
