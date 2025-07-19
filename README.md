# Parallel and Distributed Computing Portfolio: High-Performance C/C++ Solutions

Welcome to my curated portfolio of projects in Parallel and Distributed Computing. This collection demonstrates my expertise in designing, implementing, and optimizing high-performance applications using various parallel programming models and distributed systems concepts in C and C++. My work focuses on leveraging modern hardware architectures and inter-process communication techniques to achieve significant performance gains for computationally intensive tasks.

## Key Skills & Technologies Demonstrated:

* **Multithreading:** `pthreads`, `mutexes`, `condition variables`, `deadlock prevention`, `thread-safe data structures`.
* **Shared Memory Parallelism:** `OpenMP`, `#pragma omp parallel for`, `reduction`, `critical sections`, `atomic operations`, `performance analysis on multi-core CPUs`.
* **GPU Programming:** `CUDA` (kernels, memory management, `shared memory`, `thread block/grid configuration`, `streams`), `OpenCL` (host and kernel programming, device interaction, cross-vendor compatibility).
* **Distributed Memory Parallelism:** `MPI` (Message Passing Interface), `MPI_Send/Recv`, `MPI_Bcast`, `MPI_Scatterv`, `MPI_Gatherv`, `MPI_Reduce`, `halo exchange`, `master-worker architecture`.
* **Networking:** `Sockets` (TCP client/server, asynchronous communication).
* **High-Performance Computing (HPC):** Experience with `HPC cluster environments` (SINES NUST), `job submission (SGE/Slurm concepts)`, `node probing and resource mapping`, `heterogeneous computing`.
* **Performance Optimization:** `Profiling`, `Benchmarking`, `Scalability Analysis (Speedup, Efficiency)`, `Algorithm Optimization` (e.g., matrix multiplication, convolution, numerical integration, Laplace solver, machine learning algorithms).
* **Core C/C++:** `Dynamic Memory Management`, `Pointers`, `Multi-dimensional Arrays (1D-mapped)`, `Object-Oriented Programming (if used)`, `Data Structures`, `Algorithmic Development`, `CMake/Makefiles`.
* **Machine Learning (Parallelized):** `Linear Regression`, `Logistic Regression`, `Gradient Descent`.

## Project Showcase:

Explore my specialized projects below, each highlighting a core aspect of parallel and distributed computing.

---

### 1. [Shared Memory Parallelism with Pthreads and OpenMP](https://github.com/YourUsername/Shared-Memory-Parallelism-C)
* **Focus:** Core multithreading concepts, race condition resolution, and OpenMP for shared memory optimization.
* **Highlights:** Demonstrates efficient use of `pthreads` for concurrent tasks, `mutexes` for critical sections, and `OpenMP` directives for automatic parallelization of loops and blocks. Includes performance comparisons and analysis of synchronization overheads. Also features optimized summation, matrix multiplication, and 2D convolution.

### 2. [GPU Accelerated Computing with CUDA and OpenCL](https://github.com/YourUsername/GPU-Accelerated-Computing-C)
* **Focus:** Harnessing the power of GPUs for massive parallelism.
* **Highlights:** Features `CUDA` kernel development for NVIDIA GPUs and `OpenCL` for cross-platform GPU acceleration. Projects cover matrix operations, 2D convolution, numerical integration, and a **2D Heat Diffusion/Laplace Solver**, emphasizing kernel optimization, global/shared memory usage, and performance benchmarking against CPU implementations.

### 3. [Distributed Computing with MPI and Sockets](https://github.com/YourUsername/Distributed-Computing-C)
* **Focus:** Inter-process communication and distributed algorithms across multiple nodes.
* **Highlights:** Implements `MPI` for scalable distributed applications, showcasing data distribution, collective operations, and `halo exchange` for domain decomposition (e.g., 2D Laplace Solver). Also includes foundational `socket programming` for client-server communication and potentially large-scale data transfer.

### 4. [High-Performance Computing (HPC) Cluster Deployments & Analysis](https://github.com/YourUsername/HPC-Cluster-Implementations)
* **Focus:** Practical experience with real-world supercomputing environments and performance analysis.
* **Highlights:** Detailed reports on probing and mapping compute nodes on the SINES NUST HPC cluster, along with extensive performance analysis (execution time, speedup graphs) of a **2D Laplace Solver** across sequential, OpenMP, and MPI paradigms. Addresses challenges in HPC environments and provides insights into optimal parallelization strategies.

### 5. [Parallel Machine Learning Algorithms](https://github.com/YourUsername/Parallel-ML-Algorithms-C)
* **Focus:** Applying parallel computing techniques to optimize core machine learning algorithms.
* **Highlights:** Implementations of **Linear Regression** and **Logistic Regression**, parallelized using `pthreads`. Focuses on optimizing gradient descent and cost function calculations for large datasets, demonstrating speedup and efficiency.

---

## Core C/C++ Fundamentals:

My projects are built on a strong foundation of C/C++ programming principles. While implicitly demonstrated throughout, key areas include:
* **Memory Management:** Expertise in `new`/`delete` and raw pointers for efficient resource handling.
* **Data Structures:** Implementing and optimizing various data structures for parallel access.
* **Build Systems:** Proficient in using `Makefiles` and `CMake` for robust project compilation and dependency management.

Feel free to explore each repository for detailed `README.md` files, source code, and performance analysis.

---
**Usman Ayub**
**usmanayub@ieee.org**
