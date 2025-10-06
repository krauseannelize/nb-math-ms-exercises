# Counting Techniques

**Counting techniques** provide systematic methods to determine how many outcomes are possible in a given situation, ensuring we neither overlook possibilities nor double‑count them.

| Technique | Description | Formula |
| --- | --- | --- |
| **Additive Principle (Rule of Sum)** | When a task can be done in $m$ ways or $n$ ways, two distinct events that cannot happen simultaneously (mutually exclusive) | $m + n$ |
| **Multiplicative Principle (Rule of Product)** | When a task can be done in $m$ ways and another sequential or independent task in $n$ ways | $m \times n$ |
| **Full Permutations (no repetition)** | _Order matters_ - All $n$ distinct objects | $P_n = n \times (n - 1) \times (n - 2) \dots \times 1 = n!$ |
| **K‑Permutations (no repetition)** | _Order matters_ - $r$ distinct objects chosen from $n$ | $P(n,r) = \frac{n!}{(n-r)!}$ |
| **K-Permutations (with repetition)** | _Order matters_ - $r$ objects chosen from $n$ with repetition | $n^r$ |
| **Combinations (no repetition)** | _Order doesn't matter_ - $r$ distinct objects chosen from $n$ | $C(n,r) = \frac{n!}{r!(n-r)!}$ |

---

## Example | Rule of Sum

You can pick 1 snack. There are 3 types of fruit (apple, banana, orange) and 2 types of granola bars. The total number of ways to make a choice is:

$3 + 2 = 5$

---

## Example | Rule of Product

Pick 1 outfit. You have 4 shirts and 3 pairs of pants. The total number of combinations is:

$4 \times 3 = 12 \text{ outfits}$

---

## Example | Rules of Sum and Product

Imagine a school event where students can choose between participating in a science fair or a sports competition. There are 5 science fair categories and 4 sports activities. Additionally, each participant must choose one of 3 available T-shirt colors for the event.
How many combinations are there for choosing an activity and a T-shirt?

Choosing an activity:  $5 + 4 = 9$ choices  
Choosing an activity and a t-shirt color:  $9 \times 3 = 27$ choices  

---

## Example | Full Permutations (no repetition)

You have 4 different books and you want to arrange them on a shelf. The total number of ways to arrange the books is:

$P_4 = 4! = 4 \times 3 \times 2 \times 1 = 24$

---

## Example | K-Permutations (no repetition)

8 students compete for gold, silver, and bronze medals. How many possible ways can the medal winners be arranged?

Students competing:  $n = 8$  
Positions to fill:  $r = 3$  

$P(n,r) = \dfrac{n!}{(n-r)!}$

$P(8,3) = \dfrac{8!}{(8-3)!} = \dfrac{8!}{5!} = \dfrac{8 \times 7 \times 6 \times 5 \times 4 \times 3 \times 2 \times 1}{5 \times 4 \times 3 \times 2 \times 1} = 8 \times 7 \times 6 = 336$

The common $5 \times 4 \times 3 \times 2 \times 1$ is cancelled.

---

## Example | K-Permutations (with repetition)

Calculate the 4‑digit PIN combinations from 10 digits, where repeats are allowed.

$n^r = 10^4 = 10,000$

---

## Example | Combinations (no repetition)

You have a basket containing 5 different types of fruits. How many ways can you choose 3 types of fruit from the basket when order doesn't matter?

$C(n,r) = \dfrac{n!}{r!(n-r)!}$

$C(5,3) = \dfrac{5!}{3!(5-3)!} = \dfrac{5!}{3! \cdot 2!} = \dfrac{5 \times 4 \times 3 \times \ 2 \times 1}{(3 \times \ 2 \times 1)(2 \times 1)} = \dfrac{5 \times 4}{2 \times 1} = \dfrac{20}{2} = 10$

---

Proceed to next section: [Counting Technique Exercises](/s01_probability_intro/exercises-counting-techniques.md)

[(back to README)](/README.md)
