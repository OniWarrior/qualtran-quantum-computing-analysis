# Analysis of Qualtran and the Necessity of Quantum Computers

This repository contains a research white paper analyzing the **Qualtran**
quantum algorithm framework and arguing for the **necessity of quantum computers**
from a computer science and systems perspective.

The work focuses on software abstractions, resource estimation, scalability,
and fundamental limitations of classical computing, rather than on numerical
simulation or hardware execution.

---

## Overview

Qualtran is a Python-based framework designed to help manage the complexity of
large-scale quantum algorithms through composable abstractions, resource
estimation, and algorithm analysis.

This paper:
- summarizes the design philosophy of Qualtran
- evaluates its strengths and limitations
- examines its potential impact on quantum software development
- connects these ideas to fundamental problems in classical computer science

---

## Key Topics Covered

### Qualtran Framework Analysis
- Bloqs as composable quantum abstractions
- Automated resource estimation (qubits, gates)
- Algorithm decomposition and call graphs
- Block encodings and quantum arithmetic
- Visualization and validation tooling

### Strengths and Limitations
- Improved usability and reproducibility
- Scalability to teraquop-scale algorithms
- Limitations in parallel execution assumptions
- Gaps in advanced data type support

### Computer Science Constraints
- CPU size scaling limits
- Quantum tunneling at nanometer scales
- The CPU power wall and thermal limits
- Limitations of multi-core and mutex-based parallelism

### Argument for Quantum Computing
- Why classical scaling is fundamentally constrained
- How superposition and entanglement enable new computational models
- Why quantum computing is not just beneficial, but necessary for continued
  technological progress

---

## Repository Contents

```
paper/
└── QuantumInformationWhitePaper.pdf

The PDF contains the complete research report submitted as part of the
University of Texas at Dallas Quantum Information certificate program.

---

## Scope and Intent

This repository is **analysis-focused**.

It does **not** contain:
- executable quantum code
- hardware experiments
- numerical simulations

Instead, it demonstrates:
- the ability to critically analyze quantum software frameworks
- systems-level reasoning about computation
- clear technical writing and argumentation
- understanding of both classical and quantum computing constraints

---

## Author

**Stephen Aranda**  
B.S. Computer Science — University of Texas at Dallas  

Interests:
- Quantum computing
- Quantum software frameworks
- Resource estimation and scalability
- Systems-level computing constraints

---

## Notes

This work was written as a university research white paper but is preserved here
as a reference artifact to document analytical and research-oriented work in
quantum information science.