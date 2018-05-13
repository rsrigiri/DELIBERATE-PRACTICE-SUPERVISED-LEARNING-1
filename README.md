In this repository, I'm going to engage in the deliberate practice of building Machine Learning models for supervised learning right from getting data, preprocessing it, model selection and tuning. 
Datasets from Kaggle and various other sources will be used. 
The curriculum for the practice is as described below. Each of the tasks will be practiced on multiple data sets (5-10) until a comfortable level of confidence is reached on that task before moving on to the next one. 

### CURRICULUM (SUPERVISED LEARNING)
*GET THE DATA*
- Reading in the training and test sets (.csv format)
- Read datasets from formats other than .csv
  - json
  - sqlite
  - .txt
  - sklearn datasets
  - postgresql
  - webpages

*EXPLORE THE DATA* (This step is optional. But, it helps in making sense of the overall data and identifying valuable relationships)
- Create copy of the training set for data exploration
- Display shape of the dataset (df.shape)
- Display the information associated with the dataset (df.info)
- Identify target attribute(s)
- List the variables that have null values.
- Study/Explore the variables individually starting with the target variable.
  - If variable belongs to NULLS list, display the percentage of data missing.
  - Check if variable is categorical or continuous?
  - Check if variable is nominal or ordinal?
  - If categorical, display unique values and counts (df.unique, df.value_counts)
  - If continuous, display the descriptive statistics (df.describe)
  - If continuous, check and display the type of distribution of the variable(gaussian/normal, uniform, logarithmic, etc.)
  - Check for any relationships between feature and target, check correlation values.
  - Try different visualizations and see if that might generate new insights (try being creative here)
  - Check for correlations of attributes among one another. 
  - Document any learning. This might include noting if the variable needs,
     - addressing NULLS, what imputation technique could be most effective, fast?
     - Feature transformation (assigning numerical values to categorical variables, creating dummy variables, etc)
     - Feature engineering (combining features, applying functions to variables, discretization of variables, etc)
     - addressing Outliers.
     - Scaling/Standardization/Normalization

*DATA PREPARATION*
- Keep original dataset and work on copies of data
- Display shape of the dataset (df.shape)
- Display the information associated with the dataset (df.info)
- Identify target attribute(s)
- **Note**: Write functions for all data transformations keeping in mind that the test set will eventually need these transformations. 
- Address NULL values. For each variable (column) and sample(row) find precentage of missing values. While imputing missing data with mean, median, regression, combine the attribute data from train and test sets, or drop columns (or rows). Note: If rows are dropped, it should be done only in the training set.
- Outlier detection and remedy. If outliers are removed, it should be done only in the training set.
- Scale/Standardize/Normalize the features (for continuous variables).
- Make feature transformations, create dummies for categorical variables, assign numerical values, etc
- Perform feature engineering as documented in the data exploration step.

*SPLITTING THE DATASET*	
- Split the training data into training, development and test sets


### DATASETS
- *TITANIC: MACHINE LEARNING FROM DISASTER - KAGGLE COMPETITION*
- *HOUSE PRICES: ADVANCED REGRESSION TECHNIQUES - KAGGLE COMPETITION*
- *PREDICT FUTURE SALES - KAGGLE COMPETITION*
- *FIFA WORLD CUP - KAGGLE DATASET*
- *CREDIT CARD FRAUD DETECTION - KAGGLE DATASET*
- *NEW YORK STOCK EXCHANGE - KAGGLE DATASET*
- *KICKSTARTER PROJECTS - KAGGLE DATASET*
