To find the resulting wave, we use the **Principle of Superposition**, which states that the total displacement is the algebraic sum of the individual displacements: $y(x,t) = y_1(x,t) + y_2(x,t)$.

### 1. Derive the Standing Wave Equation
We start with the two given wave equations:
*   $y_1(x,t) = A \sin(kx - \omega t)$ (Wave traveling to the right)
*   $y_2(x,t) = A \sin(kx + \omega t)$ (Wave traveling to the left)

Adding them together:
$$y(x,t) = A [\sin(kx - \omega t) + \sin(kx + \omega t)]$$

We apply the trigonometric identity for the sum of sines, $\sin(\alpha) + \sin(\beta) = 2 \sin\left(\frac{\alpha + \beta}{2}\right) \cos\left(\frac{\alpha - \beta}{2}\right)$:
*   Let $\alpha = kx + \omega t$
*   Let $\beta = kx - \omega t$

Substituting these into the identity:
$$y(x,t) = A \left[ 2 \sin\left(\frac{(kx + \omega t) + (kx - \omega t)}{2}\right) \cos\left(\frac{(kx + \omega t) - (kx - \omega t)}{2}\right) \right]$$
$$y(x,t) = 2A \sin(kx) \cos(\omega t)$$

This is the standard equation for a **standing wave**.

---

### 2. Identify the Positions of the Nodes
Nodes are positions where the displacement is **always zero**, regardless of the time $t$. This occurs when the spatial part of the equation equals zero:
$$\sin(kx) = 0$$

The sine function is zero at integer multiples of $\pi$:
$$kx = n\pi \quad \text{where } n = 0, 1, 2, 3, \dots$$

Since the wave number $k$ is defined as $k = \frac{2\pi}{\lambda}$, we substitute that back in:
$$\left(\frac{2\pi}{\lambda}\right)x = n\pi$$

Solving for $x$:
$$x = n \frac{\lambda}{2}$$

**Positions of the nodes:**
*   $x = 0$
*   $x = \frac{\lambda}{2}$
*   $x = \lambda$
*   $x = \frac{3\lambda}{2}$
*   And so on...

---

### Summary
*   **Resulting Equation:** $y(x,t) = [2A \sin(kx)] \cos(\omega t)$
*   **Node Characteristics:** Nodes occur every half-wavelength ($\frac{\lambda}{2}$). At these specific points, the two counter-propagating waves interfere destructively at all times, keeping the string (or medium) perfectly still.
