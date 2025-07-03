# Python Core Implementation Tasks – Interview Practice

This repository includes 5 important Python coding tasks often asked in technical interviews. Each task highlights fundamental Python concepts like generators, comprehension, data structures, and memory management.

## Task 1: Fibonacci Generator using `yield`

Creates an infinite generator that yields Fibonacci numbers one at a time. The use of `yield` ensures lazy evaluation, making it memory-efficient and suitable for generating sequences of unknown length.

**Key Concepts**: Generator, `yield`, infinite sequence, lazy loading.

**Use Case**: Efficient number series generation in low-memory environments or real-time processing.

---

## Task 2: Finding Most Common Items using `Counter`

Uses Python’s built-in `collections.Counter` to count item frequencies in a list and return the most common ones. This approach avoids manual counting logic.

**Key Concepts**: Frequency counting, built-in modules, list analysis.

**Use Case**: Word frequency in text, top-selling products, repeated patterns.

---

## Task 3: Dictionary Comprehension for Transformation

Demonstrates how to transform an existing dictionary into a new one using dictionary comprehension. This includes modifying values, filtering keys, or remapping structure.

**Key Concepts**: Dict comprehension, transformation, key-value manipulation.

**Use Case**: Feature engineering, config remapping, filtering metadata.

---

## Task 4: Priority Queue using `heapq`

Implements a basic priority queue using Python’s `heapq` module. Elements are added with priority and always served in order of priority (min-heap by default).

**Key Concepts**: Heaps, tuple sorting, task scheduling.

**Use Case**: Background job queues, CPU task scheduling, simulations.

---

## Task 5: Manual Deep Copy Without `copy.deepcopy`

Manually deep copies a nested data structure (like dict of lists or list of dicts) without using Python’s built-in `copy.deepcopy()`, using recursion to clone inner elements.

**Key Concepts**: Recursion, type checking, deep vs. shallow copy.

**Use Case**: Custom serialization, data backups, avoiding shared references.

---
 
