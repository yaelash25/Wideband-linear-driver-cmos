# Wideband Linear Driver

Analog IC design project – wideband CMOS receiver amplifier designed for high-frequency serial communication.

## Project goal

Design a wideband linear driver suitable for 2 Gb/s serial communication using a fixed CMOS topology.  
The design required transistor sizing and bias optimization to achieve high bandwidth while maintaining low power consumption.

## Specifications

- DC Gain: 25 ± 0.1 dB  
- 3-dB Bandwidth: 1 ± 0.02 GHz  
- Maximum Power Consumption: 200 µW  
- Supply voltage: 1 V  
- Load capacitance: 10 fF  
- Technology: BiCMOS8HP (Cadence)  

## Design requirements

- All transistors must operate in saturation
- Overdrive voltage > 50 mV
- No additional components allowed
- Only transistor sizing and resistor values could be changed

## Tools

Cadence Virtuoso  
AnalogLib  
BiCMOS8HP 

## Results

The designed amplifier meets the required gain and bandwidth while maintaining linear operation and low power consumption.  
Frequency response, transient simulations, and bias point analysis were used to verify performance.

## Report

[Project report](./wideband_linear_driver_report.pdf)
