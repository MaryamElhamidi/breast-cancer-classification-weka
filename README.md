# Breast Cancer Classification: J48 vs Multilayer Perceptron (Weka)

This project evaluates and compares the performance of two machine learning classifiers, J48 Decision Tree and Multilayer Perceptron (MLP), for breast cancer prediction using the UCI Breast Cancer dataset.

## Objective
To determine whether there is a statistically significant difference in classification accuracy between a rule-based model (J48) and a neural network model (MLP) under identical experimental conditions.

## Tools & Technologies
- Weka (Experimenter & Explorer)
- Excel (statistical analysis & visualization)
- UCI Machine Learning Repository dataset

## Methodology
- 30 randomized trials per model
- 66% training / 34% testing split
- Accuracy recorded for each run
- Paired-sample t-test used for statistical comparison
- Visual analysis using boxplots and histograms

## Results
The J48 Decision Tree achieved a higher mean accuracy than the Multilayer Perceptron across 30 trials.
A paired-sample t-test confirmed the difference was statistically significant (p < 0.05).

### Statistical Analysis and Visualizations

**Paired t-test results**
![Paired t-test](/ttest.png)
- This figure illustrates a two-tailed t-test where the observed test statistic falls within the rejection region beyond the critical values, indicating a statistically significant difference between the J48 and MLP model accuracies.

**Accuracy distribution (Boxplot)**
![Boxplot](/boxplot.png)
- The boxplot shows that J48 achieved a higher median accuracy with a tighter spread across 30 trials, indicating more consistent and reliable performance than the more variable MLP model.

**Accuracy difference distribution (Histogram)**
![Histogram](/histogram.png)
- The histogram demonstrates that accuracy differences were mostly positive and approximately normally distributed, confirming that J48 consistently outperformed MLP and that the paired t-test assumptions were satisfied.

## Key Takeaways
- Decision Trees performed better on this categorical dataset
- Neural networks showed higher variance without extensive tuning
- Highlights importance of model selection based on data characteristics

## Files
- `FinalProject_Report_MaryamE.docx`: Full academic report with methodology, analysis, and references
- `WekaAnalysis.xlsx`: Accuracy results, statistical tests, and visualizations
