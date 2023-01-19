# What is Machine Learning?
Layman:
```
    Machine Learning can be defined as the ability of a machine to learn something without having to be programmed for that specific thing.
    
    computers use a massive set of data and apply algorithms for ‘training’ themselves and making predictions.
```
Def:
```
    Machine learning is a subset of Artificial Intelligence that comprises algorithms programmed to gather information without explicit instructions at each step.
```

Story:
```
    Machine Learning is a subset of AI where the machine is trained with a lot of data
    and that machine is used to solve some problems based on its training(prior experiences) even though the scenario is new to it.
    This is done without any explicit programming for that particular scenario.
```

# What is an Algoritm?
```Algorithm is a set of instructions```

# What is Machine Learning Algorithm??
```Machine Learning algorithm are sets of instructions that the model follows to return an acceptable result```

# What is Supervised Machine Learning?
```
    Supervised learning is the type of machine learning in which 
    machines are trained using well "labelled" training data. --> Training require more computation time.
```
# What is Unsupervised Machine Learning?
```
    Unsupervised learning is a type of machine learning in which 
    models are trained using unlabeled dataset
```
# What is Parametric Model?
```

```
# What is Non-Parametric Model?
```

```
# What is Bias and Variance?
```
Bias:
    Assumptions made by a model to make a function easier to learn.
     
    * It is actually the error rate of the training data. 
    * When the error rate has a high value, we call it High Bias and 
      when the error rate has a low value, we call it low Bias.
    
Variance:  
    * The difference between the error rate of testing data is called variance. 
    * If the difference is high then it’s called high variance and 
      when the difference of errors is low then it’s called low variance. 
```
# What is OverFitting?
```
A statistical model is said to be overfitted when
    the model does not make accurate predictions on testing data.
```
Reasons for Overfitting are as follows:
```
    1.High variance and low bias 
    2.The model is too complex
    3.The size of the training data 
```
Techniques to reduce overfitting:

```
    1.Increase training data.
    2.Reduce model complexity.
    3.Early stopping during the training phase (have an eye over the loss over the training period as soon as loss begins to increase stop training).
    4.Ridge Regularization and Lasso Regularization
    5.Use dropout for neural networks to tackle overfitting.
    6.Ensembling
    7.Removing Features
```
# What is UnderFitting?
```
A statistical model or a machine learning algorithm is said to have underfitting when 
it cannot capture the underlying trend of the data, 
i.e., it only performs well on training data but performs poorly on testing data. 
```
