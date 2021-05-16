# Diagnostics-Cateogrical_Covariates

## Goal:
The goal of this analysis is to run diagnostics on multiple datasets with categorical covariates to find out which methods are suitable for generating linear regression models with multiple categorical covariates. 

## Files and Directories
- `Diagnostic.Rmd`: R Markdown file used for running diagnostics.
- `Diagnostic.html`: R Markdown file above rendered into a html file.
- `Project Report.rmd`: R Markdown file of the project report.
- `Project-Report.html`: R Markdown file above rendered into a html file.

## Requirements:
```
R
MASS
tidyverse
faraway
```

## Data:

Data below are collected from the `faraway` package and the `MASS` package.

- `birthwt` - The data describes risk factors associated with low infant birth weight. The data set contains 189 observations and 10 attributes. ‘bwt’ attribute is the response variable and the rest attributes are the predictors.
- `hsb` - The data was collected to determine which factors are related to the choice of career that the students pursued in high school. The data set contains 200 observations and 11 attributes. Social science score, ‘socst’, is the response variable and rest attributes are the predictors. 
- `denim` - The data describes how much material is wasted from five different manufacturers. The data set contains 95 observations and 2 attributes. ‘waste’ variable is the response variable and the ‘supplier’ is the factor predictor.
- `butterfat` - The data shows the average butterfat content of milk from five cow breeds with two different age levels. The data set contains 100 observations and 3 attributes. ‘Butterfat’ is the response variable and the other two variables are predictors.
