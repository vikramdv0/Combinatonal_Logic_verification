# Combinational Logic Verification

## Project Overview
Design and verification of a 2:1 Multiplexer using Verilog HDL.

## Tools Used
- Verilog HDL
- Icarus Verilog
- GTKWave
- GitHub

## Project Structure
- rtl/mux.v        : Design file
- tb/mux_tb.v      : Testbench
- mux.vcd          : Waveform output

## Simulation
iverilog -o mux_out rtl/mux.v tb/mux_tb.v
vvp mux_out
gtkwave mux.vcd
