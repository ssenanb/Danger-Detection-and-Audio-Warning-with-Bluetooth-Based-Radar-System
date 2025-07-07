# Danger-Detection-and-Audio-Warning-with-Bluetooth-Based-Radar-System

# Project Description

This project involves environmental detection through angular scanning using a HC-SR04 on a servo motor.
The system is based on a simple radar simulation. The easured distance values are:

* Transmitted from the ESP32 to the ESP32 via UART.

* Then forwarded from the ESP32 to a smartphone via Bluetooth.

* Displayed in real time on a Bluetooth Serial Terminal running on Android.

If the measured distance falls a below certain threshold, the buzzer on the STM32 is activated. The system also supports remote control. When an `OFF` command is sent from the Bluetooth Terminal, the ESP32 forwards this command to the STM32 via UART and the buzzer is deactivated. 

# Components

STM32F0DISC

ESP32 WROOM 32D

HC-SR04 Ultrasonic Distance Sensor

SG-90 Mini Servo Motor

Buzzer

Jumper Cables
