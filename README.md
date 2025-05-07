Diabetes Dataset Sampling and Bootstrap Analysis

Findings 

(a): Glucose Comparison
The random sample of 25 patients slightly underestimates both the mean and maximum Glucose compared to the entire population. This difference is expected as a result of sampling variability, especially with small samples. Small samples may miss extreme values like the maximum, leading to underestimates compared to population values.


(b): 98th Percentile BMI Comparison
The sample’s 98th percentile BMI is lower than the population’s 98th percentile BMI. This happens because small random samples are less likely to include extreme high BMI values that define the upper percentiles. As a result, the sample underestimates the population’s extreme BMI threshold.


(c): Bootstrap Sampling for BloodPressure
The bootstrap averages (from 500 samples of 150 observations each) closely match the population statistics. The mean and standard deviation estimates are nearly identical to the true values, and even the 98th percentile is very close. This demonstrates the strength of bootstrap sampling in the sense that with enough samples and a reasonable size, it can reliably estimate population parameters, even for extreme percentiles. 


Conclusion
In all, small samples may underestimate population statistics, especially extremes.  However, bootstrap sampling provides accurate estimates of population parameters. The visual comparisons that were shown confirm these findings.




