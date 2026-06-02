# Income Survey Simulator

## Project Overview

This project simulates a government income survey using statistical sampling techniques. Instead of surveying every individual in the population, random samples are selected to estimate the average income. The project demonstrates concepts such as sampling, estimation, standard error, and confidence intervals using Python and NumPy.

---

## Features

- Generate a synthetic population using a log-normal distribution
- Draw multiple random samples
- Estimate average population income
- Calculate standard error
- Compute a 95% confidence interval
- Provide statistical interpretation of the results

---

## Technologies Used

- Python
- NumPy
- Matplotlib (for visualization)

---

## Sample Output

```text
===== INCOME SURVEY REPORT =====

Actual Population Mean : 124.09

Estimated Mean Income : 124.74

Standard Error : 1.79

95% Confidence Interval :
(121.23, 128.26)
```

---

## Interpretation

1. The estimated average income is very close to the actual population mean, indicating that the sampling method provides an accurate estimate.

2. The estimation error is small, suggesting that the selected samples represent the population reasonably well.

3. The 95% confidence interval indicates that we are 95% confident that the true average income lies within the calculated range.

4. Since the actual population mean falls within the confidence interval, the survey estimate can be considered statistically reliable.

5. The relatively low standard error shows that the sample means have low variability, resulting in a stable and consistent estimate of the population income.

---

## Statistical Concepts Demonstrated

- Population vs Sample
- Random Sampling
- Sample Mean
- Standard Error
- Confidence Intervals
- Statistical Inference
- Log-Normal Distribution

---

## Conclusion

The survey successfully estimated the average income of the population using a relatively small sample. The estimated mean closely matches the actual population mean, and the confidence interval contains the true value, demonstrating the effectiveness of statistical sampling techniques for population analysis.
