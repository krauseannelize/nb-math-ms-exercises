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

>In a city, **2% of people have a rare genetic condition**. A genetic test correctly identifies those with the condition **98% of the time** but has a **3% false positive rate**. If a person tests positive, what is the probability they actually have the condition?

**_Prior probabilities:_**

Probability of having a genetic condition:

$P(G) = 0.02$

Probability of not having a genetic condition:

$P(\lnot G) = 0.98$

**_Conditional probabilities:_**

Probability of getting a positive test while having a genetic condition:

$P(T \mid G) = 0.98$

Probability of getting a positive test while not having a genetic condition:

$P(T \mid \lnot G) = 0.03$

**_Marginal probability:_**

Probability of getting positive test results regardless of the medical condition:

$P(T) = P(T \mid G) \cdot P(G) + P(T \mid \lnot G) \cdot P(\lnot G)$

$\quad \quad \quad = (0.98) \cdot (0.02) + (0.03) \cdot (0.98)$

$\quad \quad \quad = 0.0196 + 0.0294 = 0.049$

**_Posteriors (Bayes' Theorem):_**

Probability of actually having a genetic condition when receiving a positive test result:

$P(G \mid T) = \dfrac{P(G) \cdot P(T \mid G)}{P(T)} = \dfrac{0.02 \times 0.98}{0.049} = \dfrac{0.0196}{0.049} \approx 0.4$

So even with a positive test, the chance the person actually has the condition is only about $40\%$.

---

## Exercise 3

>The probability of **rain $R$** tomorrow is 90%, while the probability of **sunshine $S$** is 10%. If it rains, Sam has a 10% chance of going out to meet his friends. On a sunny day, there is an 80% chance that Sam will go out. What is the overall probability that Sam will **go out $G$** tomorrow?

**_Prior probabilities:_**

$P(R) = 0.90$  
$P(S) = 0.10$

**_Conditional probabilities:_**

Probability of going out when it rains:

$P(G \mid R) = 0.10$

Probability of going out when it is sunshine:

$P(G \mid S) = 0.80$

**_Marginal probability:_**

Probability that Sam goes out tomorrow considering the weather:

$P(G) = P(G \mid R) \cdot P(R) + P(G \mid S) \cdot P(S)$

$\quad \quad \quad = (0.10) \cdot (0.90) + (0.80) \cdot (0.10)$

$\quad \quad \quad = 0.09 + 0.08 = 0.17$

The overall probability that Sam goes out, accounting for the weather forecast and his behavior under each condition, is $0.17$ or $17\%$.

---

## Exercise 4

>A factory produces two types of light bulbs: LED and Incandescent.
>
>- 60% of the bulbs are **LED $L$**, and 40% are **Incandescent $I$**.
>- 5% of the LED bulbs are **defective $D$**, and 15% of the Incandescent bulbs are defective.
>
>You randomly pick a bulb, and it turns out to be defective. What is the probability that the defective bulb is LED?

**_Prior probabilities:_**

$P(L) = 0.60$  
$P(I) = 0.40$  

**_Conditional probabilities:_**

$P(D \mid L) = 0.05$  
$P(D \mid I) = 0.15$

**_Marginal probability:_**

Probability of being defective:

$P(D) = P(D \mid L) \cdot P(L) + P(D \mid I) \cdot P(I)$

$\quad \quad \quad = (0.05) \cdot (0.60) + (0.15) \cdot (0.40)$

$\quad \quad \quad = 0.03 + 0.06 = 0.09$

**_Posteriors (Bayes' Theorem):_**

Probability of being an LED given that it is defective:

$P(L \mid D) = \dfrac{P(L) \cdot P(D \mid L)}{P(D)} = \dfrac{0.60 \times 0.05}{0.09} = \dfrac{0.03}{0.09} \approx 0.33$

If a randomly chosen light bulb is defective, the probability that it is an LED is about $0.33$ or $33\%$.

---

## Exercise 5

> A **disease ($D$)** affects 1% of a population. A test correctly detects the disease 95% of the time, but 5% of healthy people also **test positive $T$**. If a person tests positive, what is the probability they actually have the disease?

**_Prior probabilities:_**

$P(D) = 0.01$  
$P(\lnot D) = 0.99$

**_Conditional probabilities:_**

Probability of getting a positive test while having the disease:

$P(T \mid D) = 0.95$

Probability of getting a positive test while not having the disease:

$P(T \mid \lnot D) = 0.05$

**_Marginal probability:_**

Probability of getting positive test results regardless of the disease:

$P(T) = P(T \mid D) \cdot P(D) + P(T \mid \lnot D) \cdot P(\lnot D)$

$\quad \quad \quad = (0.95) \cdot (0.01) + (0.05) \cdot (0.99)$

$\quad \quad \quad = 0.0095 + 0.0495 = 0.059$

**_Posteriors (Bayes' Theorem):_**

Probability of actually having the disease when receiving a positive test result:

$P(D \mid T) = \dfrac{P(D) \cdot P(T \mid D)}{P(T)} = \dfrac{0.01 \times 0.95}{0.059} = \dfrac{0.0095}{0.059} \approx 0.161$

If a person tests positive, the probability they actually have the disease is about $16\%$.

---

Proceed to next section: 

[(back to README)](/README.md)
