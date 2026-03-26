To solve this projectile motion problem, we will break the initial velocity into its horizontal ($x$) and vertical ($y$) components and apply Newton's Second Law.

Given:
* Initial velocity $v_0 = 100 \text{ m/s}$
* Launch angle $\theta = 37^\circ$
* Acceleration due to gravity $g \approx 9.8 \text{ m/s}^2$ (we'll use this for calculations)

---

### 1. Differential Equations of Motion

We start with Newton's Second Law, $F = ma$. Since we are ignoring air resistance, the only force acting on the projectile is gravity, which acts purely in the downward vertical direction.

**Horizontal Direction ($x$):**
There are no horizontal forces ($F_x = 0$).
$$m \frac{d^2x}{dt^2} = 0 \implies \frac{d^2x}{dt^2} = 0$$

**Vertical Direction ($y$):**
The only force is weight ($F_y = -mg$).
$$m \frac{d^2y}{dt^2} = -mg \implies \frac{d^2y}{dt^2} = -g$$



---

### 2. Time of Flight ($T$)

First, let's find the initial velocity components:
* $v_{0x} = v_0 \cos(37^\circ) \approx 100 \times 0.8 = 80 \text{ m/s}$
* $v_{0y} = v_0 \sin(37^\circ) \approx 100 \times 0.6 = 60 \text{ m/s}$

The time of flight is the time it takes for the projectile to return to $y = 0$. Using the displacement equation $y(t) = v_{0y}t - \frac{1}{2}gt^2$:
$$0 = v_{0y}T - \frac{1}{2}gT^2$$
$$T(v_{0y} - \frac{1}{2}gT) = 0$$

Ignoring the $T=0$ solution:
$$T = \frac{2v_{0y}}{g} = \frac{2 \times 60}{9.8} \approx \mathbf{12.24 \text{ s}}$$

---

### 3. Maximum Height ($H$)

The maximum height occurs when the vertical velocity is zero ($v_y = 0$). We can use the formula $v_y^2 = v_{0y}^2 - 2gH$:
$$0 = (60)^2 - 2(9.8)H$$
$$19.6H = 3600$$
$$H = \frac{3600}{19.6} \approx \mathbf{183.67 \text{ m}}$$

---

### 4. Horizontal Range ($R$)

The range is the horizontal distance traveled during the total time of flight. Since horizontal acceleration is zero, the velocity remains constant ($v_x = v_{0x}$):
$$R = v_{0x} \times T$$
$$R = 80 \times 12.24 \approx \mathbf{979.2 \text{ m}}$$

---
**Summary of Results:**
* **Time of Flight:** $12.24 \text{ s}$
* **Max Height:** $183.67 \text{ m}$
* **Range:** $979.2 \text{ m}$

Would you like me to show you how these values change if we were to account for a specific launch height above the ground?
