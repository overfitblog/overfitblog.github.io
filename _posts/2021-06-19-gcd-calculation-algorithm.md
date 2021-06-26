---
layout: article
mathjax: true
title: GCD Calculation Algorithm
image: "/assets/images/img_test.jpg"
categories:
- DM
desc: Calculation of Greatest Common Divisor (GCD) of two integers $a$ and $b$ could be reduced to $\gcd(b\ mod\ a, a)$. 
imagealt: 
---

Calculation of [Greatest Common Divisor (GCD)]({% post_url 2021-06-14-greatest-common-divisor-(gcd) %}) of two integers $a$ and $b$ could be reduced to $\gcd(b\ mod\ a, a)$.

































































































































































































































































































































































This is a recursive implementation of [Euclidean Algorithm]({% post_url 2021-06-19-euclidean-algorithm %}).

```
gcd(a, b):
	if(a>0 and b>0 and a<b):
		if (a==0):
			return b
		else:
			return gcd(b mod a, a)
```



This blog was published directly from my notes.
To check the source of my notes visit [Sources](sources.html).
To see all of my notes download/clone this [repository](https://github.com/bovem/CS).