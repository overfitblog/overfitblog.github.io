---
layout: article
mathjax: true
title: Monte Carlo Algorithms
image: "/assets/images/img_test.jpg"
categories:
- DM
desc: Monte Carlo Algorithms give answers to Decision Problems. There is some probability that these answers are incorrect but it decreases as algorithm does more computations. 
imagealt: 
---

Monte Carlo Algorithms give answers to [Decision Problems]({% post_url 2021-06-20-decision-problems %}). There is some probability that these answers are incorrect but it decreases as algorithm does more computations.

At each step of these algorithms there are tests that have outputs as either "true" or "unknown". 
If correct answer is "false" then algorithm will answer "false" (because all tests will output "unknown") but if correct answer is "true" the algorithm can answer either "true" or "false". 
The probability of correct answers increases as number of tests increases.

Let $p$ be the probability that a test responds as "true" when correct answer is "true".

































































































































































































































































































































































Then $1-p$ is the probability that a test responds as "unknown" when correct answer is "true".

































































































































































































































































































































































So algorithm will answer "false" only when all $n$ test respond as "unknown" i.e. $({1-p})^n$.

































































































































































































































































































































































If $p \neq 0$ the probability of "false" response approaches 0 as $n$ increases and opposite probability approaches 1.




































































































































































































































































































































































This blog was published directly from my notes.
To check the source of my notes visit [Sources](sources.html).
To see all of my notes download/clone this [repository](https://github.com/bovem/CS).