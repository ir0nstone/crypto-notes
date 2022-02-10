# Set Operations

## Operation Types

Often in maths, we take two numbers $$a$$ and $$b$$ and perform an **operation** on the two. **Unary** operations only involve one number, for example calculating $$a^{-1}$$. **Binary** operations take two numbers, for example $$a \times b$$. The latter are especially interesting when it comes to Group Theory in Cryptography.

## Properties of Binary Operations

Binary operations may or may not have certain properties when applied to sets. We will define $$\ast$$ as the operation.

The symbol $$\forall$$ means _**for all**_, an example being $$\forall a \in \N, 2a = a + a$$ (for all $$a$$ in the natural numbers, $$2a$$ is equal to $$a + a$$).

The symbol $$\exists$$ means **there exists**.

### Closure

If the result of $$a \ast b$$ is within the original set, then the operation is **closed**. An example is multiplication in $$\N$$, as for any pair $$a,b$$ we can see that $$a \times b \in \N$$.

$$
\forall a,b \in \N, a \ast b \in \N
$$

### Commutativity

If changing the order of the element has no effect on the result, the operation is **commutative**.

$$
\forall a,b \in \N, a \ast b = b \ast a
$$

### Associativity

If the order of operations doesn't matter, the operation is **associative**.

$$
\forall a,b,c \in \N, (a \ast b) \ast c = a \ast (b \ast c)
$$

