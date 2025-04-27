# AlgosInCuda
Graph Algorithms in CUDA (PyCUDA)
This project implements and compares the performance of three classic graph algorithms — BFS, Dijkstra, and PageRank — on CPU and GPU (using PyCUDA).
The goal is to measure speedups achieved by GPU acceleration and validate the correctness of GPU implementations against their CPU counterparts.

Algorithms Implemented: Breadth-First Search (BFS), Dijkstra's Shortest Path Algorithm, PageRank Algorithm

Each algorithm is implemented in:
Pure CPU (NumPy + Python)
GPU using PyCUDA

Features
Performance Benchmarking:Measures and compares runtime for CPU vs GPU.

Correctness Verification:Ensures GPU results match CPU results (within a tolerance for floating-point calculations).

Speedup Calculation:Reports how many times faster GPU execution is compared to CPU execution.
