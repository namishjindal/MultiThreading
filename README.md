# MultiThreading  Assignment

This assignment demonstrates matrix multiplication using multithreading in Python.We need to multiply 100 random matrices of size 1000x1000 with a constant matrix of the same size using multithreading.

## Outputs
### Number of Cores:2
### Number of Threads vs. Total Time

| Num of Threads | Time Taken (seconds) |
|----------------|----------------------|
| 1              | 13.4497              |
| 2              | 13.5572              |
| 3              | 11.3754              |
| 4              | 8.0278               |
| 5              | 7.1778               |
| 6              | 8.1566               |
| 7              | 7.1336               |
| 8              | 8.2848               |
| 9              | 8.2278               |
| 10             | 7.2650               |
| 11             | 8.1210               |
| 12             | 6.9800               |
| 13             | 8.1446               |
| 14             | 8.6022               |
| 15             | 7.0155               |
| 16             | 8.1161               |


### Graph

![Number of Threads vs. Total Time](https://github.com/namishjindal/MultiThreading/blob/main/Plot.png)


The graph illustrates how the total time taken for matrix multiplication decreases as the number of threads increases due to parallelism.

### CPU Usage

![CPU usgae](https://github.com/namishjindal/MultiThreading/blob/main/CPU_Utilization.png)

The CPU usage graph shows the utilization during the execution of the multithreading program, demonstrating the effectiveness of multithreading in leveraging CPU resources.
