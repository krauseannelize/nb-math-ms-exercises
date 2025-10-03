# Probability

## What is Probability?

Formally, **probability** is defined as a set function $P$ that assigns to each event $A$ in the sample space $S$ (sometimes written $\Omega$) a number $P(A)$, called the probability of the event $A$, while obeying these _axioms of probability_ (Kolmogorov’s 3 rules):

| Axiom | Description | Formula |
| --- | --- | --- |
| **Non-negativity** | The probability of any event $P(A)$ must be non-negative | $P(A) \geq 0$ |
| **Normalization** | The probability of the sample space $P(S)$ is 1 | $P(S) = 1$ |
| **Additivity** | For mutually exclusive events, the probability of their union is the sum of their probabilities | $P(A_1 \cup A_2 \cup \dots \cup A_n) = P(A_1) + P(A_2) + \dots + P(A_n)$ |

Informally, when all outcomes are equally likely, **probability** is the ratio of the number of elements in the event to the number of elements in the sample. It helps us understand and quantify uncertainty. The probability of an event is a number between 0 and 1. The larger the probability, the more likely the event is to occur. We can write this as:

$$
\text{Probability(Event)} = \frac{\text{Number of elements in the event}}{\text{Number of elements in the sample}}
$$
$$
P(A) = \frac{N(A)}{N(S)}
$$

## Key Terms

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

## Set Operations

Before we can state and prove useful theorems in probability, we need to recall some basic **set operations**. Since events are sets of outcomes, these operations give us the tools to combine, compare, and manipulate events mathematically.

| Operation | Description | Formula |
| --- | --- | --- |
| **Empty set** | The impossible event with no outcomes | $\varnothing$ |
| **Union** | All the elements of set $A$ and all the elements of set $B$ | $A \cup B$ |
| **Intersection** | All the elements that are present in both $A$ and $B$ | $A \cap B$ |
| **Complement** | The event that $A$ does not occur | $A'$ |
| **Subset** | All elements of $A$ are also elements of $B$ | $A \subseteq B$ |
| **Cartesian product ($A \times B$)** | The set of all ordered pairs $(a,b)$ with $a$ in $A$ and $b$ in $B$ | $A \times B =$ {$(a,b) \mid a \in A \text{ and}\ b \in B$} |

## Theorems From Axioms & Set Operations
