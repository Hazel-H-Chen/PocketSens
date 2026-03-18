# PocketSens Portable Sensor Suite

PocketSens is a portable environmental sensor platform designed to measure environmental and physical data beyond the capabilities of a typical smartphone. The system integrates multiple sensors on a custom four layer PCB and provides real time measurements through a small OLED display and rotary encoder interface.

## Overview

PocketSens is built around an ARM Cortex M0+ SAMD21 microcontroller and communicates with several sensors over an I²C bus. The device collects environmental measurements and displays them directly on the device, allowing users to monitor conditions in real time.

The system is designed as a compact handheld tool capable of measuring atmospheric and environmental parameters in a single portable device. 

## Sensors

The device integrates several sensors including:

* BME680 environmental sensor
  gas, humidity, pressure, temperature
* BMP390 barometric pressure sensor
* MLX90614 infrared temperature sensor
* AS3935 lightning detection sensor

Together these sensors allow the device to measure a wide range of environmental conditions in real time. 

## Hardware

* Custom four layer PCB designed in KiCad
* ARM Cortex M0+ SAMD21 microcontroller
* OLED display for live data output
* Rotary encoder for user interface
* I²C sensor bus architecture

## Features

* Multi sensor environmental monitoring
* Real time data display on OLED screen
* Lightning detection capability
* Infrared temperature sensing
* Compact portable design

## Repository Contents

pcb/
KiCad schematic and PCB layout files

firmware/
Microcontroller firmware and drivers

images/
Board photos and layout screenshots

docs/
Additional design notes and documentation

## Project Status

REV 1.0 prototype PCB completed.

## Author

Hazel Chen
Mechanical and Electrical Engineering Student
University of Virginia
