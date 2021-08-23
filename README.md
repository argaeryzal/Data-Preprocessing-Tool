# Data Preprocessing Tool
Preprocessing is one of the important stages for data in the mining process. The data used in the mining process is not always in an ideal condition for processing. Sometimes in the data there are various problems that can interfere with the results of the mining process itself, such as missing values, redundant data, outliers, or data formats that do not match the system. Therefore, to overcome these problems, a preprocessing stage is needed. Preprocessing is one of the stages of eliminating problems that can interfere with the results of data processing.
## Importing the Libraries
- NumPy
- Matlplotlib
- Pandas
## Importing the Dataset
- Read the dataset using pandas
- x = independent variable
- y = dependent variable
## Taking Care of Missing Data
- Using sklearn.impute to import SimpleImputer module
- Find the NaN values using 'mean' strategy
- Fit and Transform it
## Encoding the Independent Variable
- Using sklearn.compose to import ColoumnTransfer
- Using sklearn.preprocessing to import OneHotEncoder
- Making method of ColoumTransfer
- Fit transform the x variable
## Encoding the Dependent Variable
- Using sklearn.preprocessing to import LabelEncoder
- Making method of LabelEncoder
- Fit transfrom the y variable
## Spliting the dataset into the Training set and Test set
- Using sklearn.model_selection to import train_test_split
- Making method of train_test_split to x and y, then use 20% of the dataset to test
- Random state 1x
## Feature Scaling
- Using sklearn.preprocessing to import StandardScaler
- Making method of StandardScaler
- Fit transofrm x_train
- Transform x_test
