# Groups

## Overview

Groups are an incredibly powerful tool where you consider a set of elements connected by one or more binary operations. The beauty of groups is that, instead of using the operations directly, we abstract them away and use the theory of groups to find results. Provided an operation satisfies the **group axioms**, it doesn't matter how that operation is defined or how complicated it is - we can prove results using only the abstract concept of an operation (this will make more sense, I promise).

## Group Axioms

A group $$(G, \ast)$$ is a set $$G$$ with a binary operation that satisfies the following axioms:

* $$\ast$$ is [closed](set-operations.md#closure) on $$G$$
* $$\ast$$ is [associative ](set-operations.md#associativity)on $$G$$
* There is an **identity element** $$e \in G$$ such that $$\forall a \in G, e \ast a = a \ast e = a$$
* For every $$a \in G$$, there is an **inverse element** $$a^{-1} \in G$$ such that $$a \ast a^{-1} = a^{-1} \ast a = e$$

Note that groups do not need to be **commutative** - if a group _is_ commutative, it is called an **Abelian group**, named after [Niels Abel](https://en.wikipedia.org/wiki/Niels\_Henrik\_Abel).

### Group Example

We take the group $$(\Z_4, +)$$ where $$\Z_4 = \{0,1,2,3\}$$. This group is addition modulo 4, forming an abelian group of **order 4** (has 4 elements). We can write the complete addition table:

```
+ | 0 1 2 3
--|--------
0 | 0 1 2 3
1 | 1 2 3 0
2 | 2 3 0 1
3 | 3 0 1 2
```

This is clearly closed and has an identity element $$0$$. Every element $$a$$ also has an inverse $$a^{-1}$$ such that $$a + a^{-1}=0$$. The associativity and commutativity can be assumed based on the associativity and commutativity of general addition, meaning $$(\Z_4, \ast)$$ forms an **abelian group**.
