# Ex03-Univariate-Analysis

# Aim:
To read the given data and perform the univariate analysis with different types of plots.
 
# Explanation:
Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.
    
# Algorithm:

## Step 1:
Read the given data.
    
## Step 2:
Get the information about the data.
    
## Step 3:
Remove the null values from the data.

## Step 4:
Mention the datatypes from the data.
    
## Step 5:
Count the values from the data.
    
## Step 6:
Do plots like boxplots,countplot,distribution plot,histogram plot.
    
# Program
```
Developed by : CHARU DHARSHINI K
Registration Number : 212221220008


import pandas as pd
import numpy as np
import seaborn as sns

df=pd.read_csv('superstore.csv')
df

df.head()

df.info()

df.describe()

df.isnull().sum()

df.dtypes

df['Postal Code'].value_counts()

sns.boxplot(x='Postal Code', data=df)

sns.countplot(x='Postal Code',data=df)

sns.distplot(df["Postal Code"])

sns.histplot(x='Postal Code',data=df)
```

# Output:

## DATA

![Output](1.jpg)
 
## DATA HEAD

![Output](2.jpg)

## DATA INFORMATION

![Output](3.jpg)

## DATA DESCRIBE

![Output](4.jpg)

## DATA NULL VALUES

![Output](5.jpg)

## DATA'S DATATYPES

![Output](6.jpg)

## DATA'S VALUECOUNT

![Output](7.jpg)

## BOXPLOT

![Output](8.jpg)

## COUNTPLOT

![Output](9.jpg)

## DISTRIBUTION PLOT

![Output](10.jpg)

## HISTOGRAM PLOT

![Output](11.jpg)

# Result:
Thus we have read the given data and performed the univariate analysis with different types of plots.





    
