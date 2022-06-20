# LogRegression-on ML-(Insurance-Data/ iris dataset)(reference:https://learn.g2.com/logistic-regression)

Logistic regression is named after the function used at its heart, the logistic function. Statisticians initially used it to describe the properties of population growth. Sigmoid function and logit function are some variations of the logistic function. Logit function is the inverse of the standard logistic function.

            ![image](https://user-images.githubusercontent.com/83010684/174529370-51f4eb34-1773-436c-b473-c19fec8319b0.png)


In effect, it's an S-shaped curve capable of taking any real number and mapping it into a value between 0 and 1, but never precisely at those limits. It's represented by the equation:


                     f(x) = L / 1 + e^-k(x - x0)
                     
                     
f(X) is the output of the function.

L is the curve’s maximum value.

e is the base of the natural logarithms.

k is the steepness of the curve.

x is the real number.

x0 is the x values of the sigmoid midpoint.

If the predicted value is a considerable negative value, it's considered close to zero. On the other hand, if the predicted value is a significant positive value, it's considered close to one.

Logistic regression is represented similar to how linear regression is defined using the equation of a straight line. A notable difference from linear regression is that the output will be a binary value (0 or 1) rather than a numerical value.


 ### Here’s an example of a logistic regression equation:
    
                      y = e^(b0 + b1*x) / (1 + e^(b0 + b1*x))
                      
In this equation:

y is the predicted value (or the output)

b0 is the bias (or the intercept term)

b1 is the coefficient for the input

x is the predictor variable (or the input)

The dependent variable generally follows the Bernoulli distribution. The values of the coefficients are estimated using maximum likelihood estimation (MLE),  gradient descent, and stochastic gradient descent.

As with other classification algorithms like the k-nearest neighbors, a confusion matrix is used to evaluate the accuracy of the logistic regression algorithm.

#### In a nutshell, by looking at historical data, logistic regression can predict whether:

###### An email is a spam

###### It’ll rain today

###### A tumor is fatal

###### An individual will purchase a car

###### An online transaction is fraudulent

###### A contestant will win an election

###### A group of users will buy a product

###### An insurance policyholder will expire before the policy term expires

###### A promotional email receiver is a responder or non-responder
