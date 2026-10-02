# 3x3 Multiplier

A 3-bit by 3-bit multiplier implemented in Verilog, taken from RTL through to a GDSII layout.

## Overview

[1-2 sentences: what the design does, e.g. "Multiplies two 3-bit unsigned inputs and produces a 6-bit product."]

## Repository Structure

- `RTL/` - Verilog source files
- `TB/` - testbenches
- `MUL3X3_RTL_IMP_TOP.gds` - final layout of the top module

## Top Module

`MUL3X3_RTL_IMP_TOP`

| Port | Direction | Width | Description |
|------|-----------|-------|-------------|
| a    | input     | 3     | Multiplicand |
| b    | input     | 3     | Multiplier   |
| p    | output    | 6     | Product      |

## How to Simulate

[Your command, e.g. `iverilog -o sim RTL/*.v TB/*.v && vvp sim`]

## Results

- Technology / PDK: [e.g. sky130]
- Area: [value]

## GDS Viewer

- [View in 3D GDS Viewer](https://gds-viewer.tinytapeout.com/?model=https://raw.githubusercontent.com/fahim-islam15/MUL3X3/master/MUL3X3_RTL_IMP_TOP.gds)
- [View in Tiny Tapeout Explorer](https://gds-explorer.tinytapeout.com/viewer.html?gds=https://raw.githubusercontent.com/fahim-islam15/MUL3X3/master/MUL3X3_RTL_IMP_TOP.gds)
