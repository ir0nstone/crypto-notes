---
description: Using Continued Fractions to attack small e values
---

# Wiener's Attack

## Overview

Wiener's Attack utilises the convergents of the continued fraction expansion of $$\frac{k}{d}$$ to attempt to guess the decryption exponent $$d$$

## Thing

We can say that

$$
\phi(N) = (p-1)(q-1) \\
= pq - (p + q) + 1 \\
\approx N
$$

​We can also say that since $$ed \equiv 1 \mod \phi(N)$$​: we can rearrange this to say that $$ed = k\phi(N) + 1$$.

$$
d = k\phi(N) + 1 \\
ed - k\phi(N) = 1 \\
$$

