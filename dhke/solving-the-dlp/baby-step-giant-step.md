---
description: The simple iterative approach
---

# Baby Step, Giant Step

Baby Step, Giant Step is a very simple approach to solving the DLP often described as a **meet-in-the-middle algorithm**.

## Approach

Let us say that $$a^x \equiv b \mod p$$. First we choose an arbitrary number $$k$$, which defines how many iterations we try. Next we evaluate

$$
a, a^2, a^3, ..., a^{k-1}
$$

​Following that, we evaluate

$$
ba^{-k}, ba^{-2k}, ba^{-3k},...,ba^{-rk} \text{ 
 where } rk>p
$$

​If the DLP has a soultion, there will be at least one common value in **both lists**. If we let these common values be $$a^n$$ and $$ba^{-mk}$$, we can then solve it easily from there:

$$
a^n \equiv ba^{-mk} \mod p \\
a ^ {mk + n} \equiv b \mod p
$$

Solving the DLP! A few problems arise, however.

You will first notice that our choice of $$k$$ is arbitrary. If $$p$$ is large enough, this approach becomes completely infeasible, so using solely this algorithm is only effective when $$p$$ is small. After all, this is a very naive brute-force approach.
