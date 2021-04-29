# coreweek2
#Overview 

Financial Inclusion remains one of the main obstacles to economic and human development in Africa. For example, across Kenya, Rwanda, Tanzania, and Uganda only 9.1 million adults (or 13.9% of the adult population) have access to or use a commercial bank account.

Traditionally, access to bank accounts has been regarded as an indicator of financial inclusion. Despite the proliferation of mobile money in Africa and the growth of innovative fintech solutions, banks still play a pivotal role in facilitating access to financial services. Access to bank accounts enables households to save and facilitate payments while also helping businesses build up their credit-worthiness and improve their access to other financial services. Therefore, access to bank accounts is an essential contributor to long-term economic growth.

The research problem is to figure out how we can predict which individuals are most likely to have or use a bank account. Your solution will help provide an indication of the state of financial inclusion in Kenya, Rwanda, Tanzania, and Uganda, while providing insights into some of the key demographic factors that might drive individuals’ financial outcomes.
Principles of Exploratory Data Analysis through summary statistics, plotting features, correlation analysis, and variable/feature importance. Statistical concepts i.e. descriptive analysis, inferential, hypothesis testing and confidence intervals 

#Steps taken
##Defining the question
##Metric for success
##Content
##Experimental design
##Importing libraries and loading the datasets viable for this project
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

sns.set_style()
df = pd.read_csv('/content/Financial Dataset - 1.csv.crdownload')
##Cleaning the dataset
###identifying and removing null values
###Correcting misspelt column headings
###Changing yes and no columns to 1 and 0 to allow numeric manipulation of data
###Looking for outliers
###Sorting values in "Respondent Age" in descinding order in order to find median
##Working on measures of central tendencies
These include finding the mean for "Has a ban account", and the mean, median nad mode for "Respondent Age"
##Finding the measures of dispersion
These are the range for "Respondent Age", skewness for all columns with numeric values, finding the variance, standard deviation, IQR, kurtosis and summary statistics for "respondent age"
##Univariate Analysis
###Plotting a histogram to show the number of respondents in the three countries
###Plotting a histogram for the repondents age
##Bivariate Analysis
###scatter plot to look for any correlation between the household size and respondents age
###scatter plot to look for relationship between the respondent age and access to cell phone
##Multivariate analysis
###Dropping the column 'uniquesid'
###Preprocessing our dataset into x and y
###Splitting the dataset into the training set and test set
###Normalisation
###Applying PCA
###Explained variance ratio
###Using 1 principal component
###Training and making predictions
###Performance evaluation
###Importing the confusion matrix and accuracy score
###Importing PCA
###Working on results with 2 principal components
#Answer the questions: 
was the dataset relevant to our question?
Was there a need for additional data in order to effectively answer the question?
did we have the right questions?
