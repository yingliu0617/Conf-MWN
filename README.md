# Conf-MWN

**Table 1:** The performance metrics of Conf-MWN with different temperature parameter T on CIFAR-10 datasets (symmetric 20%).

| T | 0.01 | 0.1 | 0.5 | 1 | 5 | 10 |
|------------|----------|----------|----------|----------|----------|----------|
| Ineff.  | 2.044     | 1.967    | 2.009    | 1.926     | 2.492    | 2.304     |
| Cov.(%)  | 98.91     | 98.95    | 98.98    | 98.78     | 99.09     | 98.89    |
| Acc.(%)   | 90.34     | 90.16     | 90.27     | 90.37     | 90.20     | 89.69     |


**Table 2:** Experimental results on conditional coverage with CE/Ours on CIFAR-10 datasets.

| Noise Type       | Symmetric-20%       | Symmetric-40%       |
|------------------|---------------------|---------------------|
| **SSCV (HPS)**   |   0.008 / 0.005  |  0.021 / 0.004 |    
| **CovGap (HPS)** |   0.003 / 0.004   |  0.004 /  0.005 |     
| **SSCV (APS)**   |   0.022 / 0.013   |  0018 / 0.014  | 
| **CovGap (APS)** |   0.005 / 0.005  |  0.005 / 0.004  |  

**Table 3:** The performance metrics of Conf-MWN with different number of calibration data on CIFAR-10N datasets (worst).

| n_cal |5000 | 3000 | 1000 | 500 |
|------------|----------|----------|----------|----------|
| Ineff.  | 3.245     | 3.331    | 3.700    | 3.160     |
| Cov.(%)  | 98.78     | 98.82    | 99.02    | 98.70     | 
