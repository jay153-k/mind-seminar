# CPU Architecture and Data Movement

## Overview

This presentation examines how source code is translated into machine instructions and how those instructions move data through a RISC-V processor. The central idea is that program execution can be viewed as controlled data movement.

## Topics

### RISC-V and the ISA

The presentation distinguishes an instruction set architecture from a microarchitecture. RISC-V defines the software/hardware interface, while single-cycle and pipelined CPUs are possible hardware implementations of that ISA.

RISC-V uses a load-store architecture: arithmetic operates on registers, while memory is accessed through explicit load and store instructions.

### Single-Cycle CPU

A single-cycle processor completes one instruction per clock cycle through the conceptual stages:

**Fetch → Decode → Execute → Memory → Write Back**.

The presentation follows several RISC-V instructions—`ADD`, `ADDI`, `LW`, `SW`, and `BEQ`—from their instruction formats and semantics to the corresponding datapaths and control signals.

A short RISC-V program is then used to show how a high-level statement becomes a sequence of movements between memory, registers, and the ALU.

### Pipelining

The clock period of a single-cycle CPU is determined by the slowest instruction, motivating pipelining.

A five-stage pipeline overlaps multiple instructions to improve throughput:

**IF → ID → EX → MEM → WB**.

The final section introduces data hazards and control hazards, along with techniques such as forwarding, stalls, flushes, and branch prediction.

## Main Takeaway

RISC-V defines what instructions mean, while CPU microarchitecture determines how they are executed.

A single-cycle design is simple but limited by its critical path, while pipelining improves throughput at the cost of handling instruction dependencies and control hazards.
