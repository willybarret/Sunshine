# Dev Container

This directory contains the configuration for the development container. The dev container provides a consistent development environment across different machines and operating systems.

## Building the Project

To build the project inside the dev container, you can use the following commands:


```bash
bash scripts/linux_build.sh --skip-cuda --step=cmake
bash scripts/linux_build.sh --skip-cuda --step=build
```

The first command will run the CMake configuration step, and the second command will build the project. The `--skip-cuda` flag is used to skip CUDA-related steps if you do not have CUDA installed.