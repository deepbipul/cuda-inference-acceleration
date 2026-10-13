# High-Performance CUDA Inference Acceleration Lab

Welcome to my core repository dedicated to breaking the memory and compute bottlenecks of modern generative AI infrastructure. 

Backed by **20 years of experience designing ultra-low latency, highly concurrent C++ networking data planes (4G/5G core)**, this laboratory tracks my architectural transition into hardware-accelerated machine learning infrastructure. Every component here is written with a strict focus on cache locality, zero-copy memory access, explicit hardware saturation, and production-grade safety.

## 🚀 Technical Focus Areas
* **Modern C++20 Systems Engineering:** Leveraging concepts, ranges, views, and coroutines for predictable, zero-overhead execution paths.
* **Custom CUDA Kernel Engineering:** Designing manual shared memory tiling, cooperative groups, and fused micro-kernels targeting NVIDIA Tensor Cores.
* **Memory & I/O Optimization:** Implementing PagedAttention-inspired virtual block allocation layouts to eliminate VRAM fragmentation.
* **Quantization-Aware Inference:** Writing performance-critical GPU micro-kernels for on-the-fly INT4/FP8 parsing to maximize memory bus throughput.

## 🛠️ The 16-Week Roadmap
- [ ] **Phase 1: GPU Hardware Saturation & RAW CUDA** (Matrix tiling, Shared Memory optimizations, CUTLASS)
- [ ] **Phase 2: Deconstructing the Inference Bottleneck** (Custom token-filtering, Paged Memory layers in C++20)
- [ ] **Phase 3: The Capstone Engine** (A lightweight, single-file C++20/CUDA LLM inference execution pipeline)

## 🏗️ Build Requirements
* **Compiler:** GCC 11+ / Clang 13+ (Strict C++20 compliance)
* **Toolkit:** NVIDIA CUDA Toolkit 12.x+
* **Build System:** Modern CMake (3.22+)
* **Testing:** GoogleTest Framework
