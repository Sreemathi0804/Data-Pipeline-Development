# Data-Pipeline-Development

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SREEMATHI.R

*INTERN ID*: CT06DL163

*DOMAIN*: DATA SCIENCE

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTOSH

 Data Pipeline Development – ETL Process on Wine Quality Data

 I Have selected the Wine Quality Dataset, which contains physicochemical test results and quality ratings of red and white wine samples. The objective of this task was to automate the ETL (Extract, Transform, Load) process using Python tools like pandas and scikit-learn, making the dataset ready for further analysis or machine learning.

Project Overview

This project demonstrates the ETL pipeline in a structured way:

Extract – Reading and loading raw data.

Transform – Cleaning, preprocessing, and modifying data.

Load – Saving the cleaned and transformed data for downstream tasks.

Extract Phase

In the extraction phase, I used the pandas library to load the Wine Quality Dataset from a CSV file. The dataset includes various features such as fixed acidity, volatile acidity, citric acid, residual sugar, pH, alcohol content, and a target variable: quality (scored from 0 to 10). This phase involved:

Reading the dataset using pd.read_csv().

Performing an initial check for missing values, data types, and basic statistics using .info() and .describe() methods.

Transform Phase

The transformation phase is the core of the pipeline. Here, I cleaned and preprocessed the data to ensure its suitability for further use. The key steps include:

Handling Missing Values: Although the dataset was relatively clean, I implemented checks to handle missing or null values using fillna() or dropna(), depending on the context.

Feature Scaling: I used StandardScaler from scikit-learn to standardize numerical columns. This ensures that features like alcohol content and pH are on the same scale for consistency in modeling.

Outlier Detection: Applied basic statistical techniques like IQR (Interquartile Range) to identify and handle outliers in certain columns.

Data Encoding: Although the Wine dataset mostly contains numerical data, I prepared code snippets for encoding categorical features using LabelEncoder or OneHotEncoder for future adaptability.

Feature Selection: Checked feature correlation to reduce redundancy, enhance performance, and simplify the model structure for later stages.

Load Phase

After transformation, the cleaned and processed dataset was saved as a new CSV file using to_csv(). This phase makes the dataset readily available for use in machine learning models or further data analysis.

Tools and Technologies Used

Language: Python

Libraries: pandas, numpy, scikit-learn

Outcome

The final deliverable for this task Jupyter Notebook that fully automates the ETL process. This pipeline can be reused or adapted for other structured datasets in the future. It showcases a clean and modular approach to handling data, which is an essential skill in data science and analytics.



