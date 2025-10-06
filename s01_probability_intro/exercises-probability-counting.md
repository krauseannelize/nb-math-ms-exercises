# Exercises | Probability & Counting Techniques

## Exercise 1

A security system uses a 5-digit passcode, where each digit is unique and chosen from the numbers 0–9. What is the probability that a randomly generated passcode is 12345?

$P(n,r) = \dfrac{n!}{(n-r)!}$  

$P(10,5) = \dfrac{10!}{(10-5)!} = \dfrac{10!}{5!}$

$\quad \quad \quad = \dfrac{10 \times 9 \times 8 \times 7 \times \ 6 \times 5 \times 4 \times 3 \times \ 2 \times 1}{5 \times 4 \times 3 \times \ 2 \times 1}$

$\quad \quad \quad = 10 \times 9 \times 8 \times 7 \times 6 = 30,240$

There are 30,240 possible arrangements of the passcode. The probability of event $A$ being the passcode 12345:

$P(A) = \dfrac{N(A)}{N(S)} = \dfrac{1}{30,240}$

---

## Exercise 2

There are 10 people participating in a raffle where the first, second, and third prizes are awarded. What is the probability that Anna, Ben, and Charlie win the first, second, and third prizes in that exact order?

$P(n,r) = \dfrac{n!}{(n-r)!}$  
$P(10,3) = \dfrac{10!}{(10-3)!} = \dfrac{10!}{7!}$

$\quad \quad \quad = \dfrac{10 \times 9 \times 8 \times 7 \times \ 6 \times 5 \times 4 \times 3 \times \ 2 \times 1}{7 \times 6 \times 5 \times 4 \times 3 \times \ 2 \times 1}$

$\quad \quad \quad = 10 \times 9 \times 8 = 750$

There are 720 possible options to arrange the prizes. The probabitliy of event $A$ being Anna, Ben, and Charlie win the first, second, and third:

$P(A) = \dfrac{N(A)}{N(S)} = \dfrac{1}{720}$

---

Proceed to next section: [Conditional Probability](/s02_conditional_probability/conditional-probability.md)

[(back to README)](/README.md)
