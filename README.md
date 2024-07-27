This project demonstrates the use of a PIC microcontroller to implement UART communication and GPIO control. The system reads input states from switches and sends corresponding characters via UART. It also receives characters via UART to control LEDs.

## Features

- **GPIO Configuration**: Sets up PORTB as output and PORTC as input.
- **UART Communication**: Transmits and receives data to control output states based on input states.
- **Real-Time Operation**: Efficiently handles data processing within the main control loop.

## Hardware Requirements

- PIC Microcontroller
- UART Interface
- Switches/Buttons connected to PORTC.F0, PORTC.F1, PORTC.F2, and PORTC.F3
- LEDs or similar devices connected to PORTB.F0, PORTB.F1, PORTB.F2, and PORTB.F3

## Software Requirements

- MikroC Compiler

## Project Setup

1. **Hardware Configuration**:
    - Connect switches/buttons to PORTC.F0, PORTC.F1, PORTC.F2, and PORTC.F3.
    - Connect LEDs to PORTB.F0, PORTB.F1, PORTB.F2, and PORTB.F3.
    - Ensure proper power supply to the microcontroller and peripherals.

2. **Software Configuration**:
    - Open the project in MikroC.
    - Compile the code and upload it to the PIC microcontroller.
