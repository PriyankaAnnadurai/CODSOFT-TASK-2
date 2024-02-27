# CODSOFT-TASK-2
# CREDIT CARD FRAUD DETECTION
## Import Libraries:

Import necessary libraries such as numpy, pandas, matplotlib, seaborn, and gridspec.
## Read Data:

Read the dataset from the CSV file "fraudTest.csv" into a Pandas DataFrame named data.
## Data Exploration:

Display the first and last few rows of the dataset using data.head() and data.tail() respectively.
Print the shape of the data and its descriptive statistics using data.shape and data.describe().
## Correlation Matrix Visualization:

Calculate the correlation matrix using data.corr() and visualize it using a heatmap with seaborn.
## Feature Selection:

Create feature matrix X by dropping the 'zip' column, and the target vector Y as the 'zip' column.
## Check for Relative Proportion:

Print the number of fraudulent cases, valid transactions, and the proportion of fraudulent cases.
## Pie Chart for Fraudulent Cases:

Create a new column in the dataset indicating whether a transaction is fraud or genuine, and plot a pie chart to visualize the distribution.
## Average Amount Analysis:

Print the average amount in fraudulent and valid transactions.
Display the summary statistics for the 'amt' feature.
## Check for Missing Values:

Check for null values in the dataset and print the count of missing and non-missing values.
## Data Splitting:

Separate the response variable ('is_fraud') and features. Use the train_test_split function from sklearn to split the data into training and testing sets.
## Label Encoding:

Use LabelEncoder from sklearn to convert categorical variables in the dataset to numerical format.
## Note on Encoding:

Display a note on encoding stating that certain categorical variables have been transformed using label encoding.
Please note that the code has some issues such as using the 'zip' column as the target variable (Y) and the usage of a few undefined variables like 'is_fraud'. Additionally, the label encoding is performed on the entire dataset, including both training and testing data, which may lead to data leakage. It's essential to handle these issues before applying machine learning models.





