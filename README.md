# Multithreading-matrix-multiplication
## Overview

This Python script benchmarks the performance of matrix multiplication using multi-threading. It generates 100 random matrices of size 1000x1000 and multiplies each of them with a constant matrix of the same size. The performance is measured for different numbers of threads ranging from 1 to 8.

## Prerequisites

- Python 3.x
- NumPy
- Matplotlib
- Pandas
- psutil

The script will generate the following outputs:
    - Table showing the time taken for matrix multiplication with different numbers of threads.
    - Graph plotting the matrix multiplication time versus the number of threads.
    - CPU usages (if available).
## Result Graph
<img width="494" alt="image" src="https://github.com/Drishti-17/MultiThreading/assets/91721425/0bef8bc7-7420-435e-a866-2d63f2c8513f">


## Results Interpretation

- **Time Taken (Sec):** Indicates the time taken for matrix multiplication in seconds. Lower values indicate better performance.
- **Number of Threads:** The number of threads used for matrix multiplication. Higher values may improve performance up to a certain point, depending on the system's capabilities.
- **CPU Usage:** Percentage of CPU being used.

## Result DataFrame

| Threads | Time Taken (Sec) | CPU Usage (%) |
|---------|------------------|---------------|
| 1       | 500              | 20            |
| 2       | 275              | 35            |
| 3       | 200              | 45            |
| 4       | 150              | 55            |
| 5       | 250              | 60            |
| 6       | 300              | 65            |
| 7       | 350              | 70            |
| 8       | 400              | 75            |

## Result Table

<img width="189" alt="image" src="https://github.com/Drishti-17/MultiThreading/assets/91721425/15598374-29aa-4d65-a555-577624dbb5f8">


Submitted By: Drishti Agarwal


Roll Number: 102117158


Batch: 3CS6
