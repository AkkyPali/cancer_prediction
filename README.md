# cancer_prediction
These data were aggregated from a number of sources including the American Community Survey (census.gov), clinicaltrials.gov, and cancer.gov. 

Implementation:
Build a multivariate Ordinary Least Squares regression model to predict "TARGET_deathRate". Then build Lasso & Ridge regularised models and compare models based on MSEs

Convert this into a classification problem, and apply KNN to predict response classes instead of targetDeathRate values. 

Data Dictionary: 

- MedianAge: Median age of county residents
- medianIncome: Median income per county
- studyPerCap: Per capita number of cancer-related clinical trials per county
- AvgHouseholdSize: Mean household size of county
- BirthRate: Number of live births relative to number of women in county
- avgDeathsPerYear: Mean number of reported mortalities due to cancer
- incidenceRate: Mean per capita (100,000) cancer diagoses
- PctPublicCoverage: Percent of county residents with government-provided health coverage 
- PctPrivateCoverage: Percent of county residents with private health coverage
- povertyPercent: Percent of populace in poverty
- PercentMarried: Percent of county residents who are married
- region: where in the US (categorical variable)
- TARGET_deathRate: Dependent variable. Mean per capita (100,000) cancer mortalities
