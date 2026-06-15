# Fluid Simulation OpenMP

OpenMP implementation of a 3D fluid simulation focused on CPU parallelization and performance optimization. The project uses profiling with `perf` to identify performance bottlenecks and applies OpenMP techniques such as `parallel for`, `collapse`, `reduction`, `simd`, and thread synchronization to accelerate computationally intensive loops.

The implementation explores shared-memory parallelism and evaluates scalability by comparing speedup across different numbers of threads.
