To prove that the maximum range is achieved at a launch angle of $45^\circ$, we will use the horizontal range formula and apply basic calculus (optimization) to find where the function reaches its peak.

### 1. The Horizontal Range Formula
The horizontal distance $R$ traveled by a projectile launched from the ground with an initial velocity $v_0$ at an angle $\theta$ is given by:

$$R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}$$

Where:
* $v_0$ is the constant initial velocity.
* $g$ is the constant acceleration due to gravity.
* $\theta$ is the variable launch angle.

---

### 2. Analytical Step-by-Step Optimization

To find the maximum of a function, we take its first derivative with respect to the variable ($\theta$) and set it to zero.

**Step A: Differentiate $R(\theta)$ with respect to $\theta$**
Using the chain rule for $\sin(2\theta)$, where the derivative of $\sin(u)$ is $\cos(u) \cdot \frac{du}{d\theta}$:

$$\frac{dR}{d\theta} = \frac{d}{d\theta} \left[ \frac{v_0^2}{g} \sin(2\theta) \right]$$
$$\frac{dR}{d\theta} = \frac{v_0^2}{g} \cdot \cos(2\theta) \cdot 2$$
$$\frac{dR}{d\theta} = \frac{2v_0^2 \cos(2\theta)}{g}$$



[Image of range versus launch angle graph]


**Step B: Set the derivative to zero**
The maximum occurs when the slope of the range function is zero:

$$0 = \frac{2v_0^2 \cos(2\theta)}{g}$$

Since $v_0$ and $g$ are non-zero constants, we can simplify this to:
$$\cos(2\theta) = 0$$

**Step C: Solve for $\theta$**
We know that the cosine function is zero at $90^\circ$ (or $\frac{\pi}{2}$ radians) within the physical limits of a projectile launch:

$$2\theta = 90^\circ$$
$$\theta = 45^\circ$$

---

### 3. Verification (Second Derivative Test)
To ensure this is a maximum and not a minimum, we look at the second derivative:
$$\frac{d^2R}{d\theta^2} = -\frac{4v_0^2 \sin(2\theta)}{g}$$

Plugging in $\theta = 45^\circ$:
$$\frac{d^2R}{d\theta^2} = -\frac{4v_0^2 \sin(90^\circ)}{g} = -\frac{4v_0^2}{g}$$

Since the second derivative is **negative**, the function is concave down at $45^\circ$, confirming it is a **local maximum**.

### Conclusion
Analytically, the sine function $\sin(2\theta)$ reaches its maximum value of **1** when its argument is $90^\circ$. Therefore, the range is maximized when $2\theta = 90^\circ$, which results in a launch angle of **$45^\circ$**.

Would you like to see how the optimal angle changes if the projectile is launched from an elevated platform instead of the ground?
