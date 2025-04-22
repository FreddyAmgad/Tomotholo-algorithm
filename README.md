# Tomasulo Algorithm Simulator

This project implements a simulator for the Tomasulo Algorithm — a dynamic scheduling technique used in modern CPUs to enable out-of-order execution and improve instruction-level parallelism.

## 🔧 Features
- Simulates CPU pipeline stages: Issue, Execute, Write Back.
- Handles data hazards (RAW) and branch mispredictions.
- Supports arithmetic, logic, memory, and control instructions.
- Tracks instruction timing per stage and calculates performance metrics (total cycles, IPC, branch misprediction rate).
- Includes configurable reservation stations, memory, and register file.

## 🛠 Supported Instructions
- Arithmetic/Logic: `add`, `addi`, `nand`, `div`
- Memory Access: `load`, `store`
- Branching: `bne`, `call`, `ret`

## 📁 Input Files
- Instruction file (e.g., `Inst1.txt`)
- Optional memory initialization file
- Optional hardware configuration file

## 📤 Output
- Detailed cycle-by-cycle instruction log (Issue, Execute, Write Back)
- Performance summary: total cycles, IPC, and misprediction rate

## 👨‍💻 Contributors
- Freddy Amgad  
- Mario Ghaly  
- Fekry Mohamed
