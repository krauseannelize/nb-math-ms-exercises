# Probability Exercises

## Exercise 1

A standard deck of playing cards has 52 cards, consisting of 4 suits (hearts, diamonds, clubs, and spades), each with 13 cards. Using the **classical approach**, calculate the probability of drawing:

$A$ | A heart from the deck.  
$B$ | A king from the deck.  
$C$ | A red card (either a heart or a diamond).  
$D$ | A face card (jack, queen, or king).  

### Solution | Event A

$P(A) = \frac{N(A)}{N(S)} = \frac{\text{Number of Hearts}}{\text{Number of cards in deck}} = \frac{13}{52} = 0.25$

### Solution | Event B

$P(B) = \frac{N(B)}{N(S)} = \frac{\text{1 King per Suit}}{\text{Number of cards in deck}} = \frac{4}{52} \approx 0.0769$

### Solution | Event C

$P(C) = \frac{N(C)}{N(S)} = \frac{\text{Number of red cards}}{\text{Number of cards in deck}} = \frac{26}{52} = 0.5$

### Solution | Event D

$P(D) = \frac{N(D)}{N(S)} = \frac{\text{3 Face cards per Suit}}{\text{Number of cards in deck}} = \frac{3 x 4}{52} = \frac{12}{52} \approx 0.2308$

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
   
$P(A) = \frac{N(A)}{N(S)} = \frac{\text{Number of white balls}}{\text{Number of all balls}} =\frac{15}{15 + 10 + 5} = \frac{15}{30} = \frac{1}{2} = 0.5$

### Solution | Event B

$P(B) = \frac{N(B)}{N(S)} = \frac{\text{Number of red balls}}{\text{Number of all balls}} =\frac{10}{15 + 10 + 5} = \frac{10}{30} = \frac{1}{3} \approx 0.3333$

### Solution | Event C

$P(C) = \frac{N(C)}{N(S)} = \frac{\text{Number of black balls}}{\text{Number of all balls}} =\frac{5}{15 + 10 + 5} = \frac{5}{30} = \frac{1}{6} \approx 0.1667$

### Solution | Event D

_Note: Use additive principle for 2 distinct events that cannot happen simultaneously_

$P(D) = P(A) + P(C) = \frac{15}{30} + \frac{5}{30} = \frac{20}{30} = \frac{2}{3} \approx 0.667$

### ESolution | vent E

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
