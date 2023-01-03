# **Predict Cancer Mortality Rates in US Counties**

The provided dataset comprises data collected from multiple counties in the US. The regression task for this assessment is to predict cancer mortality rates in "unseen" US counties, given some training data. The training data ('Training_data.csv') comprises various features/predictors related to socio-economic characteristics, amongst other types of information for specific counties in the country. The corresponding target variables for the training set are provided in a separate CSV file ('Training_data_targets.csv').

**Tasks**

The list of successfully completed tasks involved:

- Computing correlations with the target variable
- Computing feature importance from chosen models
- Computing outliers
- Evaluating best performing model
- Evaluating results using R2 and RMSE metrics
- Hyperparameter tuning using grid search cross-validation
- KMeans clustering
- Linear regression (ordinary least squares, lasso and ridge)
- Logistic regression
- Observations of usual values
- Overfitting check using cross-validation
- Plotting histograms of all features
- Plotting results of all models
- Pre-processing using a machine learning pipeline (involves computing more meaningful features, removing unwanted features, imputing outliers and missing values, scaling data, feature selection, and principle component analysis)
- Random forest regression
- Sequential Neural Networks

**Data Dictionary**

The list of predictors/features available in this data set are described below:

- avgAnnCount: Mean number of reported cases of cancer diagnosed annually
- avgDeathsPerYear: Mean number of reported mortalities due to cancer
- incidenceRate: Mean per capita (100,000) cancer diagoses
- medianIncome: Median income per county 
- popEst2015: Population of county 
- povertyPercent: Percent of populace in poverty 
- studyPerCap: Per capita number of cancer-related clinical trials per county ($\alpha$)
- MedianAge: Median age of county residents 
- MedianAgeMale: Median age of male county residents 
- MedianAgeFemale: Median age of female county residents 
- AvgHouseholdSize: Mean household size of county 
- PercentMarried: Percent of county residents who are married 
- PctNoHS18_24: Percent of county residents ages 18-24 highest education attained: less than high
- school 
- PctHS18_24: Percent of county residents ages 18-24 highest education attained: high school diploma 
- PctSomeCol18_24: Percent of county residents ages 18-24 highest education attained: some college 
- PctBachDeg18_24: Percent of county residents ages 18-24 highest education attained: bachelor's
- degree 
- PctHS25_Over: Percent of county residents ages 25 and over highest education attained: high school
- diploma 
- PctBachDeg25_Over: Percent of county residents ages 25 and over highest education attained:
- bachelor's degree 
- PctEmployed16_Over: Percent of county residents ages 16 and over employed 
- PctUnemployed16_Over: Percent of county residents ages 16 and over unemployed 
- PctPrivateCoverage: Percent of county residents with private health coverage 
- PctPrivateCoverageAlone: Percent of county residents with private health coverage alone (no public
- assistance) 
- PctEmpPrivCoverage: Percent of county residents with employee-provided private health coverage 
- PctPublicCoverage: Percent of county residents with government-provided health coverage 
- PctPubliceCoverageAlone: Percent of county residents with government-provided health coverage -lone 
- PctWhite: Percent of county residents who identify as White 
- PctBlack: Percent of county residents who identify as Black 
- PctAsian: Percent of county residents who identify as Asian 
- PctOtherRace: Percent of county residents who identify in a category which is not White, Black, or
- Asian 
- PctMarriedHouseholds: Percent of married households 
- BirthRate: Number of live births relative to number of women in county 
