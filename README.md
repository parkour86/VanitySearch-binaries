# VanitySearch Binary


## Overview

This binary was built from [parkour86/VanitySearch](https://github.com/parkour86/VanitySearch), a fork of the original VanitySearch by Jean-Luc Pons [JeanLucPons/VanitySearch](https://github.com/JeanLucPons/VanitySearch).

This project leverages NVIDIA CUDA and OpenCL for high-performance GPU computing. The provided binary is compatible with all NVIDIA GPUs listed below (from GTX 10-series to RTX 50-series, including H100/H200), and is designed to be built and run on Linux systems.

**Note:** This binary was compiled with **CUDA 12.8** for maximum compatibility with the latest NVIDIA GPUs.

## Dependencies

Before running the project, ensure the following dependencies are installed:

```bash
sudo apt update
sudo apt install g++-9 nvidia-cuda-toolkit build-essential libssl-dev ocl-icd-opencl-dev
```

- **g++-9**: C++ compiler for building the project.
- **nvidia-cuda-toolkit**: Provides CUDA libraries and tools for GPU acceleration.
- **build-essential**: Essential compilation tools (gcc, make, etc.).
- **libssl-dev**: SSL library development files (if your project uses secure connections).
- **ocl-icd-opencl-dev**: OpenCL development files for cross-vendor GPU support.

## Supported NVIDIA GPU Compute Capabilities

This binary is compatible with all the following NVIDIA GPU compute capabilities:

| Compute Capability | NVIDIA Series     |
|--------------------|-------------------|
| 6.0, 6.1           | GTX 10-series     |
| 7.0                | RTX 20-series     |
| 8.0, 8.6           | RTX 30-series     |
| 8.9                | RTX 40-series     |
| 9.0                | H100, H200        |
| 12.0               | RTX 50-series     |

For a full and up-to-date list of NVIDIA GPU compute capabilities, see the official documentation:
https://developer.nvidia.com/cuda-gpus

## Usage

To run the binary, simply execute it on a Linux system with a supported NVIDIA GPU and the required dependencies installed. No separate binaries are needed for different GPU series; this single binary supports all listed compute capabilities.

For advanced usage or configuration, refer to the original [VanitySearch documentation](https://github.com/JeanLucPons/VanitySearch).

## License

Specify your license here.
