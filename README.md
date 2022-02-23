# MACHINE-LEARNING

MACHINE LEARNING 
Machine Learning is making the computer learn from studying data and statistics.

Machine Learning is a step into the direction of artificial intelligence (AI).

Machine Learning is a program that analyses data and learns to predict the outcome.

Here are some important points to understand are as follow :
Data Set
In the mind of a computer, a data set is any collection of data. It can be anything from an array to a complete database.

Data Types
To analyze data, it is important to know what type of data we are dealing with.We can split the data types into three main categories:

A) Numerical: Numerical data are numbers, and can be split into two numerical categories:

1.Discrete Data - numbers that are limited to integers. Example: The number of cars passing by.
2.Continuous Data - numbers that are of infinite value. Example: The price of an item, or the size of an item.

B) Categorical: Categorical data are values that cannot be measured up against each other. Example: a color value, or any yes/no values.

C) Ordinal : Ordinal data are like categorical data, but can be measured up against each other. Example: school grades where A is better than B and so on.

In Machine Learning (and in mathematics) there are often three values that interests us:
•	Mean - The average value, To calculate the mean, find the sum of all values, and divide the sum by the number of values.

•	Median - The median value is the value in the middle, after you have sorted all the values:

•	Mode - The median value is the value in the middle, after you have sorted all the values.

## Standard Deviation
Standard deviation is a number that describes how spread out the values are.
A low standard deviation means that most of the numbers are close to the mean (average) value.
A high standard deviation means that the values are spread out over a wider range.

### Percentiles
Percentiles are used in statistics to give you a number that describes the value that a given percent of the values are lower than.

### MACHINE LEARNING
Machine Learning refers to the process of training a computer program to build a statistical model based on data. The goal of machine learning (ML) is to turn data and identify the key patterns out of data or to get key insights.
Machine learning can be categorized into two main types: supervised learning and unsupervised learning.

Supervised learning is a machine learning algorithm of inferring a function from labeled training data. The training data consists of a set of training examples.

Unsupervised learning is also a type of machine learning algorithm used to find patterns on the set of data given. In this, we don’t have any dependent variable or label to predict.

![](https://github.com/SOMYYA1/MACHINE-LEARNING/blob/main/Supervised%20and%20Unsupervised.png)


### Simple Linear Regression 
If a single independent variable is used to predict the value of a numerical dependent variable, then such a Linear Regression algorithm is called Simple Linear Regression.

### Multli  Linear Regression
If more than one independent variable is used to predict the value of a numerical dependent variable, then such a Linear Regression algorithm is called Multiple Linear Regression.

When working with linear regression, our main goal is to find the best fit line that means the error between predicted values and actual values should be minimized. The best fit line will have the least error.

Bias is the difference between our actual and predicted values.

Scikit-learn is probably the most useful library for machine learning in Python. The sklearn library contains a lot of efficient tools for machine learning and statistical modeling including classification, regression, clustering and dimensionality reduction.

### Assumptions of Linear Regression Below are some important assumptions of Linear Regression.
These are some formal checks while building a Linear Regression model, which ensures to get the best possible result from the given dataset.

Linear relationship between the features and target.
Linear regression assumes the linear relationship between the dependent and independent variables.

Small or no multicollinearity between the features.
Multicollinearity means high-correlation between the independent variables.
It is difficult to determine which predictor variable is affecting the target variable and which is not. So, the model assumes either little or no multicollinearity between the features or independent variables.

Homoscedasticity Assumption:
Homoscedasticity is a situation when the error term is the same for all the values of independent variables. With homoscedasticity, there should be no clear pattern distribution of data in the scatter plot.

Linear regression assumes that the error term should follow the normal distribution pattern. If error terms are not normally distributed, then confidence intervals will become either too wide or too narrow, which may cause difficulties in finding coefficients. 
It can be checked using the q-q plot. If the plot shows a straight line without any deviation, which means the error is normally distributed.

No autocorrelations: The linear regression model assumes no autocorrelation in error terms. If there will be any correlation in the error term, then it will drastically reduce the accuracy of the model. Autocorrelation usually occurs if there is a dependency between residual errors.

### Train/Test
Train/Test is a method to measure the accuracy of your model.It is called Train/Test because you split the the data set into two sets: a training set and a testing set. 80% for training, and 20% for testing.You train the model using the training set.
You test the model using the testing set. Train the model means create the model. Test the model means test the accuracy of the model.

### POLYMONIAL REGRESSION 
Polynomial regression, like linear regression, uses the relationship between the variables x and y to find the best way to draw a line through the data points.
 

### Decision Tree 
Decision Trees are a type of Supervised Machine Learning (that is you explain what the input is and what the corresponding output is in the training data) where the data is continuously split according to a certain parameter. The tree can be explained by two entities, namely decision nodes and leaves. The leaves are the decisions or the final outcomes. And the decision nodes are where the data is split.

Classification trees (Yes/No types) 
The decision variable is Categorical.

Regression trees (Continuous data types)
The decision or the outcome variable is Continuous, e.g. a number like 123.

### Clustering

![](https://github.com/SOMYYA1/MACHINE-LEARNING/blob/main/cluster.jfif)



Unsupervised learning is a machine learning technique in which models are not supervised using training dataset. 
The goal of unsupervised learning is to find the underlying structure of dataset, group that data according to similarities, and represent that dataset in a compressed format.

### K-Mean Clustering
One of the most used clustering algorithm is k-means. It allows to group the data according to the existing similarities among them in k clusters, given as input to the algorithm. I’ll start with a simple example. 







