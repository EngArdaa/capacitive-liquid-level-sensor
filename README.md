
# Capacitive Liquid Level Sensor

## Overview

This project is a custom capacitive liquid level sensor board designed to measure liquid level and provide an analog voltage output according to the measured level.

The board is based on an STM32G030F6P6 microcontroller and uses the FDC1004 capacitive sensing IC for liquid level measurement. The system is designed with a 28V input supply, onboard power regulation stages and an analog output interface.

The main goal of this project was to improve my hardware design skills in sensor interface circuits, power regulation, microcontroller-based board design and PCB layout.

## Key Features

* STM32G030F6P6 microcontroller-based design
* FDC1004 capacitive sensing IC
* 28V input voltage
* Onboard power regulation structure
* Analog output interface
* Liquid level measurement from 0 cm to 30 cm
* Output voltage range from approximately 0.25V to 4.75V
* Sensor-oriented PCB design
* Hardware design focused on measurement and signal integrity

## System Specifications

| Parameter            | Value                                |
| -------------------- | ------------------------------------ |
| Input Voltage        | 28V                                  |
| Microcontroller      | STM32G030F6P6                        |
| Capacitive Sensor IC | FDC1004                              |
| Measurement Range    | 0 cm - 30 cm                         |
| Output Voltage Range | 0.25V - 4.75V                        |
| Design Type          | Capacitive liquid level sensor board |

## Tools Used

* Altium Designer
* Datasheets and reference designs
* PCB design rule checks
* Hardware design review process
* General test and measurement equipment

## Hardware Design

The hardware design includes the microcontroller section, capacitive sensing interface, power regulation stages and analog output circuitry. During the design process, I focused on component selection, schematic design, PCB layout planning, power routing and signal routing for a sensor-based embedded system.

## Documentation

A Turkish design report is available in the [`docs/capacitive-liquid-level-sensor-design-report-tr.pdf`](docs/capacitive-liquid-level-sensor-design-report-tr.pdf) file.

## What I Learned

Through this project, I gained practical experience in capacitive sensing circuits, microcontroller-based hardware design, power regulation, analog output interfacing and PCB layout review.

This project helped me better understand how sensor measurement circuits, embedded control and analog output requirements are combined in a complete hardware design.

## Future Improvements

* Adding detailed test and validation results
* Improving documentation with measurement data
* Reviewing the PCB layout for manufacturability
* Creating a revised version based on design review feedback
