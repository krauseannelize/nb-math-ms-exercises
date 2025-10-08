# Bayes' Theorem

## What is Bayes' Theorem?

**Bayes' theorem** provides a way to calculate the probability of event $A$ given that event $B$ has occurred, incorporating prior knowledge or evidence into our calculations.

## How Bayes’ Theorem Follows from Conditional Probability

Following the **multiplication rule** from **Conditional Probability**, the joint probability of events $A$ and $B$ can be written in two equivalent ways:

$P(A \cap B) = P(A \mid B) \times P(B) = P(A) \times P(B \mid A)$

Equating the two expressions gives:

$P(A \mid B) \times P(B) = P(A) \times P(B \mid A)$

Finally, solving for $P(A \mid B)$ yields **Bayes’ Theorem**:

$P(A \mid B) = \dfrac{P(A) \cdot P(B \mid A)}{P(B)}$

## Boxes with Marbles

Suppose we have two boxes: a yellow one and a green one. Each box contains marbles, either red or blue. The yellow box has 1 blue marble and 1 red marble, while the green box has 6 blue marbles and 2 red marble. If we were to draw a red marble blindly, which box would it be most likely to come from? 

![](/s02_conditional_probability/marble-boxes.png)


