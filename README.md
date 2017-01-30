# Tutorials Data Science Basics

Melissa K (Oct 2016)

The following tutorials are a *step-by-step practical* implementation of
mathematical concepts that are at the very basis of machine learning.
I believe that mastering linear least squares, simple gradient descent and singular value
decomposition somewhat *by hand* is crucial to understanding
more advanced machine learning concepts, including Deep Learning.

- The primary focus here is on practicality (*Do it in Python*) rather than deriving
mathematical equations (there are tons of great tutorials out there that
cover that part in detail).

- The secondary focus is on connecting the dots between basic mathematical
concepts - for example you can fit a plane to a data cloud
using either least squares method or singular value decomposition...you will learn the difference and implications.

- Finally, the solutions derived *by hand* will be
compared to [sklearn](http://scikit-learn.org/stable/).



##### Table of content

1. [Linear Regression Models - Least Squares Method](Basics/Open-blackbox-basics-linear-regression-modeling.ipynb)

    Covering various multiple linear regression cases (e.g. continuous vs. mixed type features/independent
    variables to predict a continuous target/dependent variable using a closed-form solution)


2. [Binomial Logistic Regression - Gradient Descent Optimization](Basics/Open-blackbox-basics-classification-binomial-logistic-regression.ipynb)

    Covering simple gradient descent optimization as iterative method to predict a
    binary target/dependent variable.

3. [Principal Component Analysis (PCA)](Basics/Open-blackbox-basics-principal-component-analysis.ipynb)

    Introducing Principal Component Analysis (PCA) using singular value decomposition to fit a plane
    to a data cloud in 3D.
