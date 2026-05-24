# IDATT2101 Algorithms and Data Structures Coursework

## Overview
This repository contains my Java coursework solutions for IDATT2101 (Algoritmer og datastrukturer) at NTNU.
It includes assignment source files and report PDFs from the course period.

## Course Context
- Course: `IDATT2101 - Algoritmer og datastrukturer`
- Institution: `NTNU`
- Type: student coursework repository (not a production library)

## Repository Structure
```text
kode/      Java source files for Oving1-Oving7
ovinger/   PDF reports for selected assignments
docs/      Extra documentation (data file notes)
```

## Assignment Overview

| Assignment | Main focus | Source file |
| --- | --- | --- |
| Oving1 | Best buy/sell day from stock price changes | `kode/Oving1.java` |
| Oving2 | Exponentiation methods and complexity comparison | `kode/Oving2.java` |
| Oving3 | QuickSort vs Dual-Pivot QuickSort benchmarking | `kode/Oving3.java` |
| Oving4 | Hash tables, collision handling, and HashMap comparison | `kode/Oving4.java` |
| Oving5 | Directed graph and strongly connected components (Kosaraju) | `kode/Oving5.java` |
| Oving6 | LZW compression/decompression with file I/O | `kode/Oving6.java` |
| Oving7 | Dijkstra shortest path and nearest-attraction search | `kode/Oving7.java` |

## Topics Covered
- Recursion and asymptotic complexity
- Sorting algorithms
- Hashing and collision handling
- Graph representations and traversals
- Shortest path algorithms (Dijkstra)
- Strongly connected components
- Data compression (LZW)
- Runtime measurement and simple benchmarking

## How To Compile/Run Java Files

From the repository root:

```bash
cd kode
```

Simplest way (Java 11+ source-file mode):

```bash
java Oving1.java
java Oving2.java
java Oving3.java
java Oving4.java
java Oving5.java
java Oving6.java
java Oving7.java
```

Note: some files have public class names that differ from the filename (for example `Oving1.java` and `Oving7.java`), so running them directly in source-file mode is the most practical approach here.

## Required External Data Files
Some assignments reference input files that are not included in this repository.
See [`docs/DATA-FILES.md`](docs/DATA-FILES.md) for details.

## Limitations
- This is a coursework snapshot, not a polished framework or reusable library.
- No unified build system, test suite, or release setup.
- Several tasks rely on hardcoded input filenames/values.
- Not all original datasets used in assignments are included.

## Academic Integrity
This repository is shared for learning and portfolio documentation.
If you are taking the same/similar course, use it as reference only and write your own solutions.

## Status
Coursework files and reports were committed as a completed snapshot.
