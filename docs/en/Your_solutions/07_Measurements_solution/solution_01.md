```python
import math

r = 6.20
dr = 0.05

V = (4/3) * math.pi * (r**3)
dV = 4 * math.pi * (r**2) * dr

print(f"V = {V}")
print(f"dV = {dV}")



```

```text
V = 998.305991926331
dV = 24.152564320798334


```

To find the volume of the sphere and its associated uncertainty, we follow a step-by-step process using the rules of error propagation.

### **Step 1: Formula for the Volume of a Sphere**

The volume $V$ of a sphere is given by the formula:


$$V = \frac{4}{3}\pi r^3$$

Where:

* $r = 6.20\text{ cm}$ is the measured radius.
* $\Delta r = 0.05\text{ cm}$ is the absolute uncertainty in the radius.

---

### **Step 2: Calculate the Nominal Volume ($V$)**

Substitute the measured radius value into the volume formula:


$$V = \frac{4}{3}\pi (6.20\text{ cm})^3$$

$$V = \frac{4}{3}\pi (238.328\text{ cm}^3)$$

$$V \approx 998.306\text{ cm}^3$$

---

### **Step 3: Derive the Error Propagation Formula**

According to the power rule of propagation of uncertainty, if a quantity depends on a variable raised to a power ($V \propto r^3$), its relative (fractional) uncertainty is multiplied by the exponent:


$$\frac{\Delta V}{V} = 3 \frac{\Delta r}{r}$$

To find the absolute uncertainty $\Delta V$, we rearrange the equation:


$$\Delta V = 3 V \left(\frac{\Delta r}{r}\right)$$

*(Alternatively, using calculus, $\Delta V = \left| \frac{dV}{dr} \right| \Delta r = 4\pi r^2 \Delta r$, which yields identical results).*

---

### **Step 4: Calculate the Absolute Uncertainty ($\Delta V$)**

Substitute the values into the uncertainty equation:


$$\Delta V = 3 \times 998.306\text{ cm}^3 \times \left(\frac{0.05\text{ cm}}{6.20\text{ cm}}\right)$$

$$\Delta V = 2994.918 \times 0.0080645$$

$$\Delta V \approx 24.153\text{ cm}^3$$

---

### **Step 5: Round According to Significant Figures**

In experimental physics, uncertainties are typically rounded to one or two significant figures, and the central value is rounded to match the least significant decimal place of the uncertainty.

* **Using 2 Significant Figures for Uncertainty (Standard Practice):**
Rounding $\Delta V = 24.153\text{ cm}^3$ gives $\Delta V = 24\text{ cm}^3$.
We then round $V = 998.306\text{ cm}^3$ to the nearest whole unit to match the uncertainty:

$$V = (998 \pm 24)\text{ cm}^3$$


* **Using 1 Significant Figure for Uncertainty:**
Rounding $\Delta V = 24.153\text{ cm}^3$ gives $\Delta V = 20\text{ cm}^3$.
We then round $V = 998.306\text{ cm}^3$ to the tens place to match:

$$V = (1000 \pm 20)\text{ cm}^3 \quad \text{or} \quad (1.00 \pm 0.02) \times 10^3\text{ cm}^3$$
