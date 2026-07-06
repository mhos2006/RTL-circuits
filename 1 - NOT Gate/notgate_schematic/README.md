# NOT Gate

## Overview

Building an invertor (NOT) circuit using resistors and transistors.

## Hardware Specifications

- **Collector Resistor:** 1kΩ
- **Base Resistor:** 10kΩ
- **Brain:** 2N3904 BJT Transistor
- **Circuit tester:** LED

## Prerequisites
To achieve my 5V power rail, I used a battery pack regulated to output 5V. Here is a link to the repository:
[5V Linear Breadboard Power Supply](https://github.com/mhos2006/starter-dc-makeshift-power-supply) 


## Schematic

<img width="723" height="230" alt="image" src="https://github.com/user-attachments/assets/978967c0-3b40-4e2a-8b53-f6940e8a2be6" />

## Testing

In this clip, I initially have the input wire connected to GND. The LED will remain lit up until the wire is connected to the 5V rail, where the signal is inverted and the transistor is on.

https://github.com/user-attachments/assets/247801db-2280-493d-9bdd-d6d0273200bf


## Schematic and PCB Documentation

I created the schematic using KiCad software. While my schematic has been verified, I have not yet moved the components over to PCB software as I must still add component footnotes. PCB layout and component placement is in progress.
