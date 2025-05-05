Diabetes Dataset Sampling and Bootstrap Analysis

Introduction

This analysis uses the `diabetes.csv` dataset (768 patients) to:

1. Compare Glucose statistics in a random sample vs population.
2. Compare the 98th percentile BMI in the sample vs population.
3. Use bootstrap sampling to estimate BloodPressure statistics and compare them to the population.


(a): Glucose Comparison

A random sample of 25 observations was drawn. Mean and maximum Glucose were slightly lower in the sample than in the population:
Interpretation: 
The sample underestimates both mean and maximum Glucose, reflecting normal variability in small samples.


(b): 98th Percentile BMI Comparison

The 98th percentile BMI was lower in the sample than in the population:
Interpretation: 
The sample underestimates the extreme BMI value since small samples are less likely to capture population extremes.


(c): Bootstrap Sampling for BloodPressure

500 bootstrap samples (n=150) were used to estimate BloodPressure statistics:
Interpretation:
Bootstrap averages for mean, standard deviation, and 98th percentile closely match the population statistics, showing bootstrap sampling provides reliable estimates.


Conclusion

Small samples may underestimate population statistics, especially extremes.  
Bootstrap sampling provides accurate estimates of population parameters.  
Visual comparisons confirm findings.




