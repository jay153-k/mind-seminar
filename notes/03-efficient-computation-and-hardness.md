# From Efficient Computation to Computational Hardness

## Overview

This presentation explores how data structures and algorithms improve computational efficiency, and how these ideas lead to a deeper question: which computational problems can be solved efficiently at all?

It begins with practical techniques for reducing running time, then moves toward computational complexity and the limits of efficient exact algorithms. The final part connects computational hardness to public-key cryptography.

## Topics

### Data Structures and Efficiency

Introduces stacks, queues, binary heaps, and segment trees, with an emphasis on how the choice of data structure determines which operations can be performed efficiently.

The segment tree is used as a representative example of a structure that supports both range queries and point updates in logarithmic time, illustrating how additional structure can improve repeated computations.

### Greedy Algorithms and Dynamic Programming

Explores two major algorithm design paradigms.

Greedy algorithms repeatedly make locally optimal choices, but require a proof that these choices lead to a global optimum. Dynamic programming instead stores solutions to overlapping subproblems and combines them using carefully defined states and transitions.

Examples such as coin change are used to compare when greedy approaches succeed and when dynamic programming is necessary.

### From Efficient Algorithms to Hard Problems

After studying ways to improve algorithms, the presentation asks whether every computational problem can be solved efficiently.

This leads to decision problems and the complexity classes P and NP, followed by the definitions of NP-hardness and NP-completeness.

### Polynomial-Time Reductions

Polynomial-time reductions are introduced as a way to compare the difficulty of computational problems.

The presentation explains how known NP-complete problems can be transformed into other problems and uses the reduction from Hamiltonian Cycle to the decision version of the Traveling Salesman Problem as a concrete example.

### Computational Hardness and Cryptography

The final section connects computational difficulty to public-key cryptography.

RSA is introduced through key generation, encryption, and decryption, followed by the idea that its security is closely related to the difficulty of factoring large composite integers.

The presentation also distinguishes this form of computational hardness from NP-completeness.

## Main Takeaway

**Efficient Data Structures → Algorithm Design → Computational Complexity → Computational Hardness**

Data structures and algorithmic techniques can dramatically improve the efficiency of computation, but some problems appear to resist efficient exact solutions.

Understanding both efficient computation and computational hardness is important not only for algorithm design, but also for understanding why some modern cryptographic systems can be secure.