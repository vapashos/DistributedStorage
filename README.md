This project is a C++ implementation of a distributed storage system. It is designed to provide a scalable and reliable solution for storing and retrieving data across multiple nodes in a network.
It is going to be built step by step, starting with a simple key-value store and gradually adding more advanced features such as replication, sharding, and fault tolerance.

CMAKE REQUIREMENTS
* CMake version 3.24 or higher
* C++20 compatible compiler



Configure


Build Instructions
1. Clone the repository:
2. ```bash
   git clone
3. Navigate to the project directory:
4. ```bash
    cd DistributedStorage
5. Create a build directory for your platform and navigate into it:
6. ```bash
    mkdir build/macos-clang-debug
7. Build the project using your preferred build system (e.g., Make, Ninja):
8. ```bash
    cmake -S . -B build/macos-clang-debug \
    -DCMAKE_CXX_COMPILER=clang++ \
    -DCMAKE_BUILD_TYPE=Debug \
    -G Ninja