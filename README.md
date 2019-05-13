# machine-learning
This is a repository for Supervised Machine Learning Modelling along with the explaination of models.

## Linear Regression
- Least Squares Regression
- Least Mean Squares Regression

##### Least Squares
The best fit in the least-squares sense minimizes the sum of squared residuals (a residual being: the difference between an observed value, and the predicted value provided by a model) i.e. our goal is to minimize the error or cost function. This method provides the best fit to the data using simple calculus and linear algebra. We have a set of independent variables, using them we find weight vector to fit linear model with our dataset. Once, we have the "best fitting line", we can predict values for unknown variable. The weight vector can be calculated using below equation:

##### Least Mean Squares
Least Squares works well with small datasets. However, if the dataset is sufficiently large it is quite expensive(computationally) to apply Least Squares Algorithm to find the best fit for the model. We use online or sequential learning. In this type of learning, we introduce datapoints either in batches or one by one(again depending on our model) and iterate over the dataset.
Gradient Descent is a very generic optimization algorithm capable of finding optimal solutions to a wide range of problems. The general idea of Gradient Descent is to tweak parameters iteratively in order to minimize the  cost function. After derivation, we got the below equation for calculating the weight vector in online or sequential learning:


## Classification
- Pocket Algorithm 
- Quadratic Discriminant Analysis (QDA)
- Linear Discriminant Analysis (LDA)
- Logistic Regression using Softmax

Here are some key points about these Classification algorithms:

- **Pocket Algorithm** is the extension of Perceptron algorithm where we capture the best weight vector for our dataset.

- **LDA** and **QDA** are the generative models that are probablistic. Bayes' rule is freqently applied to compute the joint distribution from the conditional probabilty.

- **Logistic Regression** uses a **Softmax** function to predict the probability of the class. Input values (X) are combined linearly using weights or coefficient values to predict an output value (T). A key difference from linear regression is that the output value being modeled is a class values rather than a numeric value.

