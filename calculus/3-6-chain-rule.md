{% include mathjax.html %}

# Chain Rule

## Learning Targets

You will be able to
- [ ] Differentiate composite functions using the chain rule
- [ ] ~~Find slopes of parametric functions~~

![Image of a Chain](../assets/calculus/chain-rule_1.jpg)

## The Chain Rule

If $f$ is differentiable at the point $u=g(x)$ and $g$ is differentiable at $x$, then the composite function $(f\circ g)(x) = f(g(x))$ is differentiable at $x$.

#### Newton Notation
$$(f\circ g)'(x) = f'(g(x)) \bullet g'(x)$$

#### Liebniz
If $y = f(u)$ and $u = g(x)$, then
$$\frac{dy}{dx}=\frac{dy}{du}\bullet\frac{du}{dx}$$

#### In words
The derivative of the outside function evaluated at the inner function times the derivative of the inside function.
