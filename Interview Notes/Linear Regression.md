# What is Regression? ==> Def:
```
Regression is a statistical method used to determine 
    the strength and character of the relationship between one dependent variable and a series of  independent variables.
```
# What is simple Linear Regression?
```

```
# What is Multiple Linear Regression?
```

```



---
# What is Linear Regression? ==> Complete Story
```
Linear regression is Supervised ML Algorithm which is used to predict dependant variale based on one or more independant variable.
The prediction is done based on the best fit line

initially all the slopes and intercepts are initialized to one.
The Cost Function can be MSE, MAE, HuberLoss.    
Now the slopes and intercept values get updated using gradient descent concept till convergence (till we reach global minima or minimum cost function.)
Based on hyper parameter (learninng rate) the spped of convergence may vary.

if CF = MSE:
    The CF is differentiable and  it is a convex function and has one globa and one local minima.
    However it is not robust to outliers.
if CF = MAE:
    It is robbust to ourliers but it takes more time to converge.
    
So we use hubber loss as cost function to overcome these disadvantages.
    This huber loss is combination of MSE and MAE 
    It has hyperparamete delta.

```
# Performance Metrics:
R_SQUARE:
```

```
Adjusted_R_SQUARE :
```

```
