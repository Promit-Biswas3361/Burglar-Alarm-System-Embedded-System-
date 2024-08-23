# Burglar Alarm System

## Overview

The Burglar Alarm System is an embedded security solution developed using the LPC1768 microcontroller, HC-SR04 ultrasonic sensor, and IR sensors. It provides intelligent intrusion detection with efficient integration of hardware and software.

## Features

- **LPC1768 Microcontroller**: Central processing unit for the system.
- **HC-SR04 Ultrasonic Sensor**: Measures distance to detect intruders.
- **IR Sensors**: Detects motion and presence.
- **Embedded C Programming**: Manages system control and sensor integration.

## Tools & Technologies

- LPC1768 Microcontroller
- HC-SR04 Ultrasonic Sensor
- IR Sensors
- Embedded C
- Flash Magic Software

## Installation

1. **Hardware Setup**:
   - Connect the LPC1768 microcontroller to the HC-SR04 ultrasonic sensor and IR sensors.
   - Ensure all connections are secure as per the project’s circuit diagram.

2. **Software Setup**:
   - Compile the Embedded C code using an appropriate development environment.
   - Use Flash Magic software to transfer the compiled code to the LPC1768 microcontroller.

## Usage

1. Power on the system.
2. The system will continuously monitor for obstructions using the sensors.
3. In case of detected obstructions, the system activates the buzzer and displays the distance of the objects on the LED along with a message "INTRUDER ALERT!!".

## Contribution

This project was developed collaboratively with peers. Contributions and feedback are welcome.
