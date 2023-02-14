# Parallel-Matrix-Multiplication
Implementing parallel matrix multiplication in C++ using multithreading.

The program first creates two 200x200 matrices, A and B, and sequentially multiplies them using a regular matrix multiplication algorithm. Then, it creates two new 200x200 matrices, C and D, and multiplies them using a parallel matrix multiplication algorithm that divides the work across multiple threads. The performance of both sequential and parallel matrix multiplication is measured using the high_resolution_clock provided by the chrono library. The program uses joinable threads to synchronize thread execution and avoid data races. The goal of this project is to demonstrate the benefits of parallel computing for matrix multiplication, especially for large matrices.
