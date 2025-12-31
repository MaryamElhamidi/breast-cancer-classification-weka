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

**Accuracy distribution (Boxplot)**
![Boxplot](/boxplot.png)

**Accuracy difference distribution (Histogram)**
![Histogram](/histogram.png)


## Key Takeaways
- Decision Trees performed better on this categorical dataset
- Neural networks showed higher variance without extensive tuning
- Highlights importance of model selection based on data characteristics

## Files
- `FinalProject_Report_MaryamE.docx`: Full academic report with methodology, analysis, and references
- `WekaAnalysis.xlsx`: Accuracy results, statistical tests, and visualizations
