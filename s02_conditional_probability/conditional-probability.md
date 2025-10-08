# Conditional Probability

## Table of Contents

1. [What is Conditional Probability?](#1-what-is-conditional-probability)
2. [Multiplication Rule](#2-multiplication-rule)
3. [Calculating Conditional Probability](#3-calculating-conditional-probability)
4. [Independent Events](#4-independent-events)
5. [Dependant Events](#5-dependant-events)
6. [Mutually Exclusive Events](#6-mutually-exclusive-events)

## 1. What is Conditional Probability?

**Conditional probability** measures the likelihood of an event occurring given that _another event has already happened_. The conditional probability of event $B$ given that event $A$ has occurred is denoted as $P(A \mid B)$ and is defined as:

$P(B \mid A) = \dfrac{P(A \cap B)}{P(A)}, \quad P(A) > 0$
 
where $P(A \cap B)$ is the probability that both events $A$ and $B$ have happened.

[(back to top)](#table-of-contents)

## 2. Multiplication Rule

The probability that two events A and B both occur is given by:

$P(A \cap B) = P(A \mid B) \times P(B) \quad$ _(Probability of $A$ given $B$, multiplied by the probability of $B$)_

or by

$P(A \cap B) = P(A) \times P(B \mid A) \quad$ _(Probability of $B$ given $A$, multiplied by the probability of $A$)_

[(back to top)](#table-of-contents)

## 3. Calculating Conditional Probability

There are 5 balls in the box: two red and three blue. What is the probability of taking out a red ball after a blue one has been taken out?

$A$ | First ball is blue  
$B$ | Second ball is red

$P(A) = \dfrac{3}{5}$   

$P(B \mid A) = \dfrac{2}{4} = \dfrac{1}{2}$  

$P(A \cap B) = P(A) \times P(B \mid A) = \dfrac{3}{5} \times \dfrac{2}{4} = \dfrac{3 \times 2}{5 \times 4} = \dfrac{6}{20} = \dfrac{3}{10}$

$P(B \mid A) = \dfrac{P(A \cap B)}{P(A)} = \dfrac{3}{10} \div \dfrac{3}{5} = \dfrac{3}{10} \times \dfrac{5}{3} = \dfrac{3 \times 5}{10 \times 3} = \dfrac{15}{30} = \dfrac{1}{2}$

The probability of taking out a red ball after a blue one has been taken out is $\dfrac{1}{2}$ or 0.5.

[(back to top)](#table-of-contents)

## 4. Independent Events

Event $A$ and event $B$ are **independent** if the occurrence of one does not affect the probability of the other. It is expressed as:

$P(A \mid B) = P(A)$

For independent events, the **multiplication rule** simplifies to:

$P(A \cap B) = P(A) \times P(B)$

### Example 1 | Independent Events

Consider flipping a fair coin and rolling a six-sided die. Let event $A$ be getting Heads on the coin, and event $B$ be rolling a 4 on the die. Since flipping a coin does not influence the outcome of rolling a die:

$P(A) = \dfrac{1}{2}$

$P(B) = \dfrac{1}{6}$

$P(A \mid B) = P(A) = \dfrac{1}{2}$

---

### Example 2 | Independent Events

A recent survey of students suggested that 10% of students commute by bike, while 40% of them have a significant other. Based on this survey, what percentage of students commute by bike and have a significant other?

$A$ | Student commutes by bike  
$B$ | Student has a significant other

$P(A) = 0.10$  
$P(B) = 0.40$

$P(A \cap B) = P(A) \times P(B) = 0.1 \times 0.4 = 0.04$

---

[(back to top)](#table-of-contents)

## 5. Dependant Events

Event $A$ and event $B$ are **dependent** if the occurrence of one does affect the probability of the other. It is expressed using **conditional probability**:

$P(A \cap B) = P(A) \times P(B \mid A) = P(A \mid B) \times P(B)$

[(back to top)](#table-of-contents)

## 6. Mutually Exclusive Events

When events cannot occur at the same time, they are called **mutually exclusive** and are expressed as:

$P(A \text{ and } B) = 0$

---

Proceed to next section: [Conditional Probability Exercises](/s02_conditional_probability/exercises-conditional-probability.md)

[(back to top)](#table-of-contents)  
[(back to README)](/README.md)
