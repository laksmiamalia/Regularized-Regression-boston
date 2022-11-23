# Regularized-Regression-boston
Regularized Regression for Boston Housing

![Security Features (1)](https://user-images.githubusercontent.com/113813929/203614358-2ee8df8f-e7aa-4da2-b934-2d52c298475f.jpg)

Here I try to do regularized regression as part of weekly assignment for dibimbing Data Science Class Batch 16, with [boston](https://github.com/pararawendy/dibimbing-materials/blob/main/boston.csv) dataset. I compared between Ridge and Lasso methods, based on their RMSE, MAE and/or MAPE value. <br>

Lasso is short for Least Absolute Shrinkage and Selection Operator, which is used both for regularization and model selection. If a model uses the L1 regularization technique, then it is called lasso regression. Meanwhile, ridge regression puts a similar constraint on the coefficients by introducing a penalty factor. However, while lasso regression takes the magnitude of the coefficients, ridge regression takes the square. <br>
[source](https://www.datacamp.com/tutorial/tutorial-lasso-ridge-regression)

**Dataset Explanation** <br>
`crim` : Criminal Rate <br>
`zn` : Residential land zoned proportion <br>
`indus` : Non-retail business proportion <br>
`chas` : Is bound with river <br>
`nox` : Nitrogen Oxide Concentration <br>
`rm` : Number rooms average <br>
`age` : Owner age proportion <br>
`dis` : Weighted distance to cities <br>
`rad` : Accessibility index <br>
`tax` : Tax rate <br>
`ptratio` : Pupil-teacher ratio <br>
`black` : Black proportion <br>
`lstat` : Percent lower status <br>

## Goals for the Project 
Find out which one is the best **Regularized Regression Method** for **BOSTON** dataset, **Ridge** or **Lasso**, based on their **RMSE** [Root Mean Squared Deviation], **MAE** [Mean Absolute Error], and **MAPE** [ Mean Absolute Percentage Error] value with the best **Lambda**. <br>

## Used Library
Python, numpy, pandas, seaborn and matplotlib
