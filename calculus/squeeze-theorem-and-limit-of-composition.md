# Squeeze Theorem and Limit of Composition

## Learning Targets

You should be able to
- [ ] Evaluate limits of composition functions
- [ ] Use Squeeze Theorem to find limits

## Concepts / Definitions

### Limit Properties

Property | Description
---|---
$\lim_{x\to 0}c = c$ | The limit of a constant is equal to the constant.
$\lim_{x\to a}x = a$ | The limit of $x$ as it approaches $a$ is equal to $a$.
$\lim_{x\to 0}[f(x) + g(x)] = \lim_{x\to 0} f(x) + \lim_{x\to 0} g(x)$ | The limit of a sum is the sum of the limits.
$\lim_{x\to 0}[f(x) - g(x)] = \lim_{x\to 0}f(x) - \lim_{x\to 0}g(x)$ | The limit of a difference is the difference of limits.
$\lim_{x\to 0}[cf(x)] = c\lim_{x\to 0}f(x)$ | The limit of a constant times a function is the constant times the limit of the function.
$\lim_{x\to 0}[f(x)g(x)] = \lim_{x\to 0}f(x)\lim_{x\to 0}g(x)$ | The limit of a product is the product of the limits.
$\lim_{x\to 0}\frac{f(x)}{g(x)} = \frac{\lim_{x\to 0}f(x)}{\lim_{x\to 0}g(x)}$, provided $\lim_{x\to 0}g(x) = 0$ | The limit of a quotient is the quotient of the limits, provided that the denominator does not equal zero.
$\lim_{x\to 0}[f(x)]^n = (\lim_{x\to 0}f(x))^n$, where $a$ is a rational number | The limit of a power is the power of the limit, provided that the exponent is a rational number.
$\lim_{x\to 0}\sqrt[n]{f(x)} = \sqrt[n]{\lim_{x\to 0}f(x)}$, if the root on the right side exists | The limit of a root is the root of the limit, provided that the root exists.

### Limit of a Composite Function Theoreme

If $f$ anf $g$ are functions such that $$ and $$, then
$$\lim_{x\to c}(f \circ g)(x) = \lim_{x\to c}f(g(x)) = f(\lim_{x\to c}g(x)) = f(L)$$

### Proving the limit of $\frac{\sin x}{x}$

We know by comparing rates and / or looking at the graph that $\lim_{\theta \to 0}\frac{\sin \theta}{\theta} = 1$. How do we prove it? (L'Hospital not born yet)

