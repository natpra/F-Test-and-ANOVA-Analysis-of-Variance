# f-Test and ANOVA Analysis of Variance

## Overview

This repository contains code, resources for conducting Analysis of Variance (ANOVA), and mathematical explanations performed in Jupyter Notebook. ANOVA is a statistical method used to compare means across multiple groups or conditions.

## Contents

- `mathematical_anova.ipynb`: Jupyter Notebook containing code for manually calculating ANOVA using mathematical formulas.
- `package_anova.ipynb`: Jupyter Notebook demonstrating how to use Python packages like Pingouin for ANOVA analysis.
- `data.csv`: Sample dataset used for ANOVA analysis.
- `README.md`: This file.

## Understanding ANOVA

### One-Way ANOVA

One-way ANOVA is used to compare means across two or more independent groups. It tests the null hypothesis (H0) that there are no differences between the means of the groups. If the p-value obtained from the ANOVA test is less than a chosen significance level (usually 0.05), we reject the null hypothesis and conclude that there are significant differences between at least two group means.

### Two-Way ANOVA

Two-way ANOVA is an extension of one-way ANOVA that allows for the simultaneous comparison of the effects of two categorical independent variables (factors) on a continuous dependent variable. It assesses the main effects of each factor as well as the interaction effect between them. The null hypothesis for each factor and interaction effect is tested using F-tests.

## Interpreting Results

After conducting ANOVA analysis, it's important to interpret the results properly:

- **F-value**: The F-value is a ratio of between-group variability to within-group variability. Higher F-values indicate stronger evidence against the null hypothesis.
- **p-value**: The p-value represents the probability of observing the test statistic (F-value) or more extreme values if the null hypothesis is true. A low p-value suggests that the observed differences are unlikely to be due to random chance.
- **Rejecting H0**: If the p-value is less than the chosen significance level (e.g., 0.05), we reject the null hypothesis and conclude that there are significant differences between groups.

## How to Use

1. Clone this repository to your local machine.
2. Open the Jupyter Notebooks (`mathematical_anova.ipynb` and `package_anova.ipynb`) using Jupyter Notebook or JupyterLab.
3. Follow the instructions in the notebooks to run the code and analyze the ANOVA results.
4. Refer to the README.md file in each notebook for more detailed explanations.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize this README.md file to include any additional information or sections relevant to your project.
