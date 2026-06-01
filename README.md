# Smart Parking System with Fire Detection

## Overview

The Smart Parking System with Fire Detection is an IoT-based project that combines parking management and safety monitoring into a single intelligent system. The project uses ESP32 and multiple sensors to monitor parking slot occupancy, detect fire hazards, identify gas leaks, and measure environmental temperature in real time. Data is displayed locally on an LCD screen and remotely through the Blynk IoT platform, enabling users to monitor parking and safety conditions from anywhere.

## Objectives

* Monitor parking slot availability in real time.
* Detect fire, smoke, gas leaks, and abnormal temperature rise.
* Provide instant alerts through buzzer, LED, LCD, and Blynk notifications.
* Enable remote monitoring through mobile and web dashboards.
* Improve safety and parking management in smart city environments.

## Components Used

### Hardware

* ESP32 Microcontroller
* Ultrasonic Sensors (HC-SR04)
* DHT11/DHT22 Temperature Sensor
* MQ2 Gas Sensor
* 16x2 LCD with I2C Module
* Buzzer
* Breadboard and Jumper Wires

### Software & Platforms

* Arduino IDE
* Wokwi Simulator
* Blynk IoT Platform

## Working Principle

### Parking Monitoring

Ultrasonic sensors are installed in parking slots to measure distance. When a vehicle occupies a slot, the measured distance falls below a predefined threshold and the slot is marked as occupied. Otherwise, it is displayed as available.

### Temperature Monitoring

The DHT sensor continuously measures ambient temperature. If the temperature exceeds a safe limit, an overheat warning is generated.

### Fire and Gas Detection

The flame sensor detects fire presence, while the MQ2 sensor monitors smoke and gas concentration. When abnormal levels are detected, safety alerts are triggered immediately.

### Alert System

* LCD displays parking status and warning messages.
* Buzzer and LEDs provide local alerts.
* ESP32 sends data to the Blynk cloud platform.
* Users can monitor the system through mobile and web dashboards.
* Push notifications are sent during emergency situations.

## Features

* Real-time parking slot monitoring
* Fire detection and safety alerts
* Gas leak and smoke detection
* Temperature monitoring
* LCD-based status display
* Mobile and web dashboard monitoring
* Push notifications via Blynk
* Scalable IoT architecture

## Applications

* Smart Parking Facilities
* Shopping Malls
* Office Complexes
* Educational Institutions
* Smart Cities
* Industrial Parking Areas
* Public Infrastructure Monitoring

## Future Enhancements

* Automatic boom barrier control
* Vehicle number plate recognition
* AI-based parking analytics
* Cloud database integration
* Solar-powered operation
* Emergency response automation
* Multi-floor parking support

## Tools Used

* Arduino IDE for programming
* Wokwi for simulation and testing
* Blynk IoT for cloud monitoring and notifications

## Conclusion

This project demonstrates how IoT technology can be used to improve both parking management and public safety. By integrating parking occupancy detection with fire, gas, and temperature monitoring, the system provides a comprehensive and intelligent solution suitable for modern smart city applications.
