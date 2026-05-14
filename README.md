# UART-PROTOCOL
This project implements a UART (Universal Asynchronous Receiver Transmitter) protocol using Verilog HDL.
The design includes separate modules for UART transmission, reception, baud rate generation, and a top module integrating all components.

The project is developed for RTL design learning and FPGA digital design practice.
# Features:
1) UART Transmitter
2) UART Receiver
3) Baud Rate Generator
4) Modular RTL Design
5) Synchronous Design Methodology
6) Easy Integration with FPGA Projects

  # Modules Included :
1. Top Module:-

Integrates transmitter, receiver, and baud rate generator.

2. Baud Rate Generator:-

Generates UART baud clock from system clock.

3. UART Transmitter:-

Converts parallel data into serial UART format.

4. UART Receiver:-

Receives serial UART data and converts it into parallel data.

# UART Frame Format :
                   -->1 Start Bit
                   -->8 Data Bits
                   -->1 Stop Bit
                   -->No Parity

# Tools Used:
                   -->Verilog HDL
                   -->Icarus Verilog (iverilog)
                   -->GTKWave
                   -->VS Code

# Applications:
                  -->Serial Communication
                  -->FPGA Communication Interfaces
                  -->Embedded Systems
                  -->ASIC RTL Design Practice
                 
# Future Improvements:
                  -->Add Parity Bit Support
                  -->Configurable Baud Rate
                  -->FIFO Integration
                  -->UART Error Detection
                  
# Author
Chinthalapalli Varun Naga Sai Narayana  
B.Tech Second Year Student  
Electronics and Communication Engineering  
Indian Institute of Technology Bhubaneswar
