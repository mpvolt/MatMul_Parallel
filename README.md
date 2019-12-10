MatMul_Parallel

this is an attempt to optimally parallelize the matrix multiplication operation in c++ from serial code using OpenMP.

referenced: https://www.geeksforgeeks.org/c-program-multiply-two-matrices/ for the serial code

Instructions to compile: g++ matmul.cpp -fopenmp

Instructions to run: evn OMP_NUM_THREADS=4 ./a.out (You can switch 4 to whatever number of threads you want)
