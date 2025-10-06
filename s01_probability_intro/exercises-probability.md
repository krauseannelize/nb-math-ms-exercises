# Exercises | Probability

## Exercise 1

A standard deck of playing cards has 52 cards, consisting of 4 suits (hearts, diamonds, clubs, and spades), each with 13 cards. Using the **classical approach**, calculate the probability of drawing:

$A$ | A heart from the deck.  
$B$ | A king from the deck.  
$C$ | A red card (either a heart or a diamond).  
$D$ | A face card (jack, queen, or king).  

### Solution | Event A

$P(A) = \dfrac{N(A)}{N(S)} = \dfrac{\text{Number of Hearts}}{\text{Number of cards in deck}} = \dfrac{13}{52} = 0.25$

### Solution | Event B

$P(B) = \dfrac{N(B)}{N(S)} = \dfrac{\text{1 King per Suit}}{\text{Number of cards in deck}} = \dfrac{4}{52} \approx 0.0769$

### Solution | Event C

$P(C) = \dfrac{N(C)}{N(S)} = \dfrac{\text{Number of red cards}}{\text{Number of cards in deck}} = \dfrac{26}{52} = 0.5$

### Solution | Event D

$P(D) = \dfrac{N(D)}{N(S)} = \dfrac{\text{3 Face cards per Suit}}{\text{Number of cards in deck}} = \dfrac{3 x 4}{52} = \dfrac{12}{52} \approx 0.2308$

---

## Exercise 2

There is a box containing 15 white, 10 red, and 5 black balls. One ball is drawn at random.  
Find the probability that it will be:  

$A$ | white  
$B$ | red  
$C$ | black  
$D$ | white or black  
$E$ | white and black  

### Solution | Event A
   
$P(A) = \dfrac{N(A)}{N(S)} = \dfrac{\text{Number of white balls}}{\text{Number of all balls}} =\dfrac{15}{15 + 10 + 5} = \dfrac{15}{30} = \dfrac{1}{2} = 0.5$

### Solution | Event B

$P(B) = \dfrac{N(B)}{N(S)} = \dfrac{\text{Number of red balls}}{\text{Number of all balls}} =\dfrac{10}{15 + 10 + 5} = \dfrac{10}{30} = \dfrac{1}{3} \approx 0.3333$

### Solution | Event C

$P(C) = \dfrac{N(C)}{N(S)} = \dfrac{\text{Number of black balls}}{\text{Number of all balls}} =\dfrac{5}{15 + 10 + 5} = \dfrac{5}{30} = \dfrac{1}{6} \approx 0.1667$

### Solution | Event D

_Note: Use additive principle for 2 distinct events that cannot happen simultaneously_

$P(D) = P(A) + P(C) = \dfrac{15}{30} + \dfrac{5}{30} = \dfrac{20}{30} = \dfrac{2}{3} \approx 0.667$

### Solution | Event E

One ball cannot be white and black, thus:

$P(E) = 0$ _(impossible event)_

---

## Exercise 3

An athlete takes 5 shots. The probability of hitting the target is 0.8. Find the probability that the athlete hits ($H$) the target the first three times and misses ($M$) the last two. Assume shots are independent from one another.

### Solution

$P(H) = 0.8$  
$P(M) = 1 - P(H) = 1 - 0.8 = 0.2$  

$A = H, H, H, M, M$

_Note: Use multiplication principle for sequential or independant events_

$P(A) = (0.8) \times (0.8) \times (0.8) \times (0.2) \times (0.2)$  
$P(A) = (0.8^3)(0.2^2)$  
$P(A) = (0.512)(0.04) = 0.02048$

The probability that the athlete hits the first three shots and misses the last two is **0.02048** (about 2.05%).

---

## Exercise 4

If 7% of the population smokes cigars, 28% of the population smokes cigarettes, and 5% of the population smokes both, what percentage of the population smokes neither cigars nor cigarettes?

### Solution

$A$ | Smoke cigars  ➡  $P(A) = 0.07$  
$B$ | Smoke cigarettes  ➡  $P(B) = 0.28$  
$A \cap B$ | Smoke both  ➡  $P(A \cap B) = 0.05$  
$C$ | Smoke neither  ➡  $P(C) = 1 - P(A \cup B)$  

Find the union of $P(A)$ and $P(B)$ accounting for the intersection $P(A \cap B):

$P(A \cup B) = P(A) + P(B) - P(A \cap B)$  
$P(A \cup B) = 0.07 + 0.28 - 0.05 = 0.30$

Use the complement rule to find the event that neither is smoked:

$P(C) = 1 - P(A \cup B)$  
$P(C) = 1 - 0.30 = 0.70$

70% of the population smokes neither cigars nor cigarettes.

---

Proceed to next section: [Counting Techniques](/s01_probability_intro/counting-techniques.md)

[(back to README)](/README.md)
