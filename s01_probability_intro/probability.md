# Probability

## Table of Contents

1. [What is Probability?](#what-is-probability)
2. [Key Terms](#key-terms)
3. [Set Operations](#set-operations)
4. [Probability Interpretations](#probability-interpretations)
5. [Probability Theorems](#probability-theorems)

## 1. What is Probability?

Formally, **probability** is defined as a set function $P$ that assigns to each event $A$ in the sample space $S$ (sometimes written $\Omega$) a number $P(A)$, called the probability of the event $A$, while obeying these _axioms of probability_ (Kolmogorov’s 3 rules):

| Axiom | Description | Formula |
| --- | --- | --- |
| **Non-negativity** | The probability of any event $P(A)$ must be non-negative | $P(A) \geq 0$ |
| **Normalization** | The probability of the sample space $P(S)$ is 1 | $P(S) = 1$ |
| **Additivity** | For mutually exclusive events, the probability of their union is the sum of their probabilities | $P(A_1 \cup A_2 \cup \dots \cup A_n) = P(A_1) + P(A_2) + \dots + P(A_n)$ |

Informally, when all outcomes are equally likely, **probability** is the ratio of the number of elements in the event to the number of elements in the sample. It helps us understand and quantify uncertainty. The probability of an event is a number between 0 and 1. The larger the probability, the more likely the event is to occur. We can write this as:

$\text{Probability(Event)} = \frac{\text{Number of elements in the event}}{\text{Number of elements in the sample}}$

$P(A) = \frac{N(A)}{N(S)}$

[(back to top)](#table-of-contents)

## 2. Key Terms

| Term | Definition |
| --- | --- |
| **Event** | A specific outcome or set of outcomes of an experiment |
| **Equally Likely Events** | Events that each have the same probability of occurring |
| **Exhaustive Events** | A set of events whose union equals the sample space, covering all possible outcomes |
| **Experiment** | An action or process that leads to one of several possible outcomes |
| **Mutually Exclusive Events** | Events that cannot happen simultaneously |
| **Outcome** | A single result from the sample space |
| **Random Experiment** | An experiment whose outcome cannot be predicted with certainty in advance, but which has a well‑defined set of possible outcomes |
| **Sample Space** | The set of all possible outcomes of an experiment |

[(back to top)](#table-of-contents)

## 3. Set Operations

Before we can state and prove useful theorems in probability, we need to recall some basic **set operations**. Since events are sets of outcomes, these operations give us the tools to combine, compare, and manipulate events mathematically.

| Operation | Description | Formula |
| --- | --- | --- |
| **Empty set** | The impossible event with no outcomes | $\varnothing$ |
| **Union** | All the elements of set $A$ and all the elements of set $B$ | $A \cup B$ |
| **Intersection** | All the elements that are present in both $A$ and $B$ | $A \cap B$ |
| **Complement** | The event that $A$ does not occur | $A'$ |
| **Subset** | All elements of $A$ are also elements of $B$ | $A \subseteq B$ |
| **Cartesian product ($A \times B$)** | The set of all ordered pairs $(a,b)$ with $a$ in $A$ and $b$ in $B$ | $A \times B =$ { $(a,b) \mid a \in A \text{ and}\ b \in B$ } |

[(back to top)](#table-of-contents)

## 4. Probability Interpretations

Probability can be understood in different ways depending on how we assign or justify the numbers that describe uncertainty. In modern mathematics, all of these views are unified under the axiomatic framework, which provides the rigorous foundation for probability theory. The main interpretations are summarized below.

| Type / Approach | Definition & Context | Example |
| --- | --- | --- |
| **Classical (Theoretical)** | Probability is calculated as the ratio of favorable outcomes to total equally likely outcomes. Used in symmetric experiments where all outcomes are equally likely | Rolling a fair die: $P(\text{even}) = 3/6 = 0.5$ |
| **Empirical (Relative Frequency)** | Probability is estimated from past data or repeated trials, using the proportion of times an event occurs | It rained on 90 of 365 days → $P(\text{rain}) \approx 90/365$ |
| **Subjective** | Probability reflects personal belief or expert judgment, often used when data is limited or uncertainty is high | A doctor estimates a 70% chance of recovery |
| **Axiomatic** | Probability is defined as a set function $P$ that satisfies Kolmogorov’s three axioms. This framework provides the rigorous foundation from which all probability theorems are derived | _See theorems section below_ |

[(back to top)](#table-of-contents)

## 5. Probability Theorems

Using the language of set theory and the axiomatic definition of probability, we can derive several fundamental theorems. These theorems capture the essential properties of probability and provide the tools for solving more complex problems. Each theorem follows directly from the axioms and the definitions of events, complements, unions, and intersections.

| # | Theorem | Formula |
|---|---------|---------|
| 1 | **Complement Rule**: The probability of an event is one minus the probability of its complement | $P(A) = 1 - P(A')$ |
| 2 | **Impossible Event**: The probability of the empty set is zero | $P(\varnothing) = 0$ |
| 3 | **Subset Rule**: If $A$ is a subset of $B$, then the probability of $A$ is less than or equal to the probability of $B$ | If $A \subseteq B$, then $P(A) \leq P(B)$ |
| 4 | **Bounds of Probability**: The probability of any event lies between 0 and 1 | $0 \leq P(A) \leq 1$ |
| 5 | **Inclusion–Exclusion (Two Events)**: The probability of the union of two events is the sum of their probabilities minus their intersection | $P(A \cup B) = P(A) + P(B) - P(A \cap B)$ |

---

### Example | Theorem 1

A standard deck of cards has 52 cards. Let event $A$ be drawing a Heart from the deck and event $B$ be drawing any card that is not a Heart.

$P(A) = \frac{N(A)}{N(S)} = \frac{\text{Number of Heart cards}}{\text{Number of cards in deck}} = \frac{13}{52} = \frac{1}{4} = 0.25$

$P(B) = \frac{N(A)}{N(S)} = \frac{\text{Number of Non-Heart cards}}{\text{Number of cards in deck}} = \frac{39}{52} = \frac{3}{4} = 0.75$

Here, $B$ is the complement of $A$ and thus according to the complement rule:

$P(A) = 1 - P(A') = 1 - P(B) = 1 - 0.75 = 0.25$

---

### Example | Theorem 2

When rolling a standard six-sided die, there are no outcomes where the result is greater than 6 (event A). This means:

$A = \varnothing$

Therefore, the probability of this event is:

$P(A) = 0$

---

### Example | Theorem 3  

From a standard deck of 52 cards, let event $A$ be drawing a red queen and event $B$ be drawing any red card. Since every red queen is also a red card, we have $A \subseteq B$.

$P(A) = \frac{N(A)}{N(S)} = \frac{\text{Queen of Hearts, Queen of Diamonds}}{\text{Number of cards in deck}} = \frac{2}{52} = \frac{1}{26} \approx 0.0385$

$P(B) = \frac{N(B)}{N(S)} = \frac{\text{Number of red cards}}{\text{Number of cards in deck}} = \frac{26}{52} = \frac{1}{2} = 0.5$

Therefore, $P(A) \leq P(B)$, which confirms the subset rule.

---

### Example | Theorem 4

When rolling a standard six‑sided die, let:

$A = \{1,2,3,4,5,6\}$ (all possible outcomes)  
$B = \{2,4,6\}$ (even numbers)

To calculate the probability of each event:

$P(A) = \frac{N(A)}{N(S)} = \frac{6}{6} = 1$

$P(B) = \frac{N(B)}{N(S)} = \frac{3}{6} = \frac{1}{2} = 0.5$

In both cases, the probability of the event lies between 0 and 1, confirming that $0 \leq P(E) \leq 1$ for any event $E$.

---

### Example | Theorem 5

Consider a classroom of 30 students:

| Event | Description | Notation |
|-------|-------------|----------|
| $A$   | Student plays a musical instrument | $N(A) = 18$ |
| $B$   | Student speaks a second language   | $N(B) = 15$ |
| $A \cap B$ | Student both plays a musical instrument and speaks a second language | $N(A \cap B) = 10$ |

To calculate the probability of each event:

$P(A) = \frac{N(A)}{N(S)} = \frac{18}{30} = \frac{3}{5}$

$P(B) = \frac{N(B)}{N(S)} = \frac{15}{30} = \frac{1}{2}$

$A \cap B = \frac{10}{30} = \frac{1}{3}$ 

The probability that a randomly selected student either plays a musical instrument or speaks a second language is:

$P(A \cup B) = P(A) + P(B) - P(A \cap B)$

$P(A \cup B) = \frac{18}{30} + \frac{15}{30} - \frac{10}{30} = \frac{18 + 15 - 10}{30} = \frac{23}{30}$

---

Proceed to next section: [Probability Exercises](/s01_probability_intro/probability-exercises.md)

[(back to top)](#table-of-contents)  
[(back to README)](/README.md)
