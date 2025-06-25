# 32-bit Pipelined RISC Processor (Verilog)

This project implements a **32-bit pipelined RISC processor** in Verilog HDL. It supports a 5-stage pipeline:  
**IF → ID → EX → MEM → WB**, and covers basic arithmetic, logic, memory, and control instructions.

---

## 🚀 Features
- 5-stage pipeline: Instruction Fetch, Decode, Execute, Memory, Writeback
- Instruction Set:
  - R-type: ADD, SUB, AND, OR, SLT, MUL
  - I-type: ADDI, SUBI, SLTI, LW, SW
  - Branch: BEQZ, BNEQZ
  - HALT instruction
- Basic hazard handling (branch delay, halt detection)
- Supports memory-mapped I/O and register bank

## 🎓 What I Learned

- I learned how a CPU works step by step using a 5-stage pipeline.
- I improved my Verilog coding by designing modules like ALU, memory, and control.
- I used branching, memory access, and arithmetic operations in real hardware flow.
- I learned to test and debug my design using simulation and testbenches.
- This project gave me a strong base in computer architecture and hardware design.

## 📚 Resources Used

- 📘 *Computer Organization and Design*(RISC-V edition) by David A. Patterson & John L. Hennessy
     – helped me understand CPU architecture and pipelining concepts.
- 🎓 NPTEL course: *Digital System Design with Verilog*
   – guided me in writing and organizing Verilog code for hardware systems.


