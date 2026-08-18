# MIND Seminar

> Note: Seminar materials are still being refined and may be updated.

Technical presentation materials prepared for the MIND Seminar, a student-led seminar at Seoul National University.

## Seminar Structure

The MIND Seminar covers a broader range of computing topics presented by multiple participants.

My part focuses on **classical computing**, covering its theoretical foundations, computational limits, architecture, and applications:

1. The Power and Limits of Computation
2. CPU Architecture and Data Movement
3. From Efficient Computation to Computational Hardness

Other participants present additional topics related to next-generation computing.

## Presentations

### 1. The Power and Limits of Computation

An introduction to the theoretical foundations and limitations of classical computation.

Topics include:

- Finite State Machines
- Deterministic Finite Automata (DFA)
- Implementing finite automata
- Pushdown Automata (PDA)
- Context-Free Grammars (CFG)
- Turing Machines
- The Halting Problem
- Undecidability
- Computational complexity and P vs. NP

[Current slides](slides/01-computation.pdf) · [Notes](notes/01-computation.md)

### 2. CPU Architecture and Data Movement

An introduction to how classical computation is realized in hardware, primarily using **RISC-V** as the underlying instruction set architecture.

Topics include:

- RISC-V instructions and execution
- Datapath and control
- Single-cycle CPU architecture
- Pipelined CPU architecture
- Instruction execution
- Data movement within the processor
- Pipeline behavior and hazards

[Current slides](slides/02-cpu-architecture.pdf) · [Notes](notes/02-cpu-architecture.md)

### 3. From Efficient Computation to Computational Hardness

An exploration of efficient algorithms, data structures, computational complexity, and how computational hardness connects to cryptography.

Topics:

- Algorithmic efficiency and time complexity
- Stacks, queues, heaps, and segment trees
- Greedy algorithms and dynamic programming
- Using data structures to optimize algorithms
- Decision problems, P, NP, NP-hardness, and NP-completeness
- Polynomial-time reductions
- Hamiltonian Cycle and the Traveling Salesman Problem
- Public-key cryptography and RSA

[Current slides](slides/03-efficient-computation-and-hardness.pdf)

## Scope

Together, the presentations follow classical computing from abstract models of computation to physical implementation and practical applications:

**Theory of Computation → Limits of Computation → CPU Architecture → Algorithms → Computational Complexity → Cryptography**

## References

Presentation materials were prepared with reference to course materials including:

* Prof. Kunsoo Park — Theory of Computation
* Prof. Dae R. Jeong — Computer Architecture
