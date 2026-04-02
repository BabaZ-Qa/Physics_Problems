To solve this problem, we will use Newton’s Second Law and kinematic integration to describe the motion, then verify the energy transformation using the Work-Energy Theorem.

**Given:**
* Mass $m = 2 \text{ kg}$
* Force $\vec{F} = [6, 2] \text{ N}$ (constant)
* Initial Velocity $\vec{v}_0 = [1, -1] \text{ m/s}$
* Initial Position $\vec{r}_0 = [0, 0] \text{ m}$

---

### 1. Determine Acceleration $\vec{a}(t)$
Using Newton's Second Law, $\vec{F} = m\vec{a}$:
$$\vec{a} = \frac{\vec{F}}{m} = \left[ \frac{6}{2}, \frac{2}{2} \right] = [3, 1] \text{ m/s}^2$$
Since the force is constant, the acceleration is also constant.

---

### 2. Determine Velocity $\vec{v}(t)$
Since acceleration is constant, we use $\vec{v}(t) = \vec{v}_0 + \vec{a}t$:
$$\vec{v}(t) = [1, -1] + [3, 1]t = [3t + 1, t - 1] \text{ m/s}$$

---

### 3. Determine Position $\vec{r}(t)$
Using the kinematic equation $\vec{r}(t) = \vec{r}_0 + \vec{v}_0t + \frac{1}{2}\vec{a}t^2$:
$$\vec{r}(t) = [0, 0] + [1, -1]t + \frac{1}{2}[3, 1]t^2$$
$$\vec{r}(t) = [1.5t^2 + t, 0.5t^2 - t] \text{ m}$$

---

### 4. Trajectory of Motion
The trajectory is a **parabola**. We can see this by relating $x$ and $y$. Because the force (and thus acceleration) is constant and not parallel to the initial velocity, the path curves steadily in the direction of the force.



---

### 5. Calculate Work Done at $t = 3 \text{ s}$
Work is the dot product of Force and Displacement ($W = \vec{F} \cdot \Delta\vec{r}$).
First, find the position at $t = 3$:
* $x(3) = 1.5(3)^2 + 3 = 13.5 + 3 = 16.5 \text{ m}$
* $y(3) = 0.5(3)^2 - 3 = 4.5 - 3 = 1.5 \text{ m}$
* $\Delta\vec{r} = [16.5, 1.5] \text{ m}$

Now, calculate work:
$$W = \vec{F} \cdot \Delta\vec{r} = (6 \times 16.5) + (2 \times 1.5)$$
$$W = 99 + 3 = 102 \text{ J}$$

---

### 6. Verify Work-Energy Theorem
The theorem states that $W = \Delta K$ (Work equals the change in kinetic energy).

**Initial Kinetic Energy ($K_0$):**
$$v_0^2 = 1^2 + (-1)^2 = 2$$
$$K_0 = \frac{1}{2}mv_0^2 = \frac{1}{2}(2)(2) = 2 \text{ J}$$

**Final Kinetic Energy at $t = 3$ ($K_f$):**
First, find velocity components at $t=3$:
* $v_x(3) = 3(3) + 1 = 10 \text{ m/s}$
* $v_y(3) = 3 - 1 = 2 \text{ m/s}$
* $v_f^2 = 10^2 + 2^2 = 104$
$$K_f = \frac{1}{2}mv_f^2 = \frac{1}{2}(2)(104) = 104 \text{ J}$$

**Change in Kinetic Energy ($\Delta K$):**
$$\Delta K = 104 \text{ J} - 2 \text{ J} = 102 \text{ J}$$

**Conclusion:** Since $W = 102 \text{ J}$ and $\Delta K = 102 \text{ J}$, the results are consistent.
