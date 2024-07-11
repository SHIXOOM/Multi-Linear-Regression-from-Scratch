# Multi-Linear-Regression-from-Scratch
In this mini project I tried to implement a Multi Linear Regressor from scratch to further understand the concept of linear regression and get a since of its implementation in terms of How and Why so that I get better intuition on how it works too.

<u> Hypothesis Function:</u> $h(\vec{x}) = \vec{w}.\vec{x} + b$  
Which is the function we can predict the outputs with


<u> Cost Function:</u>
\\[
J(\vec{w}, b) = \frac{1}{2m} \sum_{i = 1}^{m} \left(((\vec{w}.\vec{x}^{(i)} + b) - y^{(i)}) \right)^2
\\]
The function that calculates the error (Mean Squared Error)

<u> # Gradient Descent: </u>
![Gradient Descent Algorithm](readme%20assets/Gradient.jpeg)

<u> # Code plan: </u>
![Code plan](readme%20assets/Plan.jpeg)


My Model scored an MSE of about 0.65 on California's Housing Dataset, which I think is fairly good
