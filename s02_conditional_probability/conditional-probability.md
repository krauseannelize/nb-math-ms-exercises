# Conditional Probability

## Table of Contents

1. [What is Conditional Probability?](#1-what-is-conditional-probability)
2. [Calculating Conditional Probability](#2-calculating-conditional-probability)

## 1. What is Conditional Probability?

**Conditional probability** measures the likelihood of an event occurring given that _another event has already happened_. The conditional probability of event $B$ given that event $A$ has occurred is denoted as $P(A \mid B)$ and is defined as:

$P(B \mid A) = \dfrac{P(A \cap B)}{P(A)}, \quad P(A) > 0$
 
where $P(A \cap B)$ is the probability that both events $A$ and $B$ have happened.

## 2. Calculating Conditional Probability

There are 5 balls in the box: two red and three blue. What is the probability of taking out a red ball after a blue one has been taken out?

$A$ | First ball is blue  
$B$ | Second ball is red

$P(A) = \dfrac{3}{5}$   

$P(B) = \dfrac{2}{4}$  

$P(A \cap B) = P(A) \times P(B) = \dfrac{3}{5} \times \dfrac{2}{4} = \dfrac{3 \times 2}{5 \times 4} = \dfrac{6}{20} = \dfrac{3}{10}$

$P(B \mid A) = \dfrac{P(A \cap B)}{P(A)} = \dfrac{3}{10} \div \dfrac{3}{5} = \dfrac{3}{10} \times \dfrac{5}{3} = \dfrac{3 \times 5}{10 \times 3} = \dfrac{15}{30} = \dfrac{1}{2}$

The probability of taking out a red ball after a blue one has been taken out is $\dfrac{1}{2}$ or 0.5.

