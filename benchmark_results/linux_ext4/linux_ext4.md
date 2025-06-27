# Without pre-alloc (Linux, Ext4)

## commit-256B
| Label       | avg     | min     | max     | stddev  | out%   |
|-------------|---------|---------|---------|---------|--------|
| okaywal-01t | 1.361ms | 1.141ms | 53.74ms | 2.617ms | 0.006% |
| okaywal-02t | 2.514ms | 2.315ms | 49.70ms | 2.240ms | 0.005% |
| okaywal-04t | 2.487ms | 2.325ms | 49.65ms | 2.095ms | 0.002% |
| okaywal-08t | 2.639ms | 1.173ms | 55.32ms | 3.041ms | 0.005% |
| okaywal-16t | 2.958ms | 1.214ms | 54.09ms | 3.981ms | 0.013% |

## commit-1KB
| Label       | avg     | min     | max     | stddev  | out%   |
|-------------|---------|---------|---------|---------|--------|
| okaywal-01t | 1.388ms | 1.146ms | 47.32ms | 2.911ms | 0.004% |
| okaywal-02t | 2.591ms | 2.327ms | 48.68ms | 2.882ms | 0.004% |
| okaywal-04t | 2.837ms | 1.243ms | 50.76ms | 3.882ms | 0.010% |
| okaywal-08t | 3.104ms | 1.335ms | 49.81ms | 4.332ms | 0.017% |
| okaywal-16t | 3.532ms | 1.197ms | 51.33ms | 5.131ms | 0.022% |


## commit-4KB
| Label       | avg     | min     | max     | stddev  | out%   |
|-------------|---------|---------|---------|---------|--------|
| okaywal-01t | 1.648ms | 1.259ms | 47.31ms | 4.100ms | 0.008% |
| okaywal-02t | 3.306ms | 1.319ms | 49.87ms | 5.392ms | 0.020% |
| okaywal-04t | 3.682ms | 1.293ms | 49.97ms | 5.569ms | 0.030% |
| okaywal-08t | 5.843ms | 1.510ms | 61.75ms | 7.133ms | 0.028% |
| okaywal-16t | 8.022ms | 1.470ms | 62.68ms | 8.951ms | 0.027% |

## commit-1MB
| Label       | avg     | min     | max     | stddev  | out%   |
|-------------|---------|---------|---------|---------|--------|
| okaywal-01t | 27.51ms | 26.53ms | 48.40ms | 3.470ms | 0.027% |
| okaywal-02t | 53.36ms | 26.83ms | 103.7ms | 20.75ms | 0.000% |
| okaywal-04t | 100.6ms | 26.87ms | 196.7ms | 44.64ms | 0.000% |
| okaywal-08t | 192.9ms | 26.62ms | 273.9ms | 82.63ms | 0.000% |
| okaywal-16t | 415.0ms | 26.95ms | 2.917s  | 311.6ms | 0.013% |


# With pre-alloc (Linux, Ext4)

## commit-256B
| Label       | avg     | min     | max     | stddev  | out%   |
|-------------|---------|---------|---------|---------|--------|
| okaywal-01t | 1.288ms | 1.155ms | 50.89ms | 2.221ms | 0.002% |
| okaywal-02t | 2.603ms | 2.300ms | 58.89ms | 3.070ms | 0.006% |
| okaywal-04t | 2.600ms | 1.176ms | 71.07ms | 3.321ms | 0.004% |
| okaywal-08t | 2.737ms | 1.196ms | 52.87ms | 3.441ms | 0.009% |
| okaywal-16t | 2.804ms | 1.197ms | 56.49ms | 3.234ms | 0.009% |

## commit-1KB
| Label       | avg     | min     | max     | stddev  | out%   |
|-------------|---------|---------|---------|---------|--------|
| okaywal-01t | 1.388ms | 1.157ms | 47.10ms | 2.897ms | 0.004% |
| okaywal-02t | 2.686ms | 1.202ms | 70.92ms | 4.324ms | 0.004% |
| okaywal-04t | 2.834ms | 1.176ms | 50.71ms | 3.855ms | 0.010% |
| okaywal-08t | 3.104ms | 1.205ms | 50.71ms | 4.365ms | 0.017% |
| okaywal-16t | 3.481ms | 1.219ms | 51.37ms | 4.564ms | 0.015% |

## commit-4KB
| Label       | avg     | min     | max     | stddev  | out%   |
|-------------|---------|---------|---------|---------|--------|
| okaywal-01t | 1.650ms | 1.258ms | 47.28ms | 4.097ms | 0.008% |
| okaywal-02t | 3.301ms | 1.275ms | 49.54ms | 5.399ms | 0.020% |
| okaywal-04t | 3.659ms | 1.270ms | 50.09ms | 5.459ms | 0.030% |
| okaywal-08t | 4.198ms | 1.294ms | 50.74ms | 4.934ms | 0.016% |
| okaywal-16t | 6.484ms | 1.748ms | 46.54ms | 5.948ms | 0.044% |

## commit-1MB
| Label       | avg     | min     | max     | stddev  | out%   |
|-------------|---------|---------|---------|---------|--------|
| okaywal-01t | 27.66ms | 26.38ms | 49.85ms | 4.263ms | 0.040% |
| okaywal-02t | 53.47ms | 26.67ms | 103.3ms | 19.12ms | 0.000% |
| okaywal-04t | 99.39ms | 26.72ms | 179.3ms | 49.46ms | 0.000% |
| okaywal-08t | 200.9ms | 26.78ms | 625.8ms | 87.40ms | 0.010% |
| okaywal-16t | 386.3ms | 27.67ms | 789.2ms | 123.0ms | 0.005% |