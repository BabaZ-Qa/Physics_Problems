To solve for the dynamical properties of this particle, we will use the given position vector $\mathbf{r}(t)$ and apply the principles of classical mechanics.

Given mass: **$m = 0.5 \text{ kg}$**
Position vector:
$$\mathbf{r}(t) = (5t^2 - t)\mathbf{\hat{i}} + (2t^3)\mathbf{\hat{j}} + (-3t + 2)\mathbf{\hat{k}}$$

---

### 1. Particle's Velocity ($\mathbf{v}$)
Velocity is the first derivative of position with respect to time ($v = \frac{dr}{dt}$).
* $v_x = \frac{d}{dt}(5t^2 - t) = 10t - 1$
* $v_y = \frac{d}{dt}(2t^3) = 6t^2$
* $v_z = \frac{d}{dt}(-3t + 2) = -3$

**$\mathbf{v}(t) = (10t - 1)\mathbf{\hat{i}} + (6t^2)\mathbf{\hat{j}} - 3\mathbf{\hat{k}} \quad [\text{m/s}]$**

---

### 2. Particle's Momentum ($\mathbf{p}$)
Momentum is the product of mass and velocity ($\mathbf{p} = m\mathbf{v}$).
* $p_x = 0.5(10t - 1) = 5t - 0.5$
* $p_y = 0.5(6t^2) = 3t^2$
* $p_z = 0.5(-3) = -1.5$

**$\mathbf{p}(t) = (5t - 0.5)\mathbf{\hat{i}} + (3t^2)\mathbf{\hat{j}} - 1.5\mathbf{\hat{k}} \quad [\text{kg}\cdot\text{m/s}]$**

---

### 3. Particle's Acceleration ($\mathbf{a}$)
Acceleration is the derivative of velocity with respect to time ($a = \frac{dv}{dt}$).
* $a_x = \frac{d}{dt}(10t - 1) = 10$
* $a_y = \frac{d}{dt}(6t^2) = 12t$
* $a_z = \frac{d}{dt}(-3) = 0$

**$\mathbf{a}(t) = 10\mathbf{\hat{i}} + 12t\mathbf{\hat{j}} + 0\mathbf{\hat{k}} \quad [\text{m/s}^2]$**

---

### 4. Force Acting on the Particle ($\mathbf{F}$)
According to Newton's Second Law ($\mathbf{F} = m\mathbf{a}$):
* $F_x = 0.5(10) = 5$
* $F_y = 0.5(12t) = 6t$
* $F_z = 0.5(0) = 0$

**$\mathbf{F}(t) = 5\mathbf{\hat{i}} + 6t\mathbf{\hat{j}} \quad [\text{N}]$**

---

### 5. Power Transferred by the Field ($P$)
Power is the rate at which work is done, calculated as the dot product of Force and Velocity ($P = \mathbf{F} \cdot \mathbf{v}$).

$$P(t) = (F_x \cdot v_x) + (F_y \cdot v_y) + (F_z \cdot v_z)$$
$$P(t) = 5(10t - 1) + 6t(6t^2) + 0(-3)$$
$$P(t) = 50t - 5 + 36t^3$$

**$P(t) = 36t^3 + 50t - 5 \quad [\text{W}]$**

---

### Summary Table

| Quantity | Expression |
| :--- | :--- |
| **Velocity** $\mathbf{v}(t)$ | $(10t - 1, 6t^2, -3)$ |
| **Momentum** $\mathbf{p}(t)$ | $(5t - 0.5, 3t^2, -1.5)$ |
| **Acceleration** $\mathbf{a}(t)$ | $(10, 12t, 0)$ |
| **Force** $\mathbf{F}(t)$ | $(5, 6t, 0)$ |
| **Power** $P(t)$ | $36t^3 + 50t - 5$ |
