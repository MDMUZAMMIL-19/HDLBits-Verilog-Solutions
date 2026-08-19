# HDLBits Verilog Solutions

This repository contains structured Verilog HDL solutions for problem sets on [HDLBits](https://hdlbits.01xz.net/), covering foundational syntax, digital circuit synthesis, procedural modeling, waveform debugging, and testbench verification.

---

### Curriculum Breakdown

| Section | Domain / Topic | Key Concepts & Modules Covered |
| :--- | :--- | :--- |
| **1. Getting Started** | Environment & Syntax Basics | Wire assignments, output grounding, basic module declarations |
| **2. Verilog Language** | Core Language Features | Vectors, module hierarchy, procedural `always` blocks, `if/case` branches, latches avoidance |
| **3. Circuits** | Digital Logic Design | Combinational logic (arithmetic, multiplexers, decoders) and Sequential logic (flip-flops, counters, FSMs) |
| **4. Verification: Reading Simulations** | Waveform Debugging | Reconstructing digital circuits and identifying faults directly from simulation waveforms |
| **5. Verification: Writing Testbenches** | Functional Verification | Generating clock signals, stimulus vectors, assertions, and automated testbenches |

---

### Detailed Module Highlights

* **Procedural Modeling:** Behavioral logic implementations comparing `always @(*)` combinational blocks with edge-triggered clocked blocks.
* **Latch Mitigation:** Avoiding unintended inferred latches through complete assignment branches and default `case` conditions.
* **Complex Combinational Blocks:** Implementing priority encoders using both parallel conditional logic and `casez` bit-masking.
* **Hierarchy & Modularity:** Submodule instantiation, port mapping by name vs. position, and multi-bit bus interconnects.

---
├── 4. Verification Reading Simulations/
├── 5. Verification Writing Testbenches/
└── README.md
