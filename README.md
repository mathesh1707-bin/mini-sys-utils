# mini-sys-utils

A collection of small Linux system utilities written in C to understand
memory, processes, and system calls.

## Goals
- Learn C memory model (stack vs heap)
- Understand Linux file descriptors
- Explore process creation and execution
- Use raw syscalls instead of libc wrappers

## Tools
- mem_inspect : explore memory layout
- file_cat    : syscall-based file reader
- proc_info   : process lifecycle demo

## Build
```bash
make
