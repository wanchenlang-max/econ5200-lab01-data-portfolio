# econ5200-lab01-data-portfolio
# Data Quality Profiling — Big Mac Index

## Objective

In this lab, I learned how to identify and correct data quality problems using the Big Mac Index dataset.

## Methodology

- I identified and corrected a PPP calculation error caused by swapping the numerator and denominator.
- I compared the average Big Mac price for countries with complete data against the average for all available countries in each period.
- I calculated the difference between the two averages to examine the effect of excluding countries with incomplete data.
- I wrote a function called `profile_dataframe()` to count units and periods, identify the data structure, check for a balanced panel, and calculate missing-data percentages for each column.

## Key Findings

I found that the complete-panel average Big Mac price was $0.081 higher on average than the all-available average, with an average relative difference of 2.1%.

The complete-panel average was higher in 33 out of 45 periods.

I also learned that reversing the numerator and denominator changes the PPP calculation. My `profile_dataframe()` function helped me examine data structure and missing values.

This lab taught me that checking calculations and missing data is important before analyzing economic data.
