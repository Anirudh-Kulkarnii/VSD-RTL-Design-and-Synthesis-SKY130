# Day 5 — Synthesis Optimization Using If, Case, For and Generate

## Topics Covered

- If statements
- Incomplete if statements
- Case statements
- Incomplete case statements
- Partial assignments
- For loops
- Generate constructs
- Multiplexer implementations
- Counter implementations

## Lab Work

The final labs explored how common Verilog coding constructs are interpreted by synthesis.

Incomplete if and case statements were studied to understand latch inference and the importance of complete assignments.

For-loop and generate-based RTL descriptions were examined as methods for describing repeated hardware structures.

Multiplexer and counter implementations were also synthesized to observe how coding style affects the generated hardware.

## Tools Used

- Yosys
- Icarus Verilog
- GTKWave
- SKY130 standard-cell library

## Key Learning

Verilog RTL is a hardware description, so constructs such as if, case, for and generate directly influence the hardware inferred by synthesis. Writing complete and synthesis-friendly RTL is important for predictable implementation.
