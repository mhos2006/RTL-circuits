# NAND Gate

## Overview

Building a NAND gate using resistors and transistors

## Hardware Specifications

- **Collector Resistor:** 1kΩ resistor
- **Base Resistors:** 2× 10kΩ resistors
- **Switch:** 2× 2N3904 BJTs
- **Circuit tester:** LED

## Prerequisites
To achieve my 5V power rail, I used a battery pack regulated to output 5V. Here is a link to the repository:
[5V Linear Breadboard Power Supply](https://github.com/mhos2006/starter-dc-makeshift-power-supply) 

## Schematic

<img width="1022" height="212" alt="image" src="https://github.com/user-attachments/assets/0e238d38-a9b6-4b65-8d49-e3c916de437e" />

## Testing

These pictures show the output (LED) with its corresponding inputs (green jumper wires to either +5V rail or GND)

**1. Q1 - Logic 0, Q2 - Logic 0:**

<img width="510" height="235.5" alt="image" src="https://github.com/user-attachments/assets/5223f9af-5862-4a52-85d8-d7c7b4b7d7bc" />


**2. Q1 - Logic 0, Q2 - Logic 1:**

<img width="510" height="235.5" alt="image" src="https://github.com/user-attachments/assets/0af01813-871a-4b4d-82de-9b2a9b501391" />


**3. Q1 - Logic 1, Q2 - Logic 0:**

<img width="510" height="235.5" alt="image" src="https://github.com/user-attachments/assets/210fa23f-ec5e-40f3-bc0b-754f693a6219" />


**4. Q1 - Logic 1, Q2 - Logic 1:**

<img width="510" height="235.5" alt="image" src="https://github.com/user-attachments/assets/e8a54a9c-92c5-42e1-81d8-98875c9e3bcd" />


## Schematic and PCB Documentation

I created the schematic using KiCad software. While my schematic has been verified, I have not yet moved the components over to PCB software as I must still add component footnotes. PCB layout and component placement is in progress.

## Documentation

For a full breakdown of the empirical voltage measurements and semiconductor saturation analysis, please see the attached technical report .docx.
