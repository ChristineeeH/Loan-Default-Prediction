# Loan-Default-Prediction
We use the loan dataset given by the Alibaba Tianchi website to construct several statistic models to make default predictions.
All the codes can run with Python 3.11.3,matplotlib 3.7.1, numpy 1.24.3, pandas 2.1.3, scikit-learn  1.2.2, seaborn 0.13.0, plotnine 0.12.3.
The dataset is downloaded from https://tianchi.aliyun.com/dataset/140861, in which the train.csv file is utilized.
# Instruction
The analysis process consists of three main parts, which are data preprocessing, data visualization, and model construction.
# Data Preprocessing
Use `DataPreprocessing` to make data preprocessing, including data loading, columns selection, variables mappings and so on. 
All the functions we use in data filtering are encapsulated in it, containing possible error capturing and processing. 
# Visualization Analysis
The visualization analysis is based on the diagrams, which can reflect the relationships between input variables and the response variable. 
# Model Construction
## Preliminary Models
After descriptive statistics, the models we utilize in this report, the logistic regression model, naive Bayes model, KNN model, and Decision Tree model, are constructed. 
## Models Optimization
Only using the original models without any parameter setting is inadequate. 
Standard scaling, hyperparameters tuning and ensembling(bagging) are used in the model optimization section. Users can accomplish the whole process just by using the functions in class `ModelOptimization`.
# Outcomes
All the outcomes of different models are shown in corresponding figures to be analyzed more intuitively.
