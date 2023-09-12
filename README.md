# 4-Bit Nano Processor Project - CS1050

## Overview

This contains the design and implementation of a 4-bit nano processor capable of executing a simple set of instructions.

## Components

Components that are designed and implemented in this project:

1. **Instruction Decoder**: Responsible for decoding instructions fetched from memory and controlling the processor's operation.

2. **Clock Controller**: Manages the timing and synchronization of the processor's operations.

3. **2-Way 3-Bit Multiplexer**: Used for data and control signal routing within the processor.

4. **3-Bit Adder**: Performs 3-bit addition operations.

5. **Register Bank**: Provides a set of registers for data storage and manipulation.

6. **2-Way 4-Bit Multiplexer**: Used for data selection and routing.

7. **Program ROM**: Stores the program instructions in machine code, including the program to calculate the total of integers between 1 and 3.

8. **Program Counter**: Keeps track of the address of the current instruction in memory.

9. **4-Bit Add/Sub Unit**: Performs 4-bit addition and subtraction operations.

10. **8-Way 4-Bit Multiplexer**: Used for selecting data sources in the processor.

## Functionality

The processor's functionality includes executing a simple program written in machine code. The program calculates the total of integers between 1 and 3. It involves fetching instructions from the Program ROM, decoding them using the Instruction Decoder, and performing arithmetic operations using the components such as the 3-Bit Adder and 4-Bit Add/Sub Unit.

## Development and Testing

We developed and verified the functionality of each component through simulations using Xilinx Vivado. The final nano processor was tested on the Basys3 board by exporting and uploading a bitstream file generated from the Vivado project.

## Getting Started

To replicate this project or work with the code, follow these steps:

1. Clone this repository to your local machine.
2. Open the Vivado project and follow the instructions for synthesis and bitstream generation.
3. For simulation and testing, use the provided testbenches and simulation scripts in the respective component directories.
4. For hardware testing, refer to the hardware setup documentation in the project report.

## License

This project is open-source and licensed under the [MIT License](LICENSE).

## Acknowledgments

I would like to acknowledge the contributions of each team member who worked on the individual components of this project.
