# Fast Parallel Matrix-Inversion in CUDA

## Introduction
This parallel Gauss-Jordan inversion algorithm serves as a proof-of-concept for an efficient parallel Gauss-Jordan algorithm for matrix inversion using CUDA [1]. While conventional Gauss-Jordan matrix inversion typically operates in O(n^3) time complexity, the use of extensive parallelization in GPUs allows for a reduced runtime complexity of O(n).

## Running the POC
To run the POC, simply upload the python notebook and the mat.txt file to Google Colaboratory and change the runtime type to T4 GPU and run all cells.

## Results
![image](https://github.com/Sami-Hussein/Fast-Parallel-Matrix-Inversion-in-CUDA/assets/62296680/ea0a2f68-e1e0-49e1-ba1c-df51e93a39ac)

## References
[1] G. Sharma, A. Agarwala, and B. Bhattacharya, "A fast parallel Gauss Jordan algorithm for matrix inversion using CUDA," Computers & Structures, vol. 128, pp. 31-37, 2013, doi: 10.1016/j.compstruc.2013.06.015.
