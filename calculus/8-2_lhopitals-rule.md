---
layout: default
---

# 8-2 L'Hopital's Rule

## Learning Targets

You will be able to
- [ ] Identify indeterminate forms
- [ ] Calculate limits using L'Hopital's rule


## Concepts / Definitions

How do we algebraically calculate $\lim_{x\to 1} \frac{\ln x}{x-1}$?

In the past, we've _looked at the graph_.

Recall previous methods for calculating limits.

- Plugging in a value (may be continuous, in this case not)
- Simplify / Factor / Cancel
- Multiply conjugates / Rationalize numerator
- Check if it's "top heavy" or "bottom heavy" - divide by the highest power for polynomials

Comparing two points

### L'Hopital's Rule

L'Hopital's rule is used for **calculating limits of the form $\frac 00$ or $\frac \infty\infty$.**

Suppose that $f(a) = g(a) = 0$, and that $f$ and $g$ are differentiable on an open interval $I$ containing $a$, and that $g'(x) \neq 0$ on $I$ if $x \neq a$. Then, if the limit below exists,

$$\lim_{x\to a} \frac{f(x)}{g(x)} = \lim_{x\to a} \frac{f'(x)}{g'(x)}$$

### Deriving L'Hopital's Rule

If you look _very_ closely at the graph (zoom in!), the equation on either side of the graph looks linear.

#### Algebraically

$\lim_{x\to a} = \frac{f(x)}{g(x)}$

$\lim_{x\to a} = \frac{f(x)-0}{g(x)-0}$

$\lim_{x\to a} = \frac{f(x)-f(a)}{g(x)-g(a)}$

$\lim_{x\to a} = \frac{\frac{f(x)-f(a)}{x-a}}{\frac{g(x)-g(a)}{x-a}}$

$\lim_{x\to a} = \frac{f'(a)}{g'(a)}$

## Examples

### Determine $\lim_{x\to\infty} (x\sin\frac 1x)$



### Determine $\lim_{x\to 0} (\cot x + \frac 1x)$

$\lim_{x\to 0} (\frac{\cos x}{\sin x} + \frac 1x)$

$\lim_{x\to 0} (\frac{\cos x}{\sin x} \frac{\sin x}{x} + \frac 1x)$

$\lim_{x\to 0} (\frac{\cos x}{x} + \frac 1x)$

$\lim_{x\to 0} (\frac{\cos x + 1}{x})$

$0$

OR

<!--TODO-->
