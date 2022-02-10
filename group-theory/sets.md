---
description: An Overview of Sets
---

# Sets

## Set Overview

A **set** is a collection of **elements**. When defining a set, we often use curly braces $$S = \{\dots\}$$.  The number of elements in a set is denoted $$\left| S \right|$$ or $$n(S)$$. We can say an element $$a$$ is a **member** of the set $$S$$ by saying $$a \in S$$. Note that a set has **no repeating elements**.

Common sets have their own symbols:

$$\N$$ - the set of **natural numbers** (there is no agreement on whether this contains $$0$$ or not)

$$\mathbb{Z}$$ - the set of **integers**

$$\mathbb{Q}$$ - the set of **rational numbers**

$$\mathbb{R}$$ - the set of **real numbers**

$$\mathbb{C}$$ - the set of **complex numbers**

## Set-Builder Notation

This notation allows us to easily define sets. For example, if we wanted to define a set with all multiple of 3 up to 30, we could do the following:

$$
S = \{ x : x = 3k, k \in \N, x \leq 30 \}
$$

## Set Rules

Assuming we have two sets $$A$$ and $$B$$, we have a way to interact with them.

### Equality

We say $$A = B$$ if both sets have the exact same elements.

### The Universal Set

The set $$U$$ contains all elements of interest.

### Union

The union of two sets $$A \cup B$$ is a combination set of all elements in $$A$$ or $$B$$.

### Intersection

The intersection of two sets $$A \cap B$$ is a set of all elements that appear in **both** $$A$$ and $$B$$.

### Set-Difference

The set-difference of $$A$$ and $$B$$ is the set of all elements in $$A$$ not in $$B$$.

$$
A \setminus B = \{ a \in A : a \not \in B\}
$$

### Complement

The complement of $$A$$, denoted $$A^\prime$$,  is all elements of $$U$$ not in $$A$$. You can think of it as $$U \setminus A$$.

### Subset

If all elements of $$A$$ are also elements of $$B$$, then $$A$$ is a subset of $$B$$ and this is denoted $$A \subseteq B$$. Note that means it **is possible that** $$A = B$$. To discount this possibility, we say $$A$$ is a **proper subset** of $$B$$, denoted $$A \subset B$$.
