# Day 4 – GLS, Blocking vs Non-Blocking and Synthesis-Simulation Mismatch

## Overview
This repository contains my Day 4 work from the **SKY130 RTL Design and Synthesis Workshop** conducted through VSDIAT.

The focus of this day is understanding Gate-Level Simulation (GLS), blocking and non-blocking assignments, and the causes of synthesis-simulation mismatches in Verilog HDL.

## Topics Covered

### 1. Gate-Level Simulation (GLS)
- Introduction to Gate-Level Simulation.
- Understanding GLS concepts.
- Difference between RTL simulation and Gate-Level Simulation.
- Importance of GLS in digital design verification.

### 2. Blocking vs Non-Blocking Assignments
- Understanding blocking (`=`) assignments.
- Understanding non-blocking (`<=`) assignments.
- Differences in execution and scheduling.
- Importance of choosing the correct assignment type in sequential and combinational logic.

### 3. Synthesis-Simulation Mismatch
- Understanding synthesis-simulation mismatch.
- Blocking statement-related mismatches.
- Simulation behavior and synthesized hardware behavior.
- Identifying and avoiding RTL coding issues.

### 4. Practical Labs
- GLS concepts and synthesis-simulation experiments.
- Blocking statement simulation experiments.
- Understanding simulation waveform differences.
- Analyzing RTL behavior using GTKWave.

## Tools Used
- Verilog HDL
- Yosys
- Icarus Verilog
- GTKWave
- SKY130 Standard Cell Library
- Ubuntu Linux

## Key Learnings
- Understood the fundamentals of Gate-Level Simulation.
- Learned the differences between blocking and non-blocking assignments.
- Explored synthesis-simulation mismatches.
- Analyzed RTL simulation waveforms using GTKWave.
- Improved understanding of proper Verilog coding practices.

## Repository Structure

```text
SKY130-Day04-GLS-Blocking-NonBlocking/
│
├── verilog_files/
│   ├── Verilog source files
│   └── Testbench files
│
├── screenshots/
│   ├── GLS waveforms
│   ├── Blocking assignment results
│   └── Synthesis-simulation mismatch results
│
└── README.md
```

## Workshop Progress

| Day | Topics | Status |
|---|---|---|
| Day 1 | Introduction to Verilog RTL Design and Synthesis | Completed |
| Day 2 | Timing Libraries, Hierarchical Design and Flip-Flops | Completed |
| Day 3 | Combinational and Sequential Logic | Completed |
| Day 4 | GLS, Blocking vs Non-Blocking and Synthesis-Simulation Mismatch | Completed |

## Acknowledgement
Thanks to **Kunal Ghosh and the VSDIAT team** for providing practical learning resources on RTL design and synthesis.

---
**Learning VLSI Design, One Day at a Time!**
