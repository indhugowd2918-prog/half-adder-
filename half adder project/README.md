# Half Adder using Verilog

## Overview

A Half Adder is a basic combinational circuit that adds two 1-bit binary numbers.

It has:

- Two Inputs: A and B
- Two Outputs:
  - SUM
  - CARRY

## Truth Table

| A | B | SUM | CARRY |
|---|---|-----|-------|
| 0 | 0 | 0 | 0 |
| 0 | 1 | 1 | 0 |
| 1 | 0 | 1 | 0 |
| 1 | 1 | 0 | 1 |

## Boolean Equations

SUM = A XOR B

CARRY = A AND B

## Files

- `half_adder.v` - Verilog design
- `half_adder_tb.v` - Testbench
- `simulation_output.txt` - Simulation results

## Simulation

Run using ModelSim or Icarus Verilog.

### Compile

```bash
iverilog -o halfadder half_adder.v half_adder_tb.v
```
