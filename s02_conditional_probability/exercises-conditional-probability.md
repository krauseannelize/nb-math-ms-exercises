# Exercises | Conditional Probability

## Exercise 1

A box contains 6 white balls and 4 red balls. We randomly (and without replacement) draw two balls from the box. What is the probability that the second ball selected is red, given that the first ball selected is white?

$A$ | First ball is white  
$B$ | Second ball is red

$P(A) = \dfrac{6}{10}$   

$P(B \mid A) = \dfrac{4}{9}$  

$P(A \cap B) = P(A) \times P(B \mid A) = \dfrac{6}{10} \times \dfrac{4}{9} = \dfrac{6 \times 4}{10 \times 9} = \dfrac{24}{90} = \dfrac{4}{15}$

$P(B \mid A) = \dfrac{P(A \cap B)}{P(A)} = \dfrac{4}{15} \div \dfrac{6}{10} = \dfrac{4}{15} \times \dfrac{10}{6} = \dfrac{4 \times 10}{15 \times 6} = \dfrac{40}{90} = \dfrac{4}{9}$

The probability of taking out a red ball after a blue one has been taken out is $\dfrac{4}{9}$ or 0.44.

---

## Exercise 2

What is the probability that two cards drawn from a 36-card deck belong to the same suit?

$A$ | First card from suit X  
$B$ | Second card also from suit X

$P(A) = \dfrac{9}{36} = \dfrac{1}{4}$   

$P(B \mid A) = \dfrac{8}{35}$  

$P(A \cap B) = P(A) \times P(B \mid A) = \dfrac{1}{4} \times \dfrac{8}{35} = \dfrac{1 \times 8}{4 \times 35} = \dfrac{8}{140} = \dfrac{2}{35}$

$P(B \mid A) = \dfrac{P(A \cap B)}{P(A)} = \dfrac{2}{35} \div \dfrac{1}{4} = \dfrac{2}{35} \times \dfrac{4}{1} = \dfrac{2 \times 4}{35 \times 1} = \dfrac{8}{35}$

The probability of taking out a red ball after a blue one has been taken out is $\dfrac{8}{35}$ or 0.23.

---

## Exercise 3

A drawer contains 6 black socks and 4 white socks. Two socks are drawn randomly, one after the other without replacement.

1. What is the probability that the first sock is black and the second sock is also black?
2. Use the multiplication rule to calculate the joint probability of both events.

**Solution 1**

$A$ | First sock is black  
$B$ | Second sock is black

$P(A) = \dfrac{6}{10} = \dfrac{3}{5} = 0.60$   

$P(B \mid A) = \dfrac{5}{9} \approx 0.56$

**Solution 2**

$P(A \cap B) = P(A) \times P(B \mid A) = \dfrac{3}{5} \times \dfrac{5}{9} = \dfrac{3 \times 5}{5 \times 9} = \dfrac{15}{45} = \dfrac{1}{3} \approx 0.34$

---

## Exercise 4

A bag contains 5 red, 3 blue, and 2 green marbles. If a marble is drawn and is known to be not red, what is the probability that it is blue?

$A$ | First marble is blue  
$B$ | First marble is not red

$P(A) = \dfrac{3}{10}$  

$P(B) = \dfrac{5}{10} = \dfrac{1}{2}$  

$P(B \mid A) = 1 \quad$ _(If blue (A), then it is automatically not red (B))_

$P(A \cap B) = P(A) \times P(B \mid A) = \dfrac{3}{10} \times 1 = \dfrac{3}{10}$

$P(A \mid B) = \dfrac{P(A \cap B)}{P(B)} = \dfrac{3}{10} \div \dfrac{1}{2} = \dfrac{3}{10} \times \dfrac{2}{1} = \dfrac{3 \times 2}{10 \times 1} = \dfrac{6}{10} = \dfrac{3}{5}$

---

## Exercise 5

A company has 60 employees, 20 of whom are in management. If a randomly selected employee is in a meeting and 15 managers are currently in meetings while 25 non-managers are also in meeting, what is the probability that the employee is a manager?

---

## Exercise 6

A factory produces 100 lightbulbs, of which 10 are defective. Two lightbulbs are selected randomly, one after the other without replacement.

1. What is the probability that the first lightbulb selected is defective and the second lightbulb is not defective?
2. Use the multiplication rule to calculate the joint probability of these two events.

---
