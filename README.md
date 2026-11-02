# MIND Seminar

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

An introduction to formal models of computation and the fundamental limits of what computers can solve.

Topics:

- Finite State Machines and DFA
- Context-Free Grammars and Pushdown Automata
- Turing Machines
- Decidability and recognizability
- The Halting Problem and undecidability
- Reductions and Rice's Theorem
- Computational complexity and P vs. NP

[Slides](slides/01-computation.pdf) · [Notes](notes/01-computation.md)

### 2. CPU Architecture and Data Movement

A RISC-V-centered introduction to how instructions are executed and how data moves through a processor.

Topics:

- Instruction Set Architecture and RISC-V
- Instruction formats and execution
- Single-cycle datapaths
- Control and data movement
- Pipelining
- Data and control hazards
- Forwarding, stalls, and branch prediction

[Slides](slides/02-cpu-architecture.pdf) · [Notes](notes/02-cpu-architecture.md)

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

[Slides](slides/03-efficient-computation-and-hardness.pdf) · [Notes](notes/03-efficient-computation-and-hardness.md)

## Scope

**Theory of Computation → Limits of Computation → CPU Architecture → Algorithms → Computational Complexity → Cryptography**

## References

Presentation materials were prepared with reference to course materials including:

* Prof. Kunsoo Park — Theory of Computation
* Prof. Dae R. Jeong — Computer Architecture
