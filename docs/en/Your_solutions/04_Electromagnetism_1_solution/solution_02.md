To calculate the electric potential at the center of the square, we use the principle of superposition. Unlike electric force (which is a vector), **electric potential ($V$) is a scalar quantity**, meaning we simply add the potentials from each charge together.

### 1. Identify the Distance ($r$)
As determined in the previous geometry, the distance from any corner of a square with sides $s = 1.0\text{ m}$ to its center is half of the diagonal.

$$r = \frac{s\sqrt{2}}{2} = \frac{1.0\sqrt{2}}{2} = \frac{\sqrt{2}}{2} \text{ m} \approx 0.707 \text{ m}$$

Because the center is equidistant from all four corners, $r$ is the same for all charges.

---

### 2. The Formula for Electric Potential
The potential $V$ created by a point charge $q$ at a distance $r$ is:
$$V = k \frac{q}{r}$$
where $k \approx 8.99 \times 10^9 \text{ N}\cdot\text{m}^2/\text{C}^2$.

For multiple charges, the total potential $V_{net}$ is:
$$V_{net} = V_1 + V_2 + V_3 + V_4 = k \frac{q_1}{r} + k \frac{q_2}{r} + k \frac{q_3}{r} + k \frac{q_4}{r}$$

We can factor out $\frac{k}{r}$ to simplify the calculation:
$$V_{net} = \frac{k}{r} (q_1 + q_2 + q_3 + q_4)$$

---

### 3. Calculate the Sum of the Charges
**Given charges:**
*   $q_1 = +1\text{ C}$
*   $q_2 = -2\text{ C}$
*   $q_3 = +3\text{ C}$
*   $q_4 = -4\text{ C}$

**Sum:**
$$\sum q = 1 + (-2) + 3 + (-4) = -2\text{ C}$$

---

### 4. Solve for $V_{net}$
Substitute the values into the factored equation:
$$V_{net} = \frac{8.99 \times 10^9}{\sqrt{2}/2} \cdot (-2)$$

Using $\frac{1}{\sqrt{2}/2} = \sqrt{2} \approx 1.414$:
$$V_{net} = (8.99 \times 10^9) \cdot (1.414) \cdot (-2)$$
$$V_{net} = (1.271 \times 10^{10}) \cdot (-2)$$
$$V_{net} = -2.542 \times 10^{10} \text{ V}$$

---

### Final Result
The electric potential at the center of the square is **$-25.42\text{ GV}$** (gigavolts) or **$-2.542 \times 10^{10}\text{ V}$**.

> **Note:** Even though the net force on a charge at the center would be non-zero in this specific configuration (unlike the previous problem), the potential is simply the sum of the work required to bring each charge to that point. Since the sum of the charges is negative, the potential is negative.
