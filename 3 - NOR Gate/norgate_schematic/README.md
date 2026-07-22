# NOR Gate

## Overview

Building a NOR gate using resistors and transistors

## Hardware Specifications

- **Collector Resistor:** 1kΩ resistor
- **Base Resistors:** 2× 10kΩ resistors
- **Switch:** 2× 2N3904 BJTs
- **Circuit tester:** LED

## Prerequisites
To achieve my 5V power rail, I used a battery pack regulated to output 5V. Here is a link to the repository:
[5V Linear Breadboard Power Supply](https://github.com/mhos2006/starter-dc-makeshift-power-supply) 

## Schematic


<img width="1105" height="211" alt="image" src="https://github.com/user-attachments/assets/15187e1a-de75-44cf-9caf-e66da4571b59" />


## Testing

These pictures show the output (LED) with its corresponding inputs (green jumper wires to either +5V rail or GND)

**1. Q1 - Logic 0, Q2 - Logic 0:**




**2. Q1 - Logic 0, Q2 - Logic 1:**




**3. Q1 - Logic 1, Q2 - Logic 0:**




**4. Q1 - Logic 1, Q2 - Logic 1:**




## Schematic and PCB Documentation

I created the schematic using KiCad software. While my schematic has been verified, I have not yet moved the components over to PCB software as I must still add component footnotes. PCB layout and component placement is in progress.

## Documentation

For a full breakdown of the empirical voltage measurements and semiconductor saturation analysis, please see the attached technical report .docx.
