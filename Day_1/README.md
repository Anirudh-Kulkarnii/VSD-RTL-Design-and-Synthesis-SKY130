# Day 1 — RTL Design, Simulation and Synthesis

## Topics Covered

- Verilog RTL design
- Testbench development
- Functional simulation
- Icarus Verilog
- GTKWave waveform analysis
- RTL synthesis using Yosys
- SKY130 standard-cell technology mapping

## Lab Work

The initial labs focused on understanding the RTL design and verification flow using simple digital designs.

The designs were compiled with Icarus Verilog and verified using dedicated testbenches. VCD files were generated and examined using GTKWave.

The designs were also synthesized using Yosys with the SKY130 standard-cell library to understand the transition from RTL to gate-level logic.

## Designs

The repository contains RTL and verification files for:

- Multiplexer
- Shift register
- Counter

## Design Flow

```text
Verilog RTL
    ↓
Testbench
    ↓
Icarus Verilog
    ↓
VCD waveform
    ↓
GTKWave
    ↓
Yosys synthesis
    ↓
SKY130 mapped netlist

