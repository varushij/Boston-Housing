# Boston-Housing
Boston House Price Prediction (Python) <br />
Being a real estate agent, one always wants to find the best house deal for their clients. In order to do so, the best they can do is study the market very well and understand which all factors can lead to what price of a house. <br />
To make things simpler for them and to help them gain and retain their clients, a statistical technique, called regression, can do this task and save them a lot of time and efforts. <br />
In this project, we aim at estimating the house prices in Boston area using linear regression technique. <br />
In this case, linear regression has succesully achieved an accuracy of 73% (R^2 = 0.73). This means, using this statistical model, one can estimate the correct house price (in Boston) 73% of the time. <br />

# Dataset:
The data set was taken from https://www.kaggle.com/c/boston-housing  <br />
It contains 506 entries with 14 columns divided into train.csv and test.csv <br />
The columns are: <br />
* crim: per capita crime rate by town.
* zn: proportion of residential land zoned for lots over 25,000 sq.ft.
* indus: proportion of non-retail business acres per town.
* chas: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise).
* nox: nitrogen oxides concentration (parts per 10 million).
* rm: average number of rooms per dwelling.
* age: proportion of owner-occupied units built prior to 1940.
* dis: weighted mean of distances to five Boston employment centres.
* rad: index of accessibility to radial highways.
* tax: full-value property-tax rate per $10,000.
* ptratio: pupil-teacher ratio by town.
* black: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town.
* lstat: lower status of the population (percent).
* medv: median value of owner-occupied homes in $1000s. <br />

Here, __medv__ is the target variable.

# Prerequisite
The project was developed using jupyter notebook (version 4.4.0) with Python 3. <br />
To run this project, following libraries needs to be installed - 
* Numpy
* Pandas
* Matplotlib
* Missingno
* Seaborn
* Sklearn
* Statsmodel

