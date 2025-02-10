# Off-by-one error in vector iteration

This repository demonstrates a common off-by-one error in C++ when iterating over a `std::vector`. The `bug.cpp` file contains code that attempts to access an element beyond the vector's bounds, leading to undefined behavior (often a segmentation fault).

The `bugSolution.cpp` file provides a corrected version with the proper loop condition to avoid the error.  This highlights the importance of careful indexing when working with containers.