# Conf-MWN

**Figure 1:** Inefficiency results of Conf-MWN by varying the number of meta data on CIFAR-10N dataset ("Worst" noise).
‹img src="https://github.com/yingliu0617/Conf-MWN/raw/main/meta_data_number.png" width="50%">

**Table 1:** Results of Conf-MWN by varying temperature T on CIFAR-10 dataset with 20% symmetric noise.

| T | 0.01 | 0.1 | 0.5 | 1 | 5 | 10 |
|------------|----------|----------|----------|----------|----------|----------|
| Ineff.   | 2.04     | 1.97     | 2.01     | 1.98     | 2.49     | 2.30     |
| Cov.(%)   | 98.91     | 98.95     | 98.98     | 98.82     | 99.09    | 98.89    |
| Acc.(%)   | 90.34     | 90.16     | 90.27     | 90.18     | 90.20     | 89.69    |

**Table 2:** Comparison between CE and Conf-MWN (CE/Conf-MWN) in terms of SSCV and CovGap on CIFAR-10 dataset with symmetric noise.

| Noise Type | Symmetric-20% | Symmetric-40% | 
|------------|----------|----------|
| SSCV(HPS)   | 0.008 / 0.005     | 0.021 / 0.004     | 
| CovGap(HPS)   | 0.003 / 0.004     | 0.004 / 0.005     | 
| SSCV(APS)   | 0.022 / 0.013     | 0.018 / 0.014     | 
| CovGap(APS)  | 0.005 / 0.005     | 0.005 / 0.004     | 

**Table 3:** Inefficiency and marginal coverage results of Conf-MWN by varying the number of calibration data on CIFAR-10N dataset ("Worst" noise).

| n_cal | 5000 | 3000 | 1000 | 500 | 
|------------|----------|----------|----------|----------|
| Ineff.  | 3.53     | 3.33     | 3.70     | 3.16     | 
| Cov. (%)   | 98.95     | 98.82     | 99.02     | 98.70     | 

**Table 4:** Examples of prediction sets obtained by CE and Conf-MWN (true label is shown in red). Models are trained on CIFAR-10 dataset with 40% symmetric noise.
‹img src="https://github.com/yingliu0617/Conf-MWN/raw/main/example.png" width="75%">
