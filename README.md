# Low-Level Programming on Linux (x86-64)
A Complete Series of 10 Technical Booklets  
By Ayman Alheraki

## Introduction

Low-Level Programming on Linux (x86-64) is a multi-volume technical series that teaches Linux systems programming using real x86-64 hardware, Intel-syntax assembly, and practical low-level engineering techniques.

The goal of this project is to provide a complete and structured path for learning:
- CPU architecture and memory hierarchy  
- Assembly programming with GAS (Intel syntax)  
- Linux system calls and process control  
- Memory management and custom allocators  
- ABIs and mixed C/Assembly development  
- ELF binary structure and manual inspection  
- Kernel module development  
- SIMD, AVX, and performance engineering  
- Minimal runtime design without using libc  

This repository includes all booklets, example code, tools, and reference material.

---

## Booklet Series (10 Volumes)

1. **Book 1 — Introduction to x86-64 Architecture and Memory**  
2. **Book 2 — Assembly Programming with GAS (Intel Syntax)**  
3. **Book 3 — Linux System Calls and Process Control**  
4. **Book 4 — Memory Management and Custom Allocators**  
5. **Book 5 — ABI and Interfacing Assembly with C/C++**  
6. **Book 6 — ELF and Binary Inspection**  
7. **Book 7 — Linux Kernel Module Development**  
8. **Book 8 — Low-Level Cryptography**  
9. **Book 9 — Performance Optimization and SIMD**  
10. **Book 10 — Minimal Runtime (No libc)**  

---

## What You Will Learn

By completing the entire series, you will gain the ability to:
- Understand x86-64 CPU internals at a practical level  
- Write optimized assembly using Intel syntax  
- Use Linux system calls directly  
- Analyze and build ELF binaries manually  
- Develop safe and functional kernel modules  
- Implement custom allocators and memory abstractions  
- Use SIMD instructions for performance optimization  
- Build complete programs without any standard C library  

---

## Repository Structure





/

├─ booklets/ # PDF versions of all 10 booklets

├─ code/ # Assembly, C, C++, syscall, ELF, SIMD examples

├─ samples/ # Minimal executables and runtime demos

├─ kernel/ # Kernel module examples

├─ simd/ # AVX and SIMD performance samples

├─ tools/ # Helper scripts, analyzers, utilities

└─ README.md







---

## Recommended Learning Path

1. Start with CPU architecture and memory fundamentals (Book 1)  
2. Learn to write real Intel-syntax assembly (Book 2)  
3. Explore system calls and OS interfaces (Book 3)  
4. Understand stack, heap, and memory allocators (Book 4)  
5. Master ABIs and linking between C and Assembly (Book 5)  
6. Dive into ELF binary structure and loaders (Book 6)  
7. Study kernel module development (Book 7)  
8. Strengthen bit-level skills with cryptography (Book 8)  
9. Learn performance engineering and SIMD (Book 9)  
10. Build minimal runtimes without libc (Book 10)

---

## Tools and Technologies

- GCC, GAS (Intel syntax), Clang/LLVM  
- GDB, objdump, readelf  
- strace, perf, valgrind  
- procfs, sysfs, DebugFS  
- x86-64 Intel and AMD manuals  
- Linker scripts and startup code  
- Linux kernel build tools  

---

## Contributions

Contributions are welcome.  
You may submit:
- Code improvements  
- Bug fixes  
- Additional examples  
- Clarifications or enhancements  
- Translation suggestions  

Use Issues or Pull Requests.

---

## Support

If this series has helped you, please consider starring the repository on GitHub to support future expansions and updates.

---

## Contact

Ayman Alheraki  
Technical Author & Systems Programmer
