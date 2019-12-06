MatMul_Parallel

this is an attempt to optimally parallelize the matrix multiplication operation in c++ from serial code using OpenMP.

referenced: https://www.geeksforgeeks.org/c-program-multiply-two-matrices/ for the serial code

To compile the code use g++ matmul.cpp -fopenmp
To run the code use env OMP_NUM_THREADS=4 ./a.out
(replace 4 with the desired number of threads)
