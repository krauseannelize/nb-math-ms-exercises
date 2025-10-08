# Bayes' Theorem

## Table of Contents

1. [What is Bayes' Theorem?](#1-what-is-bayes-theorem)
2. [How Bayes’ Theorem Follows from Conditional Probability](#2-how-bayes-theorem-follows-from-conditional-probability)
3. [Bayesian Components](#3-bayesian-components)
4. [Marginal Probability](#4-marginal-probability)
5. [Bayes’ Theorem in Action](#5-bayes-theorem-in-action)

## 1. What is Bayes' Theorem?

**Bayes' theorem** provides a way to calculate the probability of event $A$ given that event $B$ has occurred, incorporating prior knowledge or evidence into our calculations.

[(back to top)](#table-of-contents)

## 2. How Bayes’ Theorem Follows from Conditional Probability

Following the **multiplication rule** from **Conditional Probability**, the joint probability of events $A$ and $B$ can be written in two equivalent ways:

$P(A \cap B) = P(A \mid B) \times P(B) = P(A) \times P(B \mid A)$

Equating the two expressions gives:

$P(A \mid B) \times P(B) = P(A) \times P(B \mid A)$

Finally, solving for $P(A \mid B)$ yields **Bayes’ Theorem**:

$P(A \mid B) = \dfrac{P(A) \cdot P(B \mid A)}{P(B)}$

[(back to top)](#table-of-contents)

## 3. Bayesian Components

![](/s02_conditional_probability/bayes-formula.png)

| Component | Notation | Meaning |
| --- | --- | --- |
| **Posterior** | $P(A \mid B)$ | Probability of event $A$ given that event $B$ has occurred |
| **Likelihood** | $P(B \mid A)$ | Probability of event $B$ given that event $A$ has occurred |
| **Prior** | $P(A)$ | Probability of event $A$ |
| **Marginal** | $P(B)$ | Probability of event $B$ |

[(back to top)](#table-of-contents)

## 4. Marginal Probability

**Marginal probability** is the probability of an event happening, regardless of other related events. Suppose events $A_1, A_2 \dots, A_n$ cover all possibilities and form a full set, meaning they are mutually exclusive (no two can occur together) and exhaustive (one of them must occur):

$P(A_1) + P(A_2) + \dots P(A_n) = 1$

If we want the probability of another event $B$, we can calculate it by adding up the contributions from each scenario:

$P(B) = P(A_1 \cap B) + P(A_2 \cap B) + \dots + P(A_n \cap B)$  

Each term $P(A_i \cap B)$ can be rewritten using conditional probability:

$P(A_i \cap B) = P(B \mid A_i) \cdot P(A_i)$

So the full expression becomes:

$P(B) = P(B \mid A_1) \cdot P(A_1) + P(B \mid A_2) \cdot P(A_2) +\dots + P(B \mid A_n) \cdot P(A_n)$

[(back to top)](#table-of-contents)

## 5. Bayes’ Theorem in Action

Suppose we have two boxes: a yellow one ($Y$) and a green one ($G$). Each box contains marbles, either red ($R$) or blue ($B$). The yellow box has 1 blue marble and 1 red marble, while the green box has 6 blue marbles and 2 red marbles. We will choose a box uniformly at random, then draw one marble. If the randomly drawn marble is red, which box did it most likely come from?

![Marble Boxes](/s02_conditional_probability/marble-boxes.png)

**_Conditional probabilities:_**

$P(\text{R} \mid \text{G}) = \dfrac{\text{2 red marbles}}{\text{8 total marbles}} = \dfrac{1}{4} = 0.25$

$P(\text{R} \mid \text{Y}) = \dfrac{\text{1 red marble}}{\text{2 total marbles}} = 0.50$

**_Prior probabilities:_**

Choosing either box is equally likely so:

$P(Y) = P(G) = 0.50$

**_Marginal probability:_**

$P(R) = P(R \mid Y) \cdot P(Y) + P(R \mid G) \cdot P(G)$

$\quad \quad \quad = (0.50) \cdot (0.50) + (0.25) \cdot (0.50) = 0.25 + 0.125 = 0.375$

**_Posteriors (Bayes' Theorem):_**

$P(Y \mid R) = \dfrac{P(Y) \cdot P(R \mid Y)}{P(R)} = \dfrac{0.50 \times 0.50}{0.375} = \dfrac{2}{3} \approx 0.67$

$P(G \mid R) = \dfrac{P(G) \cdot P(R \mid G)}{P(R)} = \dfrac{0.50 \times 0.25}{0.375} = \dfrac{0.125}{0.375} = \dfrac{1}{3} \approx 0.33$

If a red marble is drawn, it is most likely to have come from the **yellow box**, with probability $0.67$.

---

Proceed to next section: [Bayes' Theorem Exercises](/s02_conditional_probability/exercises-bayes-theorem.md)

[(back to top)](#table-of-contents)  
[(back to README)](/README.md)
