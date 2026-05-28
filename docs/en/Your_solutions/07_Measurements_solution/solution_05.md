```python
t = 5.45
dt = 0.22
percentage_uncertainty = (dt / t) * 100
print(f"Percentage Uncertainty: {percentage_uncertainty}%")



```

```text
Percentage Uncertainty: 4.036697247706423%


```

To find the percentage uncertainty of the measurement, we follow a simple step-by-step process:

### **Step 1: Identify the Given Values**

From the given measurement $t = 5.45 \pm 0.22\text{ seconds}$, we can identify:

* **Measured value ($t$):** $5.45\text{ s}$
* **Absolute uncertainty ($\Delta t$):** $0.22\text{ s}$

---

### **Step 2: Use the Percentage Uncertainty Formula**

Percentage uncertainty expresses the absolute uncertainty as a percentage of the total measured value. The formula is:


$$\text{Percentage Uncertainty} = \left( \frac{\Delta t}{t} \right) \times 100\%$$

---

### **Step 3: Substitute the Values into the Formula**

Put the identified values into the equation:


$$\text{Percentage Uncertainty} = \left( \frac{0.22\text{ s}}{5.45\text{ s}} \right) \times 100\%$$

---

### **Step 4: Calculate the Value**

First, divide the absolute uncertainty by the measured value to get the fractional uncertainty:


$$\frac{0.22}{5.45} \approx 0.040367$$

Next, multiply by $100$ to convert it into a percentage:


$$0.040367 \times 100\% \approx 4.0367\%$$

---

### **Step 5: Round to the Correct Significant Figures**

When multiplying or dividing, your final answer should match the number of significant figures of the value with the fewest significant figures:

* $5.45$ has $3$ significant figures.
* $0.22$ has $2$ significant figures.

Therefore, the final answer should be rounded to **2 significant figures**:


$$\text{Percentage Uncertainty} \approx 4.0\%$$


*(Note: If your specific curriculum requires keeping two decimal places for percentages, it would be written as **$4.04\%$**).*
