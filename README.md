# Wideband Linear CMOS Driver

Analog IC design project – wideband receiver amplifier designed for high-frequency serial communication.

## Overview

This project implements a wideband linear CMOS driver designed for receiver front-end applications supporting multi-Gb/s data rates.  
The circuit was implemented in Cadence Virtuoso using the BiCMOS8HP technology and optimized to meet strict gain, bandwidth, and power consumption requirements.

## Specifications

- DC Gain: 25 dB
- 3-dB Bandwidth: 1 GHz
- Maximum Power Consumption: 200 µW
- Supply Voltage: 1 V
- Load Capacitance: 10 fF
- Technology: BiCMOS8HP

## Design Requirements

- Fixed topology (no additional components allowed)
- All transistors in saturation region
- Overdrive voltage > 50 mV
- Gain, bandwidth, and power must meet spec simultaneously
- Verified using AC, transient, and bias simulations

## Tools

Cadence Virtuoso  
Spectre Simulator  
AnalogLib  
BiCMOS8HP PDK  

## Results

The designed driver achieves the required gain and wideband response while maintaining low power consumption.  
Simulation results include AC response, transient linearity verification, and bias point analysis.

## Report

[Project report](./DesignEx2_Wide_and_Linear_Driver.pdf)
