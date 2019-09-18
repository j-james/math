{% include mathjax.html %}

# Squeeze Theorem

## Learning Targets

You should be able to
- [ ]

## Concepts / Definitions

### Limit of a Composite Function Theorem

If $f$ and $g$ are functions such that $\lim_{x\to c}g(x) = L$ and $\lim_{x\to L}f(x) = f(L)$, then
$$\lim_{x\to c}(f \circ g)(x) = \lim_{x\to c}f(g(x)) = f(\lim_{x\to c}g(x)) = f(L)$$

The limit of a composition is the composition of the limit, provided the outside function is continuous at the limit of the inside function.

### Squeeze Theorem

If $f(x) \leq h(x) \leq g(x)$ for all $x\neq c$ in some interval about $c$, and $\lim_{x\to c}g(x) = \lim_{x\to c}f(x) = L$ then
$$\lim_{x\to c}h(x) = L$$

![Image](../assets/calculus/squeeze-theorem-and-limit-of-composition-function.md)

## Assignment

  1. Evaluate $\lim_{x\to 1} \arcsin(\frac{1-\sqrt x}{1-x})$
  2. Show analytically that $\lim_{x\to 0}x^2\cos(\frac{1}{x^2}) = 0$
  3. Evaluate $\lim_{x\to 0}\frac{(x+2)^4}{x}$
  4. Show analytically that $\lim_{x\to\infty}\frac{\sin x}{x} = 0$
  5. For the graphs below, <!--TODO-->
  6. Functions $f$, $g$, and $h$ are twice-differentiable functions with $g(2) = h(2) = 4$. The line $y = 4 + \frac 23 (x-2)$ is tangent to both the graph of $g$ at $x=2$ and the graph of $h$ at $x=2$.<br>
   It is known that $g(x) \leq h(x)$ for $1 < x < 3$. Let $k$ be a function satisfying $g(x)\leq k(x)\leq h(x)$ for $1 < x < 3$. Is $k$ continuous at $x=2$? Justify your answer.
