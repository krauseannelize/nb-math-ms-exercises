# Exercises | Counting Techniques

## Table of Contents

1. [Full Permutations (no repetition)](#full-permutations-no-repetition)
2. [K-Permutations (no repetition)](#k-permutations-no-repetition)
3. [Combinations (no repetition)](#combinations-no-repetition)

## Full Permutations (no repetition)

### Exercise 1

What is the number of ways to line up 5 students for a class photo?

$P_n = P_5 = 5! = 120$

---

### Exercise 2

How many ways are there to shuffle the letters A, B and C?

$P_n = P_3 = 3! = 6$

---

### Exercise 3

A dance competition has 6 performers, and each must perform in a specific sequence. How many different performance orders are possible for all 6 performers?

$P_n = P_6 = 6! = 720$

---

### Exercise 4

In how many ways can a 5-letter password be formed using the letters A, B, C, D, E with no repetition?

$P_n = P_5 = 5! = 120$

---

### Exercise 5

A bag contains 6 different colored balls. How many ways can you draw and arrange all 6 balls in a line?

$P_n = P_6 = 6! = 720$

---

[(back to top)](#table-of-contents)

## K-Permutations (no repetition)

### Exercise 1

How many ways there are to create a password from letters A,B,C of a length 2?

$P(n,r) = \dfrac{n!}{(n-r)!}$  

$P(3,2) = \dfrac{3!}{(3-2)!} = \dfrac{3!}{1!} = \dfrac{3 \times 2 \times 1}{1} = \dfrac{6}{1} = 6$

---

### Exercise 2

Imagine you need to create a 4-character password using distinct digits from 0 to 9. In how many ways can you do it given that you can use each digit only once (no repetitions)?

$P(n,r) = \dfrac{n!}{(n-r)!}$  

$P(10,4) = \dfrac{10!}{(10-4)!} = \dfrac{10!}{6!} = 10 \times 9 \times 8 \times 7 = 5,040$

---

### Exercise 3

A school is electing a President, Vice President, and Secretary from 7 candidates. How many different ways can these positions be assigned?

$P(n,r) = \dfrac{n!}{(n-r)!}$  

$P(7,3) = \dfrac{7!}{(7-3)!} = \dfrac{7!}{4!} = \dfrac{7 \times \ 6 \times 5 \times 4 \times 3 \times \ 2 \times 1}{4 \times 3 \times \ 2 \times 1}$

$\quad \quad \quad = 7 \times \ 6 \times 5 = 210$

---

### Exercise 4

How many ways can 7 runners be arranged in a race where only the top 3 positions matter?

$P(n,r) = \dfrac{n!}{(n-r)!}$  

$P(7,3) = \dfrac{7!}{(7-3)!} = \dfrac{7!}{4!} = \dfrac{7 \times \ 6 \times 5 \times 4 \times 3 \times \ 2 \times 1}{4 \times 3 \times \ 2 \times 1}$

$\quad \quad \quad = 7 \times \ 6 \times 5 = 210$

---

[(back to top)](#table-of-contents)

## Combinations (no repetition)

### Exercise 1

Four friends have three movie tickets. In how many ways can a group of three friends be formed to go to the movies? The order in which the friends are chosen doesn't matter.

$C(n,r) = \dfrac{n!}{r!(n-r)!}$  

$C(4,3) = \dfrac{4!}{3!(4-3)!} = \dfrac{4!}{3! \cdot 1!}$

$\quad \quad \quad = \dfrac{4 \times 3 \times \ 2 \times 1}{(3 \times \ 2 \times 1)(1)} = \dfrac{4}{1} = 4$

---

### Exercise 2

A library has **7 different novels**, and you want to **borrow 4** of them to read over the summer. The order in which you choose the books doesn't matter.

$C(n,r) = \dfrac{n!}{r!(n-r)!}$  

$C(7,4) = \dfrac{7!}{4!(7-4)!} = \dfrac{7!}{4! \cdot 3!}$

$\quad \quad \quad = \dfrac{7 \times \ 6 \times 5 \times 4 \times 3 \times \ 2 \times 1}{(4 \times 3 \times \ 2 \times 1)(3 \times 2 \times 1)}$

$\quad \quad \quad = \dfrac{7 \times 6 \times 5}{3 \times 2 \times 1} = \dfrac{210}{6} = 35$

---

### Exercise 3

A bakery offers **8 different types of muffins**, and you want to buy a box of **3 different muffins** to share with friends. How many different combinations of 3 muffins can you choose?

$C(n,r) = \dfrac{n!}{r!(n-r)!}$  

$C(8,3) = \dfrac{8!}{3!(8-3)!} = \dfrac{8!}{3! \cdot 5!}$

$\quad \quad \quad = \dfrac{8 \times 7 \times \ 6 \times 5 \times 4 \times 3 \times \ 2 \times 1}{(3 \times \ 2 \times 1)(5 \times 4 \times 3 \times 2 \times 1)}$

$\quad \quad \quad = \dfrac{8 \times 7 \times 6}{3 \times 2 \times 1} = \dfrac{336}{6} = 56$

---

### Exercise 4

A committee of 4 members is to be formed from a group of 12 people. How many different ways can the committee be selected?

$C(n,r) = \dfrac{n!}{r!(n-r)!}$  

$C(12,4) = \dfrac{12!}{4!(12-4)!} = \dfrac{12!}{4! \cdot 8!}$

$\quad \quad \quad = \dfrac{12 \times 11 \times 10 \times 9 \times 8 \times 7 \times \ 6 \times 5 \times 4 \times 3 \times \ 2 \times 1}{(4 \times 3 \times \ 2 \times 1)(8 \times 7 \times 6 \times 5 \times 4 \times 3 \times 2 \times 1)}$

$\quad \quad \quad = \dfrac{12 \times 11 \times 10 \times 9}{4 \times 3 \times 2 \times 1} = \dfrac{11,880}{24} = 495$

---

### Exercise 5

A team of 4 people is to be chosen from a group of 10. How many different teams can be formed?

$C(n,r) = \dfrac{n!}{r!(n-r)!}$  

$C(10,4) = \dfrac{10!}{4!(10-4)!} = \dfrac{10!}{4! \cdot 6!}$

$\quad \quad \quad = \dfrac{10 \times 9 \times 8 \times 7 \times \ 6 \times 5 \times 4 \times 3 \times \ 2 \times 1}{(4 \times 3 \times \ 2 \times 1)(6 \times 5 \times 4 \times 3 \times 2 \times 1)}$

$\quad \quad \quad = \dfrac{10 \times 9 \times 8 \times 7}{4 \times 3 \times 2 \times 1} = \dfrac{5,040}{24} = 210$

---

### Exercise 6

From a deck of 52 cards, how many ways can you choose 5 cards for a hand in a card game?

$C(n,r) = \dfrac{n!}{r!(n-r)!}$  

$C(52,5) = \dfrac{52!}{5!(52-5)!} = \dfrac{52!}{5! \cdot 47!}$

$\quad \quad \quad = \dfrac{52 \times 51 \times 50 \times 49 \times 48}{5 \times 4 \times 3 \times 2 \times 1}$

$\quad \quad \quad = \dfrac{311,875,200}{120} = 2,598,960$

---

Proceed to next section: [Probability & Counting Exercises](/s01_probability_intro/exercises-probability-counting.md)

[(back to top)](#table-of-contents)  
[(back to README)](/README.md)
