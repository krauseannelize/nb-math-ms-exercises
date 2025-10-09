# Exercises | Bayes' Theorem

## Exercise 1

> Suppose a factory has three machines: **Machine A**, **Machine B**, and **Machine C**. These machines produce a total of 10,000 items daily, with the following production rates and defect rates:
>
>- **Machine $A$** produces 4,000 items per day, with a defect rate of 1%.
>- **Machine $B$** produces 3,000 items per day, with a defect rate of 2%.
>- **Machine $C$** produces 3,000 items per day, with a defect rate of 3%.
>
> If an item is randomly selected and found to be **defective $D$**, what is the probability it was produced by each machine?

**_Prior probabilities:_**

Probabilities of selecting an item from each machine are:

$P(A) = \dfrac{4000}{10000} = 0.40$

$P(B) = \dfrac{3000}{10000} = 0.30$

$P(C) = \dfrac{3000}{10000} = 0.30$

**_Conditional probabilities:_**

Probability of selecting a defected item for each machine:

$P(D \mid A) = 0.01$

$P(D \mid B) = 0.02$

$P(D \mid C) = 0.03$

**_Marginal probability:_**

Probability of selecting a defective item:

$P(D) = P(D \mid A) \cdot P(A) + P(D \mid B) \cdot P(B) + P(D \mid C) \cdot P(C)$

$\quad \quad \quad = (0.01) \cdot (0.40) + (0.02) \cdot (0.30) + (0.03) \cdot (0.30)$

$\quad \quad \quad = 0.004 + 0.006 + 0.009 = 0.019$

There is a $1.9\%$ chance of getting a defective item regardless of the machine.

**_Posteriors (Bayes' Theorem):_**

Probability of each machine producing a defective item:

$P(A \mid D) = \dfrac{P(A) \cdot P(D \mid A)}{P(D)} = \dfrac{0.40 \times 0.01}{0.019} = \dfrac{0.004}{0.019} \approx 0.21$

$P(B \mid D) = \dfrac{P(B) \cdot P(D \mid B)}{P(D)} = \dfrac{0.30 \times 0.02}{0.019} = \dfrac{0.006}{0.019} \approx 0.32$

$P(C \mid D) = \dfrac{P(C) \cdot P(D \mid C)}{P(D)} = \dfrac{0.30 \times 0.03}{0.019} = \dfrac{0.009}{0.019} \approx 0.47$

The defective item is most likely to have been produced by **Machine C** with a probability of $4.7\%$.

---

## Exercise 2

---

Proceed to next section: 

[(back to README)](/README.md)
