# Diabetic patient analysis 

### Project overview

This data analysis project aims at predicting diabetic patients from Pima Indians dataset retrived from Kaggle Dataset library. Theis self made project aims at preparing myself to learn more about KNN algorithm and the understand about different models used for prediction of a purticular subject. The project is basically a self learning strategy to dive deeper from the basics of cleaning a dataset and also educating myself about how algorithms are chosen and implemented. Also later on the project i have mentioned the accuracy, scalability of the model created. The documentation of the project is explained in detailed through each step.

### Data sources

The dataset used is Pima indians diabetes dataset reteived from Kaggle Library. The csv file named 'diabetes4.csv' contains detailed information of different patients. 
[download dataset here](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database/download?datasetVersionNumber=1)

### Tools 

- MS Excel - Basic data overview and cleaning
- Jupiter notebook - Coding and creating prediction models

### Choice of algorithm

The algorithm which has been opted for the project is the K-Nearest Neighbors (KNN). 

K-Nearest Neighbors (KNN) algorithm is a method used for classification and predicting tasks. KNN algorithm perform the tasks by comparing the object with the closest neighbors for predicting which category it belongs.

Among other machine learning algorithm, the reason to choose K-Nearest Neighbors (KNN) algorithm over other algorithms is :
1. Because of personal experience as a beginner to data analysis, that there is more opportunity to learn and improve my knowledge in machine learning.
2. KNN covers the aspects of data analysis in terms of data preprocessing, selecting features and understanding how to handle the nonlinear relationships in the data.
3. KNN is a non-parametric algorithm it serves with a freedom of selection of different types of datasets without being concerned of the characteristics of the data.
4. KNN doesn't rely on broad statistical metrics, it is generally resistant to outliers. Certain algorithms, like linear models, can be significantly impacted by outliers, but because K-Nearest Neighbors (KNN) algorithm bases its decisions on the closest neighbors, it is less vulnerable to the impact of outliers.

### Choice of dataset

The dataset chosen for working with K-Nearest Neighbors (KNN) algorithm is Pima Indians Diabetes Dataset taken from Kaggle dataset library. Original source of the dataset is The National Institute of Diabetes and Digestive and Kidney Diseases. The dataset contains the specific data about the patients diagnosed. Particularly, all patients at this facility are Pima Indian women who are at least 21 years old. The dataset includes one target variable and other predictor variables. The predictor variable consists of BMI, Insulin Level, Age etc. As the collection includes data on 768 people the results are frequently stronger and more trustworthy.

### Methodology of cleaning dataset

1. The source of the data is from very well-known research study conducted by the National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK) in the year1980s. So, the credibility of the source makes the dataset trustworthy to provide realistic outcomes.
2. The quantity of data: The dataset contains diagnostic results of 768 people. This provides a good number to do the analysis. The larger the size of the sample, more reliable the results would be.
3. Data specific variables: The dataset contains several variables that are relevant to diabetes research, including blood pressure, body mass index (BMI), glucose levels, and other specific characteristics. Multiple variables in the dataset gives the ability to investigate relationships and create predictive models.
4. Outliers and Missing values: Nonrealistic values or errors in the data can significantly affect the analysis. The dataset is with minimal missing values. This is crucial for analysis and for the machine learning algorithm because these missing as missing data can influence the training models. These minimal errors are further treated in the cleaning process.
5. Cleaning the dataset: The list of columns to clean are: 'Glucose', 'BloodPressure', 'SkinThickness', 'Insulin', 'BMI', and 'DiabetesPedigreeFunction'. To replaces zeros in every column, the program search for NaN which is the missing value. Then, the mean of each column is calculated, and the missing values (NaN) are replaced with the mean of each column, using the mean() and replace() functions from pandas library. 




























