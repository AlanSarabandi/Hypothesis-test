# Inferential Statistics: Analyzing Gender Differences in Climbing Route Grades

## Project Overview
This project analyzes whether females have an average climbing route grade lower than males, using a dataset of 1,000 climbers. It uses a variety of inferential statistical methods in R, including both traditional and non-traditional approaches.

The analysis follows the steps:
- Stating the null and alternative hypothesis
- Calculating point estimates and standard errors
- Performing hypothesis testing using both traditional t-test and non-traditional bootstrapping and permutation methods
- Visualizing results with boxplots, histograms, and distributions

We provide detailed commentary on the hypothesis testing process, supported by visual insights.

## Key Components
- **Hypothesis Testing**: Comparison of the average climbing grades of males and females, testing the null hypothesis at a 0.05 significance level.
![Unknown](https://github.com/user-attachments/assets/0a217387-519e-4c24-bfee-1a98086fac4e)
As you see the p value is far from our distribution so we reject the null hypothesis.
- **Bootstrap Method**: Creating confidence intervals using resampling to assess the reliability of our estimates.
![Unknown](https://github.com/user-attachments/assets/624d44d6-31d5-49f3-8d5c-bca1125e377c)
We see that 0 is not contained in this confidence interval as a plausible value of the population parameter. This matches with our hypothesis test results of rejecting the null hypothesis. Since zero is a plausible value of the population parameter, we do not have evidence that female have an average grade equal or greater to the male.
We are 95% confident the true grades mean for female and male is between -5.748401 to -3.654263.
- **Permutation Test**: A non-parametric method to observe if the difference in means is statistically significant.
- **Visualizations**: Boxplots, histograms, and distribution plots to visually assess data distributions and results.
  

## How to Run the Project
1. Clone the repository.
2. Open the R markdown file `inferential_statistics.Rmd` in RStudio.
3. Ensure all required libraries (tidyverse, infer, readr) are installed.
4. Knit the markdown file to generate HTML or PDF output.

## Conclusion
Based on our hypothesis tests and confidence intervals, we find statistically significant evidence suggesting that females have a lower average climbing route grade than males.
