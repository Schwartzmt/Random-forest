# Random-forest
This repository uses a bank churn modeling dataset to demonstrate the homogenous ensemble approach (Random forest). Numpy, seaborn, and pandas are some of the different libraries used. First, the dataset is loaded, and any missing values are inspected. In this instance, there are no null values. Preprocessing involves deleting unnecessary columns from the dataset. RowNumber, CustomerId, and Surname in the churn modeling dataset are examples of this because they have no bearing on the examination of the data.

The data is processed via feature engineering, which uses One Hot Encoding to convert categorical data to numerical data. Under the 0.2 test fraction, the data are divided into training and test sets.The creation of a homogenous ensemble random forest classifier and evaluation of its accuracy score can be repeated numerous times using various tree counts and Gini criteria. More trees and Gini criteria result in more accuracy.
