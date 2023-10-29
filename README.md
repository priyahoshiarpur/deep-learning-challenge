Project Title: Deep Learning for Charity Funding Prediction
Project Overview:
•
I embarked on a data-driven journey to create a predictive model for Alphabet Soup, a charitable organization that has historically supported over 34,000 organizations.
Data Preprocessing:
1.
Data Collection: The project began with the collection of data from the 'charity_data.csv' file, which was loaded into a Pandas DataFrame.
2.
Target and Features: I identified the target variable(s) for the model, which represent funding approval. The relevant features for model building were also determined.
3.
Data Cleaning: I dropped the 'EIN' and 'NAME' columns, as they were not contributing to the prediction task.
4.
Data Exploration: A comprehensive analysis of the dataset was conducted, including an assessment of the unique values in each column.
5.
Binning Strategy: For columns with more than ten unique values, I developed a strategy to group rare categorical variables into a single 'Other' category, optimizing data quality.
6.
Categorical Encoding: The categorical variables were encoded using the pd.get_dummies() method, preparing the data for model training.
7.
Data Split: I split the preprocessed data into two arrays: one for features (X) and the other for the target variable (y). The dataset was further divided into training and testing subsets using the train_test_split function.
8.
Feature Scaling: To ensure consistency and improve model performance, I scaled the features using the StandardScaler.
