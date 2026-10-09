# LEON3 Embedded Software Development and Hamming Error Correction

**C Programming | LEON3 SPARC V8 | TSIM | BCC2 | GitLab CI/CD | Error-Correcting Codes**

## Project Overview

This academic project investigates the LEON3 embedded software development environment for space avionics applications.

The work focuses on cross-compilation, processor simulation, performance benchmarking, and the development and optimisation of a Hamming(31,26) error-correction algorithm.

## Project Objectives

- Investigate the LEON3 SPARC V8 architecture.
- Explore the BCC2 cross-compilation toolchain and TSIM simulator.
- Benchmark simulated processor performance using Dhrystone.
- Implement Hamming(31,26) encoding and decoding in C.
- Optimise computational performance through bitwise operations and lookup tables.
- Reconstruct a JPEG payload using single-bit error correction.
- Examine GitLab version control and CI/CD workflows.

## Tools and Technologies

- C programming
- LEON3 SPARC V8
- Gaisler BCC2
- TSIM3
- GitLab CI/CD
- Dhrystone benchmarking
- Hamming(31,26) error correction

## Performance Results

| Metric | Baseline | Optimised |
|---|---:|---:|
| Encoding throughput | 5,329 words/s | 130,281 words/s |
| Decoding throughput | 5,448 words/s | 126,319 words/s |

The optimised implementation uses bitwise operations, reduced loop overhead, and lookup-table-based parity computation.

The payload decoding demonstration reported 393 detected and corrected single-bit errors, with successful JPEG reconstruction.

## Limitations

The reported performance measurements were obtained in a simulated LEON3 environment rather than on physical spacecraft hardware.

The original development environment was hosted on a university GitLab instance. Repository source files and test infrastructure may not all be available for independent reproduction.

## Documentation

The technical report describes the development environment, optimisation approach, benchmarking results, and error-correction implementation.

## Author

Mehwish Akram

MSc Astronautics & Space Engineering
