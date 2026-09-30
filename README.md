# OS Debugging Project: Segmentation Faults and Memory Bugs

## Overview

This project demonstrates practical debugging of C programs in Linux/Ubuntu using:

- GCC
- GDB
- SIGSEGV
- Core dumps
- Valgrind
- Git

The project focuses on two common classes of programming errors:

1. Segmentation fault caused by NULL pointer dereference
2. Memory leak caused by dynamically allocated memory not being freed

---

## Project Structure

```text
OS-Debugging-Project/
│
├── src/
│   ├── faults/
│   │   ├── null_pointer.c
│   │   └── memory_leak.c
│   │
│   └── fixed/
│       ├── null_pointer_fixed.c
│       └── memory_leak_fixed.c
│
├── reports/
│   ├── gdb/
│   ├── core-dump/
│   └── valgrind/
│       ├── memory_leak_buggy.txt
│       └── memory_leak_fixed.txt
│
├── screenshots/
│
└── README.md
