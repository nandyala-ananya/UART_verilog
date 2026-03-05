# UART Communication Protocol in Verilog

This project implements the UART (Universal Asynchronous Receiver Transmitter) communication protocol using Verilog. The design includes a baud rate generator, UART transmitter, UART receiver, and parity generation/checking. A testbench is used to simulate and verify the communication.

## Features
- Asynchronous serial communication
- Baud rate generator
- UART transmitter (TX)
- UART receiver (RX)
- Even parity generation and checking
- Verilog testbench for simulation

## Modules
- **baud_gen** – Generates the baud rate timing signal
- **uart_tx** – Converts parallel data into serial data
- **uart_rx** – Receives serial data and converts it back to parallel
- **uart_top** – Connects transmitter, receiver, and baud generator

## Simulation
The design was simulated using **EDA Playground**.  
Waveforms were observed using **EPWave**.

## Files
- `uart_design.v` – Verilog design modules
- `uart_tb.v` – Testbench for simulation
- `uart_epwave.png` – Simulation waveform
- `uart_output.png` – Simulation result

