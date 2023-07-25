# 7. Statistical Measures and Hypothesis Testing

**Statistical Measures in Exploratory Data Analysis (EDA):**

1. **Measures of Central Tendency:**
   * Mean: The arithmetic average of a set of numerical values. It represents the central value around which the data points tend to cluster.
   * Median: The middle value in a sorted set of data. It is less sensitive to extreme outliers and provides a robust measure of central tendency.
   * Mode: The most frequently occurring value in a dataset. It helps identify the most common data point.
2. **Measures of Dispersion:**
   * Standard Deviation: Measures the average amount by which each data point deviates from the mean. A higher standard deviation indicates greater variability in the data.
   * Variance: The square of the standard deviation, providing a measure of the spread or dispersion of the data.
   * Range: The difference between the maximum and minimum values in the dataset, representing the extent of variability.
   * Interquartile Range (IQR): The range between the first quartile (Q1) and the third quartile (Q3), providing a measure of variability that is less affected by extreme values.
3. **Percentiles and Quartiles:**
   * Percentiles: Divide the data into 100 equal parts. For example, the 25th percentile (Q1) represents the value below which 25% of the data falls.
   * Quartiles: Divide the data into four equal parts, denoted as Q1 (25th percentile), Q2 (50th percentile, which is the median), and Q3 (75th percentile).
4. **Correlation:**
   * Pearson's Correlation Coefficient: Measures the strength and direction of a linear relationship between two numerical variables. It ranges from -1 to 1, where -1 indicates a perfect negative correlation, 1 indicates a perfect positive correlation, and 0 indicates no correlation.
5. **Covariance:**
   * Covariance: Measures the degree to which two numerical variables vary together. A positive covariance indicates that both variables increase or decrease together, while a negative covariance indicates an inverse relationship.

**Hypothesis Testing in Exploratory Data Analysis (EDA):**

Hypothesis testing is a critical aspect of EDA that allows data analysts to make inferences about the population based on sample data. The process involves setting up null and alternative hypotheses and using statistical tests to determine the validity of the hypotheses. Some common hypothesis tests in EDA include:

1. **t-test:**
   * Independent t-test: Used to compare the means of two independent groups to determine if there is a significant difference between them.
   * Paired t-test: Used to compare the means of two related groups (paired data) to check for a significant difference.
2. **ANOVA (Analysis of Variance):**
   * One-way ANOVA: Used to compare means across multiple groups (more than two) to check for significant differences.
   * Two-way ANOVA: Used to analyze the influence of two categorical variables on a continuous dependent variable.
3. **Chi-square test:**
   * Chi-square test of independence: Used to assess the association between two categorical variables in a contingency table.
4. **Correlation test:**
   * Pearson correlation test: Used to determine if there is a significant linear relationship between two numerical variables.
   * Spearman rank correlation test: Used for non-linear relationships between variables or when data is not normally distributed.
5. **Regression analysis:**
   * Linear regression: Used to model the relationship between a dependent variable and one or more independent variables.
   * Multiple regression: Extends linear regression to model relationships with multiple independent variables.

By employing these statistical measures and hypothesis tests in EDA, data analysts can gain valuable insights into the data, validate assumptions, and make informed decisions. EDA helps identify outliers, patterns, and trends, providing a solid foundation for subsequent analyses, model building, and drawing meaningful conclusions from the data. These statistical techniques enable data professionals to uncover the underlying structure and characteristics of the data, leading to data-driven insights and actionable knowledge.
