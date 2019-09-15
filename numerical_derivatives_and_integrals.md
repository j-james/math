{% include mathjax.html %}

# More on Limits and calculating Numerical Derivatives / Integrals

## Learning Targets:

You should be able to
- Evaluate limits algebraically and numerically, with and without calculator
- Numerically calculate derivatives and integrals using `nDeriv` and `fnInt` on calculator

## Concepts / Definitions

### Limit Theorem

| $\lim_{x \to a} f(x) = L$ | $\iff$ | $\lim_{x \to a^+} f(x) = \lim_{x \to a^-} f(x) = L$ |
|---|---|---|

### Sine and Cosine Limit Laws

| $\lim_{x \to 0} \frac{sinx}{x} = 1$ | $\lim_{x \to 0} \frac{cosx - 1}{x} = 0$ |
|---|---|

### Derivative and Integral button

#### From Graphing Screen

- Graph $f(x)$,
- $2^{nd}$ `trace` (`calc`)
- 6: $dy/dx$
- 7: $\int f(x) dx$

#### From Main Screen

- `math`
- 8: $nDeriv(f(x), x, x_a)$
- 9: $fnInt(f(x), x, a, b)$

## X limit theorem

If $r > 0$ **is a rational number**, then

$$\lim_{x \to \pm \infin} \frac{1}{x^r} = 0$$

&nbsp;

Suppose we want to answer a limit question, and when _we "plug in" the limit value, this is what we get.
So, what would they equal?

$$\lim_{\infin \to \infin}$$

| | | |
|---|---|---|
| $0^\infin = ???$ | $\frac{0}{0} = indeterminate$ |$\frac{\infin}{\infin} = indeterminate$ |
| $0^0 = indeterminate$ | $\frac{some \space number}{\infin} = 0$ | $\infin - \infin = indeterminate$ |
| $\infin^0 = indeterminate$ | $\frac{\infin}{some \space number} = \pm \infin$ | $(0)(\infin) = indeterminate$ |
| $1^\infin = indeterminate$ | $\frac{some \space number}{0} = indeterminate$ |

__undefined__: impossible to tell (note that without context, many here are undefined)

__indeterminate__: we'll find out

## Examples

### Given $f(x) = \frac{5x}{x-3}$ find the following (no calc)

- $\lim_{x \to 3^-} f(x) =$ $-\infin$
- $\lim_{x \to 3^-} f(x) =$ $\infin$
- $\lim_{x \to 3} f(x) =$ $Does \space Not \space Exist$

### Evaluate $\lim_{h \to 0} \frac{\sqrt{9+h} - 3}{h}$ algebraically

1) $(\lim_{h\to0} \frac{\sqrt{9+h}-3}{h}) (\lim_{h\to0}\frac{\sqrt{9+h}+3}{\sqrt{9+h}+3})$
2) $\lim_{h\to0}\frac{9+h-9}{h(\sqrt{9+h}+3)}$
3) $\lim_{h\to0}\frac{h}{h(\sqrt{9+h}+3)}$
4) $\lim_{h\to0}\frac{1}{\sqrt{9+h}+3}$
5) $\frac{1}{\sqrt{9+0}+3}=\frac{1}{\sqrt{9}+3}=\frac{1}{3+3}=\frac{1}{6}$

### Evaluate $\lim_{x\to\infin}\frac{5x^2+2}{2x-3x^2}$ algebraically using limit laws and theorems

1) $(\lim_{x\to\infin}\frac{5x^2+2}{2x-3x^2})(\lim_{x\to\infin}\frac{\frac{1}{x^2}}{\frac{1}{x^2}})$
2) $\frac{\lim_{x\to\infin}5+2\lim_{x\to\infin}\frac{1}{x^2}}{2\lim_{x\to\infin}\frac{1}{x}-3\lim_{x\to\infin}1}$
3) $\frac{5+2(0)}{2(0)-3(1)}$
4) $-\frac{5}{3}$

## Exercises

1) Use the calculator `nDeriv` button to calculate the derivative of $f(x)=3x^2+2$ at $x=-2$
2) Use the calculator `fnInt` button to calculate $\int_{0}^{2}3x^2+2\space dx$
3) A truck is driven at a variable rate for 3 hours so that its velocity is given by $v(t)=35-12\cos(4t)$ miles per hour. How far deos the truck travel during its first 3 hours? (Use calculator to solve)
4) Evaluate (no calc)

    a) $\lim_{x\to0^+}\frac{x-2}{x^2}$

    b) $\lim_{x\to0^-}\frac{x-2}{x^2}$

    c) $\lim_{x\to0}\frac{x-2}{x^2}$

5)  Evaluate (no calc, show steps)

$$\lim_{x\to3}\frac{x^2-9}{x^2+2x-15}$$

6) Evaluate (no calc, show steps with limit laws)

$$\lim_{x\to0}\frac{\sin x}{\sin\pi x}$$

7) Evaluate (no calc)

$$\lim_{x\to\infin}\arctan x$$

8) Evaluate (no calc)

$$\lim_{x\to2}\frac{|2-x|}{2-x}$$

9) Evaluate (no calc)

$$\lim_{x\to\infin}x^{25}e^{-x}$$

10) Evaluate (algebraically, with limit laws)

$$\lim_{x\to\infin}\frac{2x-1}{2-3x-5x^2}$$

11) Evaluate (no calc)

$$\lim_{y\to1}\sqrt{y-1}$$

12) Evaluate (calc okay)

$$\lim_{x\to0}\sin{\frac{\pi}{x}}$$

13) Evaluate (no calc, show steps)

$$\lim_{x\to5}\frac{\sqrt x-\sqrt 5}{x-5}$$

14) Evaluate (no calc, show steps)

$$\lim_{x\to5}\csc{\frac{\pi x}{4}}$$

15) Evaluate (no calc)

$$\lim_{x\to-\infin}\frac{x-100}{\sqrt{x^2+100}}$$

16) Evaluate (algebraically)

$$\lim_{h\to0}\frac{(3+h)^{-1}-3^{-1}}{h}$$

17) Evaluate (no calc)

$$\lim_{x\to0}\frac{x\cos h-x}{h}$$

18) Evaluate (algebraically)

$$\lim_{u\to2}\frac{\sqrt{4u+1}-3}{u-2}$$

19) Evaluate (no calc, show steps)

$$\lim_{x\to\infin}\frac{2x^5-2x^3+18}{x^4+3x^3-x+2}-2x$$

20) Evaluate (no calc, show steps)

$$\lim_{\theta\to\infin}\theta\sin{\frac{\pi}{\theta}}$$

21) Evaluate (no calc, show steps)

$$\lim_{y\to0}(\csc y-\cot y)$$

22) Evaluate (no calc, show steps)

$$\lim_{x\to\infin}x^{\frac{1}{x}}$$
