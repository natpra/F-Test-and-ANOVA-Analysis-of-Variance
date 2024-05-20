# f-Test and ANOVA Analysis of Variance

## Overview

This repository contains code, resources for conducting Analysis of Variance (ANOVA), and mathematical explanations performed in Jupyter Notebook. ANOVA is a statistical method used to compare means across multiple groups or conditions.

## Contents

- `1wayAnova.ipynb`: Jupyter Notebook containing code for manually calculating One Way ANOVA using mathematical formulas.
- `2wayAnova.ipynb`: Jupyter Notebook containing code for manually calculating Two Way ANOVA using mathematical formulas.
- `data.csv`: Sample dataset used for ANOVA analysis.
- `README.md`: This file.

## Understanding ANOVA

### One-Way ANOVA

One-way ANOVA is used to compare means across two or more independent groups. It tests the null hypothesis (H0) that there are no differences between the means of the groups. If the p-value obtained from the ANOVA test is less than a chosen significance level (usually 0.05), we reject the null hypothesis and conclude that there are significant differences between at least two group means.

### Two-Way ANOVA

Two-way ANOVA is an extension of one-way ANOVA that allows for the simultaneous comparison of the effects of two categorical independent variables (factors) on a continuous dependent variable. It assesses the main effects of each factor as well as the interaction effect between them. The null hypothesis for each factor and interaction effect is tested using F-tests.

## Interpreting Results

After conducting ANOVA analysis, it's important to interpret the results properly:

- **F-Value**: The F-value is a ratio of between-group variability to within-group variability. Higher F-values indicate stronger evidence against the null hypothesis.
- **F-Critical**: The F critical value is the value from the F-distribution table corresponding to the chosen significance level and degrees of freedom. It is used to determine whether the observed F-value is statistically significant.
- **Rejecting H0**: If the calculated F-value exceeds the critical F-value for a given significance level, we reject the null hypothesis and conclude that there are significant differences between groups.

## Understanding $H_0$

The null hypothesis ($H_0$) in ANOVA states that there are no differences between the means of the groups or conditions being compared. In other words, it assumes that any observed differences are due to random variability or chance. By conducting ANOVA, we test the null hypothesis to determine whether there is sufficient evidence to reject it in favor of an alternative hypothesis. If the calculated F-value is large enough to exceed the critical F-value, we reject H0 and conclude that there are significant differences between groups. Otherwise, we fail to reject H0, indicating that any observed differences are likely due to random chance.

## How to Use

1. Clone this repository to your local machine.
2. Open the Jupyter Notebooks (`mathematical_anova.ipynb` and `package_anova.ipynb`) using Jupyter Notebook or JupyterLab.
3. Follow the instructions in the notebooks to run the code and analyze the ANOVA results.
4. Refer to the README.md file in each notebook for more detailed explanations.

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

