# Day 4 — Gate-Level Simulation and Synthesis Mismatch

## Topics Covered

- Gate-level simulation
- RTL versus synthesized netlist
- Blocking and non-blocking assignments
- Incomplete sensitivity lists
- Latch inference
- Synthesis-simulation mismatch

## Lab Work

The labs examined RTL coding styles that can produce unexpected synthesized hardware or simulation-synthesis mismatches.

RTL designs were synthesized into gate-level netlists and the behavior of the synthesized implementation was examined.

Examples involving blocking assignments, incomplete sensitivity and latch-related coding issues were used to understand the difference between RTL simulation and synthesized hardware behavior.

## Verification Flow

```text
RTL
 ↓
RTL Simulation
 ↓
Synthesis
 ↓
Gate-Level Netlist
 ↓
Gate-Level Simulation
