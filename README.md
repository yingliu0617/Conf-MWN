# Conf-MWN

<img src="https://github.com/yingliu0617/Conf-MWN/raw/main/cifar10n_m.png" width="55%">

<img src="https://github.com/yingliu0617/Conf-MWN/raw/main/test_example.png" width="60%">


**Table 1:** Performance comparison of Method A and B.

| T | 0.01 | 0.1 | 0.5 | 1 | 5 | 10 |
|------------|----------|----------|----------|----------|----------|----------|
| Ineff.  | 2.044     | 1.967    | 2.009    | 1.926     | 2.492    | 2.304     |
| Cov.(%)  | 98.91     | 98.95    | 98.98    | 98.78     | 99.09     | 98.89    |
| Acc.(%)   | 90.34     | 90.16     | 90.27     | 90.37     | 90.20     | 89.69     |


**Table 2:** Performance comparison of Method A and B.

| Noise Type       | Symmetric-20%       | Symmetric-40%       |
|------------------|---------------------|---------------------|
| **SSCV (HPS)**   | 2.044 / 1    | `1.876`   |    
| **CovGap (HPS)** | 98.91     | `99.12`   |     
| **SSCV (APS)**   | 90.34     | `91.25`   | 
| **CovGap (APS)** | 90.34     | `91.25`   |  


**Table 3:** Performance comparison of Method A and B.

| n_cal |5000 | 3000 | 1000 | 500 |
|------------|----------|----------|----------|----------|
| Ineff.  | 3.245     | 3.331    | 3.700    | 3.160     |
| Cov.(%)  | 98.78     | 98.82    | 99.02    | 98.70     | 
