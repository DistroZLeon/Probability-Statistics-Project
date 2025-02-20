# Probability&Statistics Project
## Main purpose:
Use of different R functions, familiarisation with the Shiny package and learning the various particularities of the cumulative density functions of the probability repartisions.
## Requirements:

### I. Simulation of Total Activity Time
Consider an activity that involves sequentially completing `n` stages. The time required to complete stage `i` by a person `A` is a random variable `T_i ~ Exp(λ_i)`. After completing stage `i`, `A` will proceed to stage `i+1` with probability `α_i` or stop working with probability `1 - α_i`. The total time spent by person `A` in completing the activity is defined as `T`.

#### Requirements:
1. Implement an algorithm in R that simulates `10^6` values for `T` and approximates `E(T)`. Graphically represent the obtained values for `T`. What can you say about the distribution of `T`?
2. Compute the exact value of `E(T)` and compare it with the simulated value.
3. Approximate the probability that person `A` completes the activity.
4. Approximate the probability that person `A` completes the activity in a time `≤ σ`.
5. Determine the minimum and maximum time in which `A` completes the activity. Graphically represent the completion times and analyze their distribution.
6. Approximate the probability that `A` stops working before stage `k`, where `1 < k ≤ n`. Graph these probabilities and analyze their distribution.

---

### II. Shiny Application for the Negative Binomial Distribution
Develop a Shiny application that presents the five alternative formulations of the Negative Binomial Distribution, along with all known parameterizations and related distributions.

#### Requirements:
1. Graphically represent the probability mass function and cumulative distribution function for different parameters.
2. Create an animation that highlights how the shape of the functions changes as parameters vary.
3. Illustrate examples of applications where the Negative Binomial Distribution is relevant.

---

### III. Shiny Application for Graphical Representation of Distribution Functions
Develop a Shiny application to represent the distribution functions of the following random variables:

1. X = sum(i=1 to n) [X_i^2] - sum(i=1 to n) [X_i], where X_i ~ N(0,1)
2. X = sum(i=1 to n) [X_i^2] - sum(i=1 to n) [X_i], where X_i ~ N(mu, sigma^2)
3. X = sum(i=1 to n) [X_i] + 2, where X_i ~ Exp(lambda)
4. X = sum(i=1 to n) [X_i] - 3, where X_i ~ Pois(lambda)
5. X = sum(i=1 to n) [X_i] - 5, where X_i ~ Binom(r, p)

#### Useful Resources:
- [Shiny Basics](https://shiny.posit.co/r/getstarted/shiny-basics/lesson1/)
- [Negative Binomial Distribution](https://en.wikipedia.org/wiki/Negative_binomial_distribution)

