To calculate the equivalent resistance and the current for these two configurations, we will use Ohm’s Law: $V = I \cdot R$.

---

## 1. Series Circuit

In a series circuit, the current flows through each resistor one after the other. The total resistance is simply the sum of all individual resistances.

### **Step 1: Calculate Equivalent Resistance ($R_s$)**

The formula for resistors in series is:


$$R_s = R_1 + R_2 + R_3$$

Substituting the values:


$$R_s = 15\,\Omega + 30\,\Omega + 50\,\Omega$$

$$R_s = \mathbf{95\,\Omega}$$

### **Step 2: Calculate Total Current ($I_s$)**

Using Ohm's Law ($I = V / R$):


$$I_s = \frac{12\,\text{V}}{95\,\Omega}$$

$$I_s \approx \mathbf{0.126\,\text{A}} \text{ (or } 126\,\text{mA})$$

---

## 2. Parallel Circuit

In a parallel circuit, the voltage across each resistor is the same (12 V), but the total current is divided among the branches.

### **Step 1: Calculate Equivalent Resistance ($R_p$)**

The formula for the reciprocal of equivalent resistance in parallel is:


$$\frac{1}{R_p} = \frac{1}{R_1} + \frac{1}{R_2} + \frac{1}{R_3}$$

Substituting the values:


$$\frac{1}{R_p} = \frac{1}{15} + \frac{1}{30} + \frac{1}{50}$$

To solve this, find a common denominator (150):


$$\frac{1}{R_p} = \frac{10}{150} + \frac{5}{150} + \frac{3}{150} = \frac{18}{150}$$

Now, take the reciprocal to find $R_p$:


$$R_p = \frac{150}{18} \approx \mathbf{8.33\,\Omega}$$

### **Step 2: Calculate Total Current ($I_p$)**

Using Ohm's Law:


$$I_p = \frac{12\,\text{V}}{8.33\,\Omega}$$

$$I_p = \mathbf{1.44\,\text{A}}$$

---

## Summary Table

| Configuration | Equivalent Resistance ($R_{eq}$) | Total Current ($I$) |
| --- | --- | --- |
| **Series** | $95\,\Omega$ | $0.126\,\text{A}$ |
| **Parallel** | $8.33\,\Omega$ | $1.44\,\text{A}$ |
