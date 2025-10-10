# Discrete Probability Distributions

## Table of Contents

1. [What is Discrete Probability Distribution?](#1-what-is-discrete-probability-distribution)
2. [Probability Mass Function (PMF)](#2-probability-mass-function-pmf)

## 1. What is Discrete Probability Distribution?

A **probability distribution** is a rule or function that assigns probabilities to the possible values of a random variable. A **discrete probability distribution** applies when the random variable $X$ is discrete, meaning it can take on a finite or countably infinite number of distinct values.

[(back to top)](#table-of-contents)

## 2. Probability Mass Function (PMF)

**Probability Mass Function (PMF)** is a function that gives the probability that a discrete random variable $X$ takes on a specific value $x$, that is $P(X = x)$ and is frequently denoted as $f(x)$.

$P(X = x) = f(x)$

It satisfies the following properties:

| Property | Description | Expression |
| --- | --- | --- |
| **Non-Negativity** | The probability of each value is non-negative | $P(X = x) \geq 0$ |
| **Normalization** | The sum of probabilities over all possible values of $X$ is 1 | $\sum_{x \in S} P(X = x) = 1$ |

**Example | Tossing 3 Coins**

Imagine tossing three fair coins. Let $X$ represent the number of **Heads** obtained in the tosses. The possible values of $X$ are 0, 1, 2 and 3.

| Nr | Outcome | Number of Heads |
| --- | --- | --- |
| 1 | HHH | 3 |
| 2 | HHT | 2 |
| 3 | HTH | 2 |
| 4 | THH | 2 |
| 5 | HTT | 1 |
| 6 | THT | 1 |
| 7 | TTH | 1 |
| 8 | TTT | 0 |

**Heads** and **tails** are equally likely with a probability of 0.50. Each of the outcomes has an equal probability of $\frac{1}{8}$.

**PMF Table**

| $x$ | Outcomes | $P(X = x)$ |Probability |
| --- | --- | --- | --- |
| 0 | 1 | $= 1 \times \frac{1}{8}$ | $\frac{1}{8}$ or $0.125$ |
| 1 | 3 | $= 3 \times \frac{1}{8}$ | $\frac{3}{8}$ or $0.375$ |
| 2 | 3 | $= 3 \times \frac{1}{8}$ | $\frac{3}{8}$ or $0.375$ |
| 3 | 1 | $= 1 \times \frac{1}{8}$ | $\frac{1}{8}$ or $0.125$ |

All the properties of discrete probability distribution were satisfied in that:

- the probability of all possible values is non-negative, and
- the sum of all probabilities adds up to 1

$P(X = 0) + P(X = 1) + P(X = 2) + P(X = 3) = 1$
