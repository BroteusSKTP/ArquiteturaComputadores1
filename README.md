# Computer Architecture I — University of Évora

> Projects and exercises developed for the **Computer Architecture I** course at [University of Évora](https://www.uevora.pt/), Portugal.

---

## 📋 Table of Contents

- [About the Course](#about-the-course)
- [Topics Covered](#topics-covered)
- [Projects & Exercises](#projects--exercises)
- [Technologies & Tools](#technologies--tools)
- [Skills Demonstrated](#skills-demonstrated)
- [How to Run](#how-to-run)
- [Author](#author)

---

## About the Course

**Computer Architecture I** is a foundational course in Computer Engineering and Informatics at the University of Évora. It covers the low-level organisation of computer systems — from transistors and logic gates, all the way up to assembly language programming and processor pipelines.

The coursework combines theoretical study with hands-on projects, giving students direct experience with how modern processors are designed and how software interacts with hardware.

---

## Topics Covered

| # | Topic |
|---|-------|
| 1 | Boolean Algebra & Logic Simplification (Karnaugh Maps) |
| 2 | Combinational Logic Circuits (Adders, Multiplexers, Decoders) |
| 3 | Sequential Logic Circuits (Flip-Flops, Registers, Counters) |
| 4 | Finite State Machines (FSM) |
| 5 | Memory Organisation (RAM, ROM, Cache) |
| 6 | MIPS Instruction Set Architecture (ISA) |
| 7 | MIPS Assembly Language Programming |
| 8 | Datapath & Control Unit Design |
| 9 | Pipelining & Hazard Detection |
| 10 | I/O Systems & Interrupts |

---

## Projects & Exercises

### 🔢 Combinational Circuits
Design and simulation of combinational logic circuits using **Logisim**, including:
- Arithmetic Logic Unit (ALU) supporting ADD, SUB, AND, OR, XOR, and comparison operations
- Binary multiplier and divider circuits
- 7-segment display decoder

### ⏱️ Sequential Circuits & FSMs
- Design of Moore and Mealy finite state machines
- Synchronous counter design with reset and load capabilities
- Register file implementation

### 🖥️ MIPS Assembly Programming
Programs written in MIPS assembly language and simulated with **MARS (MIPS Assembler and Runtime Simulator)**:
- Sorting algorithms (Bubble Sort, Selection Sort) operating on arrays stored in memory
- Recursive subroutines (factorial, Fibonacci) using the call stack
- String manipulation routines (length, copy, reverse)
- Interrupt-driven I/O handling

### ⚙️ Processor Datapath Design
- Single-cycle MIPS processor datapath implementation in Logisim
- Multi-cycle processor control unit with microprogramming
- 5-stage pipeline with forwarding unit and hazard detection

---

## Technologies & Tools

| Tool | Purpose |
|------|---------|
| [Logisim-Evolution](https://github.com/logisim-evolution/logisim-evolution) | Digital circuit design & simulation |
| [MARS MIPS Simulator](http://courses.missouristate.edu/KenVollmar/mars/) | MIPS assembly IDE & simulator |
| MIPS Assembly | Low-level programming language |
| Boolean algebra / Karnaugh Maps | Logic minimisation |

---

## Skills Demonstrated

- **Digital Logic Design** — combinational and sequential circuits from gate level up
- **Low-Level Programming** — MIPS assembly, memory-mapped I/O, stack management
- **Computer Organisation** — understanding of how a CPU fetches, decodes, and executes instructions
- **Pipeline Architecture** — data hazard identification, forwarding paths, branch prediction concepts
- **Problem Solving** — translating high-level algorithms into constrained assembly code
- **Documentation** — clear circuit schematics, commented assembly source, and written reports

---

## How to Run

### MIPS Assembly (MARS Simulator)
1. Download [MARS](http://courses.missouristate.edu/KenVollmar/mars/) (`Mars4_5.jar` or later).
2. Open MARS: `java -jar Mars4_5.jar`
3. `File → Open` any `.asm` file from this repository.
4. Click **Assemble** then **Run** to execute.

### Digital Circuits (Logisim-Evolution)
1. Download [Logisim-Evolution](https://github.com/logisim-evolution/logisim-evolution/releases).
2. Open Logisim-Evolution: `java -jar logisim-evolution.jar`
3. `File → Open` any `.circ` file from this repository.
4. Use the **Simulate** menu to run or step through the circuit.

---

## Author

**BroteusSKTP**  
Computer Engineering Student — University of Évora, Portugal  
[GitHub Profile](https://github.com/BroteusSKTP)

---

*Developed as part of the Computer Engineering degree at the University of Évora.*
