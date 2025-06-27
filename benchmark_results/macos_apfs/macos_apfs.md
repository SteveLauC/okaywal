# Without pre-allocation (macOS, APFS)

## commit-256B
| Label       | avg     | min     | max     | stddev  | out%   |
|-------------|---------|---------|---------|---------|--------|
| okaywal-01t | 4.075ms | 1.226ms | 11.93ms | 903.0us | 0.026% |
| okaywal-02t | 7.904ms | 5.565ms | 19.92ms | 859.5us | 0.014% |
| okaywal-04t | 7.789ms | 2.796ms | 12.72ms | 852.6us | 0.037% |
| okaywal-08t | 7.884ms | 2.880ms | 20.88ms | 927.5us | 0.027% |
| okaywal-16t | 7.979ms | 2.883ms | 18.15ms | 949.2us | 0.018% |

## commit-1KB
| Label       | avg     | min     | max     | stddev  | out%   |
|-------------|---------|---------|---------|---------|--------|
| okaywal-01t | 3.875ms | 1.435ms | 7.645ms | 487.2us | 0.012% |
| okaywal-02t | 7.957ms | 4.512ms | 17.01ms | 877.1us | 0.020% |
| okaywal-04t | 7.965ms | 3.003ms | 19.80ms | 1.398ms | 0.016% |
| okaywal-08t | 7.949ms | 3.013ms | 20.89ms | 1.202ms | 0.018% |
| okaywal-16t | 8.400ms | 2.957ms | 20.83ms | 1.717ms | 0.022% |

## commit-4KB
| Label       | avg     | min     | max     | stddev  | out%   |
|-------------|---------|---------|---------|---------|--------|
| okaywal-01t | 3.954ms | 2.851ms | 9.238ms | 718.6us | 0.016% |
| okaywal-02t | 7.956ms | 4.980ms | 15.92ms | 1.059ms | 0.024% |
| okaywal-04t | 7.824ms | 3.049ms | 17.77ms | 1.219ms | 0.052% |
| okaywal-08t | 9.017ms | 3.929ms | 26.01ms | 2.406ms | 0.016% |
| okaywal-16t | 10.82ms | 2.613ms | 27.88ms | 2.965ms | 0.014% |

## commit-1MB
| Label       | avg     | min     | max     | stddev  | out%   |
|-------------|---------|---------|---------|---------|--------|
| okaywal-01t | 8.409ms | 5.432ms | 14.15ms | 1.442ms | 0.013% |
| okaywal-02t | 13.97ms | 8.939ms | 19.89ms | 2.388ms | 0.000% |
| okaywal-04t | 25.55ms | 8.951ms | 276.1ms | 30.67ms | 0.027% |
| okaywal-08t | 48.57ms | 7.261ms | 1.087s  | 92.71ms | 0.020% |
| okaywal-16t | 99.49ms | 7.000ms | 1.669s  | 185.6ms | 0.027% |

# With pre-allocation (macOS, APFS)

## commit-256B
| Label       | avg     | min     | max     | stddev  | out%   |
|-------------|---------|---------|---------|---------|--------|
| okaywal-01t | 3.991ms | 2.825ms | 14.99ms | 686.8us | 0.010% |
| okaywal-02t | 7.952ms | 5.963ms | 15.47ms | 623.1us | 0.017% |
| okaywal-04t | 7.846ms | 2.884ms | 17.91ms | 834.2us | 0.029% |
| okaywal-08t | 7.905ms | 2.936ms | 19.14ms | 1.001ms | 0.029% |
| okaywal-16t | 8.013ms | 2.810ms | 19.13ms | 1.056ms | 0.030% |


## commit-1KB
| Label       | avg     | min     | max     | stddev  | out%   |
|-------------|---------|---------|---------|---------|--------|
| okaywal-01t | 3.950ms | 2.856ms | 7.513ms | 381.4us | 0.008% |
| okaywal-02t | 7.866ms | 3.950ms | 12.00ms | 560.3us | 0.020% |
| okaywal-04t | 7.838ms | 2.987ms | 18.93ms | 948.0us | 0.030% |
| okaywal-08t | 7.919ms | 2.966ms | 18.05ms | 1.055ms | 0.037% |
| okaywal-16t | 8.090ms | 2.869ms | 17.06ms | 1.299ms | 0.036% |

## commit-4KB
| Label       | avg     | min     | max     | stddev  | out%   |
|-------------|---------|---------|---------|---------|--------|
| okaywal-01t | 3.930ms | 2.861ms | 7.635ms | 461.7us | 0.008% |
| okaywal-02t | 7.934ms | 4.518ms | 11.97ms | 644.1us | 0.028% |
| okaywal-04t | 7.999ms | 3.985ms | 19.49ms | 1.489ms | 0.022% |
| okaywal-08t | 8.917ms | 3.091ms | 24.08ms | 2.289ms | 0.019% |
| okaywal-16t | 10.18ms | 3.024ms | 32.06ms | 3.085ms | 0.013% |

## commit-1MB
| Label       | avg     | min     | max     | stddev  | out%   |
|-------------|---------|---------|---------|---------|--------|
| okaywal-01t | 8.448ms | 5.990ms | 13.93ms | 1.278ms | 0.013% |
| okaywal-02t | 12.84ms | 7.910ms | 26.17ms | 2.255ms | 0.013% |
| okaywal-04t | 22.73ms | 7.343ms | 178.7ms | 22.48ms | 0.027% |
| okaywal-08t | 45.42ms | 5.000ms | 588.6ms | 72.29ms | 0.028% |
| okaywal-16t | 88.64ms | 7.071ms | 1.693s  | 169.4ms | 0.028% |
