To find the time-dependent velocity and position, we will use Newton's Second Law ($\mathbf{F} = m\mathbf{a}$) and integrate the acceleration.

**Given:**
* Mass $m = 3\text{ kg}$
* Force $\mathbf{F}(t) = (15t, 3t - 12, -6t^2)$
* Initial Velocity $\mathbf{v}_0 = (2, 0, 1) \text{ m/s}$
* Initial Position $\mathbf{r}_0 = (5, 2, -3) \text{ m}$

---

### 1. Find the Acceleration ($\mathbf{a}$)
Using $\mathbf{a} = \frac{\mathbf{F}}{m}$:
* $a_x = \frac{15t}{3} = 5t$
* $a_y = \frac{3t - 12}{3} = t - 4$
* $a_z = \frac{-6t^2}{3} = -2t^2$

**$\mathbf{a}(t) = (5t, t - 4, -2t^2) \text{ m/s}^2$**

---

### 2. Find the Velocity ($\mathbf{v}$)
Velocity is the integral of acceleration: $\mathbf{v}(t) = \int \mathbf{a}(t) dt + \mathbf{v}_0$.

* **x-component:** $v_x = \int 5t \, dt = \frac{5}{2}t^2 + C_1$. Since $v_x(0) = 2$, $C_1 = 2$.
* **y-component:** $v_y = \int (t - 4) \, dt = \frac{1}{2}t^2 - 4t + C_2$. Since $v_y(0) = 0$, $C_2 = 0$.
* **z-component:** $v_z = \int -2t^2 \, dt = -\frac{2}{3}t^3 + C_3$. Since $v_z(0) = 1$, $C_3 = 1$.

**$\mathbf{v}(t) = (2.5t^2 + 2, 0.5t^2 - 4t, -0.67t^3 + 1) \text{ m/s}$**

---

### 3. Find the Position ($\mathbf{r}$)
Position is the integral of velocity: $\mathbf{r}(t) = \int \mathbf{v}(t) dt + \mathbf{r}_0$.

* **x-component:** $x(t) = \int (2.5t^2 + 2) \, dt = \frac{2.5}{3}t^3 + 2t + C_4$. 
  Since $x(0) = 5$, $C_4 = 5$. 
  $\rightarrow x(t) = \frac{5}{6}t^3 + 2t + 5$

* **y-component:** $y(t) = \int (0.5t^2 - 4t) \, dt = \frac{0.5}{3}t^3 - 2t^2 + C_5$. 
  Since $y(0) = 2$, $C_5 = 2$. 
  $\rightarrow y(t) = \frac{1}{6}t^3 - 2t^2 + 2$

* **z-component:** $z(t) = \int (-\frac{2}{3}t^3 + 1) \, dt = -\frac{2}{12}t^4 + t + C_6$. 
  Since $z(0) = -3$, $C_6 = -3$. 
  $\rightarrow z(t) = -\frac{1}{6}t^4 + t - 3$

---

### Summary of Results

| Vector | Expression |
| :--- | :--- |
| **Velocity** $\mathbf{v}(t)$ | $(\frac{5}{2}t^2 + 2)\mathbf{i} + (\frac{1}{2}t^2 - 4t)\mathbf{j} + (-\frac{2}{3}t^3 + 1)\mathbf{k}$ |
| **Position** $\mathbf{r}(t)$ | $(\frac{5}{6}t^3 + 2t + 5)\mathbf{i} + (\frac{1}{6}t^3 - 2t^2 + 2)\mathbf{j} + (-\frac{1}{6}t^4 + t - 3)\mathbf{k}$ |

These equations describe the path and speed of the particle at any given time $t$ within the force field.
