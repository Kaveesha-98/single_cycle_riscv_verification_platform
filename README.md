# Single-Cycle RISC-V CPU Framework

## Overview
This project provides a framework for implementing a single-cycle RISC-V processor. It is designed as an educational tool, allowing users to practice writing a CPU by completing the missing components. The framework includes a basic structure with memory and a simple testbench, but requires users to implement core functionalities such as the ALU, register file, and control logic.

## Features
- Pre-configured environment for implementing a single-cycle RISC-V CPU.
- Provided components:
  - Memory module (Instruction & Data Memory)
  - Testbench for simulation
- Missing components that users need to implement:
  - core (The single cycle cpu to implement)
- Simple test cases to verify implementation.

## Getting Started

### Prerequisites
Before using this framework, ensure you have the following tools installed:
- **Simulation & Synthesis Tools**: Mention the python versions and libraries needed

### Setup Instructions
1. Clone the repository:
   ```sh
   git clone https://github.com/Kaveesha-98/single_cycle_riscv_verification_platform.git
   cd single_cycle_riscv_verification_platform
   ```
2. Open the project in your preferred development environment and open the file rtl/core.v.
3. Complete module core.
4. Run the simulation using the testbench.
   ```sh
   python command to run tests
   ```

## Project Structure
```
├── rtl
│   ├── core.v          # single cycle core to be implemented
│   ├── sim_top.sv      # simulation test bench
│   ├── control.sv      # Control logic (To be implemented)
│   ├── memory.sv       # Memory module (Provided)
│   ├── decoder.sv      # Instruction decoder (Provided)
│   ├── cpu.sv          # CPU top-level module (Partially provided)
│
├── sim/cocotb_env (Need to be completed)
│   ├── sim_top.py       # Testbench
│
└── README.md           # This file
```

## Contributing
Contributions are welcome! If you have improvements or additional test cases, feel free to submit a pull request.
