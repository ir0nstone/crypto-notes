---
description: An introduction to the fundamentals
---

# Modular Arithmetic

Modular Arithmetic is an incredibly important aspect of practically all asymmetric cryptography. A common way to refer to it is as **clock arithmetic** - imagine it's eleven o'clock right now. Three hours later it'll be two o'clock, right? Well we do the same thing in modular arithmetic:

$$
11 + 3 = 14 \equiv 2 \mod 12
$$

​Essentially we take the sum of $$11$$ and $$3$$ and then divide by $$12$$ and keep the remainder. Here, the $$12$$ is called the **modulus**. The triple equals $$\equiv$$ denotes a _congruence_, and we say $$14$$ is congruent to $$2$$ $$\mod 12$$.

We can think of this another way and say that two numbers $$a$$ and $$b$$ are congruent modulo $$m$$ if their difference $$a-b$$ is divisible by $$m$$. For example, $$26$$ and $$2$$ are congruent modulo $$12$$ because  $$26-2=24$$ which is divisible by $$12$$.
