To solve this problem, we will analyze the behavior of a restorative force, which is the physical basis for **Simple Harmonic Motion (SHM)**, such as a mass on a spring.

### 1. Equation of Motion and Solution
According to Newton's Second Law, $F = ma$. Given $F(x) = -kx$, we can write:
$$m \frac{d^2x}{dt^2} = -kx \implies \frac{d^2x}{dt^2} + \frac{k}{m}x = 0$$

This is a second-order linear differential equation. By defining $\omega^2 = \frac{k}{m}$, we get the standard form:
$$\ddot{x} + \omega^2x = 0$$

**The general solution is:**
$$x(t) = A \cos(\omega t + \phi)$$
where $A$ is the amplitude and $\phi$ is the phase constant.

---

### 2. Work Done from $0$ to $x_0$
Work ($W$) is defined as the integral of force over displacement. Since the force is variable, we calculate:
$$W = \int_{0}^{x_0} F(x) \, dx$$
$$W = \int_{0}^{x_0} (-kx) \, dx$$
$$W = -k \left[ \frac{1}{2}x^2 \right]_{0}^{x_0}$$
$$W = -\frac{1}{2}kx_0^2$$

---

### 3. Interpretation as Potential Energy
The work done by a **conservative force** is equal to the negative change in potential energy ($\Delta U$):
$$W = -\Delta U = -(U(x_0) - U(0))$$

If we define the potential energy at the origin as zero ($U(0) = 0$), then:
$$-\frac{1}{2}kx_0^2 = -U(x_0)$$
$$U(x) = \frac{1}{2}kx^2$$
This result represents the **Elastic Potential Energy** stored in the system.

---

### 4. Verify the Relationship $F = -\frac{dU}{dx}$
To verify, we take the negative derivative of our derived potential energy function with respect to $x$:
$$-\frac{d}{dx} \left( \frac{1}{2}kx^2 \right) = -\frac{1}{2}k(2x) = -kx$$
Since this matches our original force $F(x) = -kx$, the relationship is verified.

---

### 5. Graphs of $F(x)$ and $U(x)$



* **$F(x) = -kx$:** This is a **straight line** passing through the origin with a negative slope ($-k$). It shows that as displacement increases, the restoring force increases in the opposite direction.
* **$U(x) = \frac{1}{2}kx^2$:** This is a **parabola** opening upwards with its vertex at the origin. It shows that potential energy is always positive (or zero) and increases quadratically with displacement in either direction.
