In this repository, I'm going to engage in the deliberate practice of building Machine Learning models for supervised learning right from getting data, preprocessing it, model selection and tuning. 
Datasets from Kaggle and various other sources will be used. 
The curriculum for the practice is as described below. Each of the tasks will be practiced on multiple data sets (5-10) until a comfortable level of confidence is reached on that task before moving on to the next one. 

### CURRICULUM (SUPERVISED LEARNING)
*GET THE DATA*
- **Task 1**: Reading in the training and test sets (.csv format)
- Read datasets from formats other than .csv
  - json
  - sqlite
  - .txt
  - sklearn datasets
  - postgresql
  - webpages

*EXPLORE THE DATA*
- **Task 1**: Create copy of the training set for data exploration
- **Task 1**: Identify target attribute(s)
- **Task 1**: Display descriptive statistics and information associated with attributes
- For each attribute(column) and sample(row) find precentage of missing values
- For each attribute check if there are any outliers
- For each attribute, check the type of distribution (gaussian/normal, uniform, logrithmic, etc.)
- Visualize the data
- Correlations between attributes(themselves) and target attribute
- Documenting any learning

*DATA PREPARATION*
- Keep original dataset and work on copies of data
- Note: Write functions for all data transformations
- Outlier detection and remedy. If outliers are removed, it should be done only in the training set
- While imputing missing data with mean, median, regression, combine the attribute data from train and test sets, or drop columns (or rows). Note: If rows are dropped, it should be done only in the training set
- Scale the features
- Standardize or normalize features
- Discretizing continuous features
- Creating dummies for categorical attributes

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
