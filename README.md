# Resistor-Transistor Logic (RTL) Combinational Circuits

This repository documents the design, assembly, and testing of fundamental logic gates using discrete Bipolar Junction Transistors (BJTs) and passive components.

### Hardware and Components
*   **Transistors:** 2N3904 NPN Bipolar Junction Transistors
*   **Passives:** Assorted through-hole resistors for base biasing and load management
*   **Platform:** 830-point solderless breadboard
*   **Power:** 5V regulated DC supply

### Completed Logic Gates

#### 1. NOT Gate (Inverter)
*   **Status:** Completed
*   **Description:** Built using a single NPN transistor. The circuit successfully inverts the input signal, driving the output low when the input is driven high, and allowing the output to float high when the input is low.

#### 2. NAND Gate
*   **Status:** Completed
*   **Description:** Constructed with two BJTs in a series configuration. The output is pulled to ground only when both inputs are actively driven high.

#### 3. NOR Gate
*   **Status:** Completed
*   **Description:** Implemented using two BJTs in a parallel configuration. If either input receives a high signal, the output is pulled low. 
*   **Note:** Physical assembly and testing were successfully verified on the breadboard. While photographic documentation of the physical build is not included, the provided KiCad schematics serve as the primary technical reference for the design and routing.

### Planned Circuits
*   **AND Gate**
*   **OR Gate**
*   **XOR Gate**

### Documentation
In each gate file, I have included the schematic in KiCad and a PDF of it too. The PCB files are also they but are incomplete.
