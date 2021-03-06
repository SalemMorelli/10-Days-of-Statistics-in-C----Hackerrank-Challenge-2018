
# 10-Days-of-Statistics-in-C++ Hackerrank-Challenge-2018

# The Challenge
10 Days of Statistics is a challenge on Hackerrank. The challenge covers the basics of statistics with levels spanning Easy to Medium.  I coded all the exercises in my core programming language C++. The questions that did not require coding have an explanation appended to them as to how the answer was derived. 

# Probability and Statistic notes taken from Hackerrank


### Combinations and Permutations:-
Mathematically, the different terms usually mean
1. Permutations: Number of ways in which n different things can be arranged among themselves (n!)
2. Combinations: Number of ways in which r things can be chosen from n different things (C(n,r))
3. Combination with order: Number of ways in which r things can be chosen from n different things, order of choosing being important (P(n,r))

-------------------------------------------------------------------------------------------------------------------------------------
### Binomial Distribution:-
Binomial distribution
Random number distribution that produces integers according to a binomial discrete distribution, which is described by the following probability mass function:


[Insert PMF here]
 

This distribution produces random integers in the range [0,t], where each value represents the number of successes in a sequence of t trials (each with a probability of success equal to p).


### Negative Binomial Experiment
A negative binomial experiment is a statistical experiment that has the following properties:

The experiment consists of  repeated trials.
- The trials are independent.
- The outcome of each trial is either success (s) or failure (f).
  is the same for every trial.
- The experiment continues until  successes are observed. 

If X is the number of experiments until the xth success occurs, then X is a discrete random variable called a negative binomial.

### Negative Binomial Distribution
Consider the following probability mass function:

The function above is negative binomial and has the following properties:

The number of successes to be observed is x .
The total number of trials is n.
The probability of success of 1 trial is p.
The probability of failure of 1 trial q, where q=1-p.
b*(x,n,p) is the negative binomial probability, meaning the probability of having x-1 successes after n-1 trials and having x successes after n trials. 

Note: Recall that nCr. For further review, see the Combinations and Permutations Tutorial. 

---------------------------------------------------------------------------------------------------------------------------------------
### Poisson Experiment
A Poisson experiment is a statistical experiment that has the following properties: 


The outcome of each trial is either success or failure.
The average number of successes  that occurs in a specified region is known.
The probability that a success will occur is proportional to the size of the region.
The probability that a success will occur in an extremely small region is virtually zero. 

---------------------------------------------------------------------------------------------------------------------------------------
### Central Limit Theorem
The central limit theorem (CLT) states that, for a large enough sample (), the distribution of the sample mean will approach normal distribution. This holds for a sample of independent random variables from any distribution with a finite standard deviation. 

### Covariance
This is a measure of how two random variables change together, or the strength of their correlation. 
>>>>>>> ab68733f5f2468b09e85ff9cbcbcd45637a002f3
