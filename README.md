# VanitySearch-binarys

## Overview

These binaries are built from [VanitySearch](https://github.com/JeanLucPons/VanitySearch) by Jean-Luc Pons.

This project leverages NVIDIA CUDA and OpenCL for high-performance GPU computing. It is compatible with a wide range of NVIDIA GPUs, from GTX 10-series to RTX 50-series, and is designed to be built and run on Linux systems.

## Dependencies

Before running the project, ensure the following dependencies are installed:

```bash
sudo apt update
sudo apt install g++-12 nvidia-cuda-toolkit build-essential libssl-dev ocl-icd-opencl-dev
```

- **g++-12**: C++ compiler for building the project.
- **nvidia-cuda-toolkit**: Provides CUDA libraries and tools for GPU acceleration.
- **build-essential**: Essential compilation tools (gcc, make, etc.).
- **libssl-dev**: SSL library development files (if your project uses secure connections).
- **ocl-icd-opencl-dev**: OpenCL development files for cross-vendor GPU support.

## Supported NVIDIA GPU Compute Capabilities

For a full and up-to-date list of NVIDIA GPU compute capabilities, see the official documentation:
https://developer.nvidia.com/cuda-gpus

| GPU Series      | Compute Capability |
|-----------------|-------------------|
| GTX 10-series   | 6.1               |
| RTX 20-series   | 7.5               |
| RTX 30-series   | 8.6               |
| RTX 40-series   | 8.9               |
| RTX 50-series   | 12.0              |

## Usage

Instructions for running the project will depend on your implementation. Please refer to the documentation or source files for details.

## License

Specify your license here.
