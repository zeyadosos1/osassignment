# Operating Systems - Assignment 2

**Course:** CSE233 - Operating Systems 
**University:** Alamein International University 
**Faculty:** Computer Science & Engineering

## Description

This repository contains the solutions for **Assignment 2** of the Operating Systems course.
The assignment focuses on basic **forks** and **C-style development**. It includes examples of process creation using `fork()`, explanations of the linker and loader, a working Makefile, and instructions for running the programs.

## Contents

* `*.c` files: C source code examples from Lab-5
* `Makefile`: Compile and run all the examples
* `README.md`: Project overview and instructions
* `LICENSE`: Open-source license for the project
* `screenshots/`: Screenshots of compiled and executed programs

## Fork Examples

The C programs demonstrate:

* Creating child processes using `fork()`
* Differentiating between parent and child processes
* Basic process management concepts

## How to Compile and Run

1. Open terminal in the repository directory.
2. Compile the programs using the Makefile:

```bash
make
```

3. Run any program, for example:

```bash
./process_creation
```

4. Clean compiled files:

```bash
make clean
```

## Makefile Targets

* `all`: Compiles all programs
* `clean`: Removes object and executable files
* `[program_name]`: Compile a specific program

## License

This project is licensed under the **MIT License**. See `LICENSE` for details.

## Author

* Student: Zeyad Osama 23101566
* Course: CSE233 - Operating Systems


