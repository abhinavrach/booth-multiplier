# booth-multiplier
FPGA-based implementation of a 4-bit multiplier using Booth encoding and Wallace tree reduction to achieve faster computation with minimized hardware complexity.

# 4-bit Booth Encoded Wallace Tree Multiplier (FPGA)

## Overview
This project implements a 4-bit binary multiplier using Booth encoding and Wallace tree reduction techniques. The design is implemented on an FPGA to achieve high-speed and efficient multiplication by reducing the number of partial products and minimizing computation delay.

## Objectives
- To design a high-speed 4-bit multiplier
- To reduce partial products using Booth encoding
- To optimize addition stages using Wallace tree structure
- To implement and verify the design on FPGA hardware

## Key Concepts

### Booth Encoding
Booth encoding reduces the number of partial products by encoding the multiplier bits, leading to fewer arithmetic operations.

### Wallace Tree
Wallace tree structure reduces multiple partial products in parallel using carry-save adders, significantly improving speed.

## Methodology
1. Generate partial products using Booth encoding
2. Reduce partial products using Wallace tree structure
3. Perform final addition using a fast adder
4. Implement the design in Verilog/VHDL
5. Synthesize and deploy on FPGA
6. Verify output using simulation and hardware testing

## Tools and Technologies
- Hardware Description Language: Verilog / VHDL
- FPGA Board: (Specify your board, e.g., Xilinx Spartan-6 / Artix-7)
- Software Tools: Xilinx Vivado / Intel Quartus
- Simulation Tool: ModelSim / Vivado Simulator

## Results
- Reduced number of partial products compared to conventional multiplication
- Faster computation due to parallel reduction
- Successful implementation and verification on FPGA

## Project Structure

```text
├── src/          # Verilog/VHDL source files
├── sim/          # Testbenches and simulation files
├── constraints/  # FPGA constraint files
├── docs/         # Diagrams and images
└── README.md
```

## How to Run
1. Open the project in your FPGA design tool (Vivado/Quartus)
2. Add source and constraint files
3. Run synthesis and implementation
4. Generate bitstream
5. Program the FPGA
6. Verify outputs using test inputs

## Applications
- Digital signal processing (DSP)
- Arithmetic logic units (ALUs)
- Embedded systems
- High-speed computing systems

## Future Improvements
- Extend to 8-bit or 16-bit multiplier
- Optimize power consumption
- Implement pipelining for higher throughput

## Author
Abhinav Racha Battuni
RV College of Engineering (RVCE)

---

## Links

- Portfolio: https://abhinavrach.github.io/
- Project Repo: https://github.com/abhinavrach/smart-irrigation-system
