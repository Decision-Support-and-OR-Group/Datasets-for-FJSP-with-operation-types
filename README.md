# Datasets-for-FJSP-with-operation-types

The dataset is licensed under Creative Commons Attribution 4.0, which permits reuse, sharing, and modification as long as the original creators are credited.

The data/ directory contains randomly generated test data sets used for algorithm evaluation.

The src/ directory contains random datasets generator, which can be downloaded, compiled and executed, to generate not only test data but also training and validation data used in the experiments.

# Compile and run instructions.
 
### Prerequisites

- Git (for cloning the repository)
- CMake (version 3.20 or higher)
- A C++ compiler (e.g., GCC /c++20 was tested/, Clang, or MSVC)

### Open a terminal or command prompt and run:

```bash
git clone https://github.com/tsliwins/Datasets-for-FJSP-with-operation-types.git
cd Datasets-for-FJSP-with-operation-types/src
mkdir build
cd build
cmake ..
make
```

### Run the generator with
```bash
./fjsp_gen
```

Warning: as `./fjsp_gen` generates several million data files (1mln for each problem size), it will require 40GB of free disk space or possibly more to generate all the data.




   
