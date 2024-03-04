# Binomial distribution
This is an excerise for Udacity's [AI Programming with Python](https://www.udacity.com/course/ai-programming-python-nanodegree--nd089?_gl=1*1kctbqu*_up*MQ..&gclid=CjwKCAiA6byqBhAWEiwAnGCA4Nwb9FgNnKlOtUKjqVQP83iehOPuQQ_NSUB1G1Bm2dG8ESnE_L8ZWxoCoQsQAvD_BwE#plans) lesson 7.



## What is Binomial Distribution?

A **Binomial distribution** is a probability distribution that summarizes the likelihood of a binary outcome, such as success or failure, in a fixed number of independent trials. It's characterized by two parameters:

1. **Number of Trials (*n*)**: The total number of independent experiments or trials.
2. **Probability of Success (*p*)**: The probability of success in each individual trial.

In a Binomial distribution:

- Each trial is independent, meaning the outcome of one trial does not affect the outcome of another.
- Each trial has only two possible outcomes, often labeled as success (usually denoted as 1) or failure (usually denoted as 0).
- The probability of success (denoted as *p*) remains constant from trial to trial.
- The number of successes in *n* trials, denoted as *k*, can range from 0 to *n*.

The **probability mass function (PMF)** of the Binomial distribution gives the probability of observing exactly *k* successes in *n* trials, given the probability of success *p*.

The formula for the PMF of a Binomial distribution is:

\[ P(X = k) = \binom{n}{k} \times p^k \times (1 - 
