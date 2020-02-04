# Generalized-Linear-Mixed-Models

This repository focuses on Non Linear models that are Linearized via a "Link Function". Analysis of these types of data sets require previously digested statistical knowledge (Shown in Linear Models Repository).

Assumption here change with regards to the Normal Distribution and must also be met. What is crucial about being able to manage different distribution of the exponential family is that naturally many data sets follow a certain type of probability distribution. When a data-set is forced to coerce with the normal distribution, usually ugly things are obligated to be done to the data, like estimating new variance parameters to re-estimate the variance data-set to comply with the "homoscedasticity" principle. This is messy, sometime data just has over-dispersion and just follows the poisson distribution. Sometimes the data might follow the poisson distribution but has too much overdispersion and other models must be given a chance. 

This README.md file is to specify the order of "difficulty" for the repositories, where difficulty is measured by number of models and different distributions in order to explain the data with the best amount of explained deviance (we no longer talk about variance in these models). 

#1 Poisson

#2 Bernoulli (a very specific type of Binomial distribution) 

#3 & 4 Poisson + Aleatory effects - Bernoulli + Aleatory effects (same difficulty)
This is what is known as a Generalized Linear Mixed Model. This model contemplates correlation that must be declared in the model for it to have statistically meaningful coefficient estimates.

