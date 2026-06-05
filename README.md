# DSA-Visualizer

## Overview

**DSA-Visualizer** is an interactive, terminal-based application developed in C++ designed to demonstrate the step-by-step execution of fundamental data structures and algorithms. It provides real-time state changes for sorting, searching, and graph traversal algorithms, helping developers and students grasp low-level execution flows.


## Key Features

### 1. Sorting Algorithms

Visualizes the exact state of an array after each logical pass or iteration:

* **Bubble Sort:** Step-by-step element swapping and bubble-down visualization.
* **Insertion Sort:** Real-time shifting and insertion tracking.
* **Selection Sort:** Minimum/maximum element scanning and positioning.

### 2. Searching Algorithms

Demonstrates standard search mechanics with structural conditions:

* **Linear Search:** Sequential element evaluation.
* **Binary Search:** Visualizes pivot calculations, middle-index evaluation, and search-space reduction on pre-sorted arrays.

### 3. Graph Algorithms

Exhibits standard traversal techniques on structural data:

* **Breadth-First Search (BFS):** Layer-by-layer traversal using queue-based state tracking.
* **Depth-First Search (DFS):** Path-based recursive deep traversal.


## Technical Stack & Architecture

* **Core Language:** C++
* **Object-Oriented Programming (OOP):** Modular, class-based design separating algorithm logic from user interface components.
* **Standard Template Library (STL):** Leverages container primitives (`std::vector`, `std::queue`, `std::stack`, `std::map`) for efficient data manipulation and memory management.


## Execution Walkthrough

### Main Interface & Sorting Example

```text
==== DSA Visualizer ====
1. Sorting Algorithms
2. Searching Algorithms
3. Graph Algorithms
4. Exit
Enter choice: 1

Choose Sorting:
1. Bubble
2. Insertion
3. Selection
Choice: 1

Array: 5 3 8 4 2

Pass 1: 3 5 4 2 8
Pass 2: 3 4 2 5 8
Pass 3: 3 2 4 5 8
Pass 4: 2 3 4 5 8

Sorted Array: 2 3 4 5 8

```

### Searching Example (Binary Search)

```text
Choose Search:
1. Linear
2. Binary
Choice: 2
Enter element to search: 4

Sorted Array for Binary Search: 2 3 4 5 8
Checking middle index 2 -> 4
Element found at index 2

```

### Graph Traversal Example (BFS)

```text
Choose Graph:
1. BFS
2. DFS
Choice: 1

BFS Traversal: 0 1 2 3 4

```

---

## Setup & Installation

### Prerequisites

Ensure you have a C++ compiler installed (e.g., `g++` via GCC or Clang).

### Steps to Run

1. **Clone the repository:**
```bash
git clone https://github.com/Jashuva2007/DSA-Visualizer
cd DSA-Visualizer

```


2. **Compile the source code:**
```bash
g++ src/main.cpp -o dsa_visualizer

```


3. **Execute the binary:**
```bash
./dsa_visualizer

```
