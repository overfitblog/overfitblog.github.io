---
layout: article
mathjax: true
title: Loop Invariant
image: "/assets/images/covers/tim-johnson-Vwf8q3RzBRE-unsplash.jpg"
categories:
- DM
desc: While loop has structure like 
imagealt: Cover Image for article
---

*While loop* has structure like
```
while condition
	S
```
It is executed till condition becomes false.

*Loop Invariant* is an assertion that is true each time program segment $S$ is executed. 




















































































































































































































































































































































































































If $p$ is loop invariant then $(p \wedge condition)\{S\}p$ is true.





















































































































































































































































































































































































































$$




















































































































































































































































































































































































































\begin{align}
	(p \wedge condition)\{S\}p \\
	\hline \\
	\therefore p\{while\ condition\ S\}(\neg condition \wedge p)
\end{align}
$$





















































































































































































































































































































































































































This blog was published directly from my notes.
To check the source of my notes and images used in this blog, visit <a href="/credits.html" target="_blank">Credits</a>.

To read my notes, download this <a href="https://github.com/bovem/CS" target="blank">repository</a>.