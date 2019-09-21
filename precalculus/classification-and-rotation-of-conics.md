{% include mathjax.html %}

# Classification and Rotation of Conics

## Learning Targets

You should be able to
- [ ] Classify conics
- [ ] Find angle of rotation
- [ ] Write in its transformed form to eliminate the $xy$ term
- [ ] Graph the transformed conic

![Graph the Transformed Conic](../assets/precalculus/classification-and-rotation-of-conics_1.gif)

## Concepts / Definitions

### Classification of Conics

#### The graph of $Ax^2 + Cy^2 + Dx + Ey + F = 0$
If $A = C$ - circle<br>
If $AC = 0$ - parabola<br>
If $AC > 0$ - ellipse<br>
If $AC < 0$ - hyperbola

#### Using the discriminant = $B^2 - 4AC$<br>
If $B^2 - 4AC < 0$ - ellipse or circle<br>
If $B^2 - 4AC = 0$ - parabola<br>
If $B^2 - 4AC > 0$ - hyperbola

### Rewriting Conics in transformed form

$Ax^2 + Bxy + Cy^2 + Dx + Ey + F = 0$ can be written as $A'x'^2 + C'y'^2 + D'x' + E'y' + F' = 0$ by rotating the axis through an angle $\theta$, where
$$\cot{2\theta} = (\frac{A-C}{B})$$

![Rotated Axis](../assets/precalculus/classification-and-rotation-of-conics_2.svg)

The coefficients of the new equation are obtained by making the following substitutions.<br>
$$ x = x' \cos{\theta} - y' \sin{\theta}\ and\ y = x' \sin{\theta} + y' \cos{\theta}$$
