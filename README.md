# Implementation of DRAM using Cadence

## Problem Statement: Implementing DRAM
The objective of this project is to design and implement a Dynamic Random-Access Memory (DRAM) module using Cadence tools.

## Theory:
Dynamic Random-Access Memory (DRAM) is a type of memory that is used in computing devices to store data. Unlike static RAM (SRAM), DRAM requires periodic refreshing to maintain the stored data. DRAM cells consist of a capacitor and a transistor, where the capacitor stores the data in the form of an electrical charge, and the transistor acts as a switch to read or write the data.

1. **DRAM Cell Operation**:
   - **Write Operation**: To write a bit to a DRAM cell, the word line is activated, which allows the charge to be stored in the capacitor through the bit line.
   - **Read Operation**: To read a bit from a DRAM cell, the word line is activated, and the charge stored in the capacitor is transferred to the bit line, which is then sensed and amplified.

2. **Refresh Mechanism**:
   DRAM cells lose their charge over time due to leakage currents. To prevent data loss, DRAM cells must be periodically refreshed. This involves reading the charge stored in each cell and then writing it back.

3. **DRAM Architecture**:
   - **Array of Cells**: DRAM is organized in a matrix of rows and columns where each cell can be accessed by its unique row and column address.
   - **Row Address Strobe (RAS)** and **Column Address Strobe (CAS)**: These signals are used to latch the row and column addresses, respectively.

## Design and Implementation:
The DRAM module is implemented using Cadence tools with the following steps:

1. **Specification**: Define the requirements and specifications of the DRAM module including the size, refresh rate, and access times.

2. **Schematic Design**: Create the schematic of the DRAM cell, including the capacitor and transistor, as well as the peripheral circuits like row decoder, column decoder, and sense amplifiers.

3. **Layout Design**: Design the physical layout of the DRAM cell and array. Ensure the layout is optimized for area and performance while meeting the design rules.

4. **Simulation and Verification**: Perform simulations to verify the functionality of the DRAM cell and array. Use Cadence simulation tools to check for correct read/write operations and refresh mechanisms.

5. **Fabrication**: Once the design is verified, it can be sent for fabrication. The fabricated chip will then be tested for real-world performance.

## Results:
The results section includes simulation outputs and analysis:
- **Simulation Outputs**: Provide screenshots of the simulation waveforms showing successful read, write, and refresh operations.
- **Layout**: Provide the layout views of the DRAM cell and array.

## References
- [DRAM Basics](https://www.geeksforgeeks.org/introduction-of-dram-dynamic-random-access-memory/)
- [Cadence Design Systems](https://www.cadence.com/)
