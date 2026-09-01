# Day 2 — Timing Libraries and Sequential Logic

## Topics Covered

- Liberty timing libraries
- Standard-cell characterization
- PVT concepts
- Hierarchical and flat synthesis
- Flip-flop coding styles
- Asynchronous reset and set
- Synchronous reset
- Constant optimization

## Lab Work

The labs focused on understanding how standard-cell timing information is represented in a Liberty file and how that library is used during synthesis.

Different flip-flop RTL implementations were simulated and synthesized, including asynchronous reset, asynchronous set and synchronous reset configurations.

Constant-driven sequential designs were also analyzed to observe synthesis optimization.

## Tools Used

- Yosys
- Icarus Verilog
- GTKWave
- SKY130 Liberty library

## Key Learning

The timing library provides the cell, timing and electrical information required during technology mapping. Different RTL coding styles can lead to different hardware implementations after synthesis.
