# FPGA Secure Boot Status Peripheral

## Overview
Verilog RTL project implementing a secure-boot status monitoring peripheral for a Zynq-7000 FPGA platform.

The design monitors boot/authentication status, stores results, provides AXI4-Lite register access, and generates status indications.

## Features
- AXI4-Lite register interface
- Boot monitoring FSM
- IDLE, BOOTING, PASS, FAIL states
- Latched authentication failure
- Error-code storage
- Status monitoring output

## Flow
RTL -> Simulation -> Synthesis -> Timing Analysis

## Tools
- AMD Vivado
- Verilog/SystemVerilog
- XSim

## Target
- Xilinx Zynq-7000 (XC7Z045)
