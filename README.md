## Description
This project is a C++ implementation of a distributed storage system. It is designed to provide a scalable and reliable solution for storing and retrieving data across multiple nodes in a network.
It is going to be built step by step, starting with a simple key-value store and gradually adding more advanced features.
## CMAKE REQUIREMENTS
* CMake version 3.24 or higher
* C++20 compatible compiler

## Build Instructions
1. Clone the repository:
    ```bash
    git clone https://github.com/vapashos/DistributedStorage.git
    ```
2. Navigate to the project directory:
    ```bash
    cd DistributedStorage
    ```
3. Configure the project using your preferred build system (e.g., Make, Ninja):
    ```bash
    cmake -S . -B build/macos-clang-debug \
    -DCMAKE_CXX_COMPILER=clang++ \
    -DCMAKE_BUILD_TYPE=Debug \
    -G Ninja
    ```
4. Build the project:
    ```bash
    cmake --build build/macos-clang-debug
    ```