# Without pre-allocation (Linux, BTRFS)

## commit-256B
| Label       | avg     | min     | max     | stddev  | out%   |
|-------------|---------|---------|---------|---------|--------|
| okaywal-01t | 1.356ms | 1.095ms | 5.459ms | 209.0us | 0.006% |
| okaywal-02t | 2.815ms | 2.392ms | 6.202ms | 324.8us | 0.016% |
| okaywal-04t | 2.898ms | 1.410ms | 12.36ms | 553.3us | 0.011% |
| okaywal-08t | 2.711ms | 1.127ms | 6.626ms | 449.5us | 0.019% |
| okaywal-16t | 2.679ms | 2.096ms | 8.025ms | 500.7us | 0.014% |

## commit-1KB
| Label       | avg     | min     | max     | stddev  | out%   |
|-------------|---------|---------|---------|---------|--------|
| okaywal-01t | 1.443ms | 1.124ms | 7.326ms | 491.6us | 0.012% |
| okaywal-02t | 2.855ms | 2.241ms | 5.383ms | 286.9us | 0.020% |
| okaywal-04t | 2.732ms | 1.564ms | 7.062ms | 423.2us | 0.008% |
| okaywal-08t | 2.742ms | 1.113ms | 5.238ms | 430.7us | 0.021% |
| okaywal-16t | 2.838ms | 1.305ms | 9.468ms | 593.5us | 0.020% |

## commit-4KB

| Label       | avg     | min     | max     | stddev  | out%   |
|-------------|---------|---------|---------|---------|--------|
| okaywal-01t | 1.460ms | 1.119ms | 4.706ms | 349.8us | 0.024% |
| okaywal-02t | 2.863ms | 2.384ms | 5.486ms | 293.0us | 0.012% |
| okaywal-04t | 2.843ms | 1.286ms | 5.512ms | 340.2us | 0.018% |
| okaywal-08t | 3.053ms | 1.282ms | 16.37ms | 1.356ms | 0.008% |
| okaywal-16t | 3.654ms | 1.142ms | 9.220ms | 963.9us | 0.009% |


## commit-1MB
| Label       | avg     | min     | max     | stddev  | out%   |
|-------------|---------|---------|---------|---------|--------|
| okaywal-01t | 2.259ms | 1.922ms | 4.717ms | 356.3us | 0.013% |
| okaywal-02t | 2.914ms | 1.735ms | 6.735ms | 969.3us | 0.013% |
| okaywal-04t | 4.696ms | 2.117ms | 26.88ms | 3.449ms | 0.027% |
| okaywal-08t | 8.072ms | 1.751ms | 40.69ms | 5.804ms | 0.027% |
| okaywal-16t | 15.28ms | 1.838ms | 115.1ms | 15.02ms | 0.017% |


# With pre-allocation (Linux, BTRFS)

## commit-256B

| Label       | avg     | min     | max     | stddev  | out%   |
|-------------|---------|---------|---------|---------|--------|
| okaywal-01t | 1.171ms | 808.4us | 5.212ms | 242.2us | 0.002% |
| okaywal-02t | 2.839ms | 2.240ms | 8.436ms | 343.8us | 0.008% |
| okaywal-04t | 2.818ms | 1.279ms | 19.48ms | 899.2us | 0.011% |
| okaywal-08t | 2.736ms | 1.402ms | 13.39ms | 594.3us | 0.009% |
| okaywal-16t | 2.780ms | 1.120ms | 9.157ms | 556.1us | 0.011% |

## commit-1KB

| Label       | avg     | min     | max     | stddev  | out%   |
|-------------|---------|---------|---------|---------|--------|
| okaywal-01t | 1.441ms | 1.120ms | 6.549ms | 499.2us | 0.016% |
| okaywal-02t | 2.520ms | 1.122ms | 5.650ms | 394.4us | 0.024% |
| okaywal-04t | 2.817ms | 1.418ms | 7.444ms | 334.6us | 0.008% |
| okaywal-08t | 2.673ms | 1.120ms | 9.199ms | 537.7us | 0.009% |
| okaywal-16t | 2.897ms | 1.269ms | 7.120ms | 440.3us | 0.019% |



## commit-4KB

| Label       | avg     | min     | max     | stddev  | out%   |
|-------------|---------|---------|---------|---------|--------|
| okaywal-01t | 1.394ms | 1.120ms | 2.889ms | 164.5us | 0.016% |
| okaywal-02t | 2.874ms | 2.378ms | 5.763ms | 347.1us | 0.020% |
| okaywal-04t | 2.866ms | 1.277ms | 6.661ms | 455.4us | 0.012% |
| okaywal-08t | 3.110ms | 1.264ms | 14.10ms | 1.346ms | 0.016% |
| okaywal-16t | 3.715ms | 1.390ms | 8.275ms | 988.4us | 0.015% |

## commit-1MB

| Label       | avg     | min     | max     | stddev  | out%   |
|-------------|---------|---------|---------|---------|--------|
| okaywal-01t | 2.310ms | 1.925ms | 4.156ms | 370.2us | 0.027% |
| okaywal-02t | 2.872ms | 1.843ms | 5.484ms | 796.4us | 0.020% |
| okaywal-04t | 4.049ms | 1.749ms | 25.00ms | 2.376ms | 0.013% |
| okaywal-08t | 7.529ms | 1.812ms | 45.80ms | 5.597ms | 0.018% |
| okaywal-16t | 13.95ms | 1.808ms | 135.1ms | 13.56ms | 0.018% |

