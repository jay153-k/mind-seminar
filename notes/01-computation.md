# The Power and Limits of Computation

## Overview

This presentation explores what computation is, what different models of computation can express, and whether there are problems that no computer can solve.

## Topics

### Finite State Machines and DFA

The presentation begins with combinational and sequential logic, then introduces finite state machines as systems whose behavior depends on stored state. A DFA is presented as a formal model of finite-state computation.
Regular languages can be described using equivalent models such as DFA, NFA, regular expressions, and regular grammars. The limitation of finite-state computation is illustrated using languages that require unbounded memory.

### Context-Free Grammars and PDA

Context-free grammars are introduced as a way to generate structured languages, together with parse trees and ambiguity.

A pushdown automaton extends finite-state computation with a stack, allowing it to recognize languages such as (0^n1^n). Its limitations motivate a more general computational model.

### Turing Machines

Turing machines provide a general model of computation using a read/write tape and finite control. The presentation also connects Turing-machine components with modern CPU concepts such as memory, addresses, control state, and execution logic.

### Computability and Undecidability

The final part distinguishes recursively enumerable and recursive languages, introduces the Church-Turing thesis and universal Turing machines, and studies undecidable problems such as the Halting Problem and Post Correspondence Problem.

## Main Takeaway

The models form a progression:

**Finite State Machines → Pushdown Automata → Turing Machines**

More powerful memory models increase what can be computed, but even Turing machines have fundamental limits.
