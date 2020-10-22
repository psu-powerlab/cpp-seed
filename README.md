# cpp-seed
This will be a starting point for c++ projects which will auto include gtest and boost libs

The requirements are:

* CMake 3.11 or better; 3.14+ highly recommended.
* A C++11 compatible compiler
* Boost Libraries
* Git

```bash
sudo apt update && sudo apt install gcc g++ git cmake libboost-all-dev
```

To configure (must be done first):

```bash
cmake -S . -B build
```

To build:

```bash
cmake --build build
```

To test:

```bash
./build/tests/all-tests
```

To run:

```bash
./build/src/app
```
