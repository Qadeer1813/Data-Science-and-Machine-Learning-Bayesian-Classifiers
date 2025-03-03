# Data-Science-and-Machine-Learning-Bayesian-Classifiers

**Student Name: Qadeer Hussain**

**Student ID: C00270632**

**Lecture: Greg Doyle**

**Bayes Classifier**

# Project Description
The purpose of this project is to predict a persons income is less then or greater than $50,000 a year 

# Data Source
The dataset that was used for this project can be downloaded from https://archive.ics.uci.edu/dataset/2/adult

# Data
Attributes
- age
- workclass
- fnlwgt
- education
- education-num
- marital-status
- relationship
- race
- sex
- capital-gain
- capital-loss
- hours-per-week
- native-country
- income
  
# Processing
After downloading this dataset, a test print was conducted using the following piece of code ```data.head()```, ```data.info()```.  The loaded data was then displayed. A check was done to find missing values in the dataframe using the following piece of code ```missing_values = data.isnull().sum()```. This found no missing values in the dataset. Striped any white spaces. Binary indicator columns were created for capital gain and capital loss, marking whether a person had any gain or loss. Additionally, a log transformation was applied to both capital gain and loss values to reduce skewness. One hot encoding was then done on the following columns ```workclass```, ```education```, ```marital-status```, ```occupation```, ```relationship```, ```race```, ```sex```, ```native-country```. The data was then split into features and target variable ```income```. Data was then split into training and testing set 70% training and 30% testing.

# Data Understanding and Visualisation 
After processing the data and fitting it to the Gaussian Bayes and MultiNomial Bayes the classifcation report and the confusion matrix were created.

1. Gaussian Bayes Classfication report

   ![image](https://github.com/user-attachments/assets/6acd0381-e3b2-440e-a7c7-2223d3a63ee8)

2. MultiNomial Bayes Classfication report

   ![image](https://github.com/user-attachments/assets/d9de6ac5-134a-44cd-9621-0849eb0e96f7)

3. MultiNomial Bayes Confusion Matrix

   ![image](https://github.com/user-attachments/assets/b49a0eec-ff5a-4c27-b21e-b3d62952e34a)

# Algorithims:
Gaussian Bayes Classifier:

MultiNomial Bayes Classifier:

# Online Sources:
1. User guide# (2024) User Guide - pandas 2.2.3 documentation. Available at: https://pandas.pydata.org/docs/user_guide/index.html (Accessed: Jan 2025).
2. Matplotlib 3.9.2 documentation# (2024) Matplotlib documentation - Matplotlib 3.9.2 documentation. Available at: https://matplotlib.org/stable/ (Accessed: Jan 2025).
3. User guide (2024) scikit. Available at: https://scikit-learn.org/stable/user_guide.html (Accessed: Jan 2025).
4. Jakevdp (2023) Pythondatasciencehandbook/notebooks/05.05-Naive-Bayes.ipynb at master · JAKEVDP/Pythondatasciencehandbook, GitHub. Available at: https://github.com/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.05-Naive-Bayes.ipynb (Accessed: Jan 2025).

# Tools and Tech Used: 
1. Jupter Notebook
2. Gaussian Bayes Classifier
3. MultiNomial Bayes Classifiers 
4. Pandas Library - Loading the data and analysing it
5. Matplotlib - Plotting and Visualising the graph 
6. Scikit Learn(Sklearn) - Implementing Gaussian Bayes Classifier & MultiNomial Bayes Classifier.
