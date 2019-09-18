# Limits

## Learning Targets

You will be able to
- [ ] Evaluate limits graphically, numerically, and algebraically.

## Concepts / Definitions

### Informal definition of a limit
If $f(x)$ becomes arbitratily close to a single number $L$ as $x$ approaches a number $a$ from _either_ side, the limit of $f(x)$ as $x$ approaches $$ is $L$.

![Limit Definition](../assets/calculus/limits_1.png)

### Definition for a Limit using one-sided limits
$$\lim_{x\to a} f(x) = L\quad iff\quad \lim_{x\to a^-} f(x) = L = \lim_{x \to a^+} f(x)$$

Note: Technically, the theorem is based on a real number, $L$, but we include infinity as a possible answer.

![Input x approaches a](../assets/calculus/limits_2.jpg)


### Graphical Example
![Graphical Example](../assets/calculus/limits_3.jpg)

### Numerical Example
![Numerical Example](../assets/calculus/limits_4.jpg )

Numerically, we will have a limit _if it is clear we are approaching one output value_ as we look at values from inputs smaller and larger than $\alpha$.

### Analytic / Algebraic Example
$$\lim_{x\to 1}\frac{x^2-1}{x-1}$$
$$= \lim_{x\to 1}\frac{(x+1)(x-1)}{x-1}$$
$$= \lim_{x\to 1}(x+1)$$
$$= 2$$

Many times limits (not all), like the derivative, require us to find the output value of the hole of the difference quotient.

### Continuity at a Point

#### Interior Point
A function $y = f(x)$ is continuous at an interior point c of its domain if
$$\lim_{x\to c} f(x) = f(c)$$

#### Endpoint
A function $y = f(x)$ is continuous at a left endpoint $\alpha$ or is continuous at a right endpoint $b$ of its domain if
$$\lim_{x\to a^+} f(x) = f(a)\quad or\quad \lim_{x\to b^-} f(x) = f(b)\ respectively$$

### Intermediate Value Theorem for Continuous Functions

A function $y = f(x)$ that is continuous on a closed interval $[a, b]$ takes on every value between $f(a)$ and $f(b)$. In other words, if $y_0$ is between $f(a)$ and $f(b)$, then $y_0 = f(c)$ for some $c$ in $[a, b]$.

![Intermediate Value Theorem](../assets/calculus/limits_5.jpg)

#### Properties of Limits
Let $b$ and $c$ be real numbers, lef $n$ be a positive integer, and let $f$ and $g$ be functions with the following limits.

![Properties of Limits](../assets/calculus/limits_6.png)

Ex: Is any real number exactly 1 less than its cube?
