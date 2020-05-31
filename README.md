# Different Regression Models!

  - Simple Linear Regression
  - Multiple Linear Regression
  - Polynomial Linear Regression
  - Support Vector Regression
  - Decision Tree Regression
  - Random Forest Regression

# Most Asked Question
#### How do I choose from various regression model?

##### You can try to plot your data over the *x-y* axis and try to deduce the relationship between dependent variables and the independent variables. It can be a linear or curvilinear relationship.

##### Or you can just evaluate all the models with *R-squared*.
R-squared shows how close data values are to the fitted regression line.

***R-squared* is calculated as =>** **1 - RSE**

RSE - Relative Squared Error = ( **sum_of_all**( *y_act* - *y_pred* )^2 ) / ( **sum_of_all**( *y_act* - *y_mean*)^2 )

**or**
```python
from sklearn.metrics import r2_score
r2_score(y_test, y_pred)
```


**Author**
------
#### Chaitanya Laxman