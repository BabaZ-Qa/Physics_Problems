To find all possible equivalent resistances using exactly three $1\,\Omega$ resistors, we need to look at every possible way to arrange them in a circuit. There are four unique configurations.

---

### **1. All Three in Series**

In a series circuit, you simply add the resistances together.

* **Configuration:** $R_1 + R_2 + R_3$
* **Calculation:** $1 + 1 + 1 = 3$
* **Equivalent Resistance:** **$3\,\Omega$**

---

### **2. All Three in Parallel**

In a parallel circuit, the reciprocal of the total resistance is the sum of the reciprocals of each individual resistance.

* **Configuration:** $\frac{1}{R_{eq}} = \frac{1}{R_1} + \frac{1}{R_2} + \frac{1}{R_3}$
* **Calculation:** $\frac{1}{R_{eq}} = \frac{1}{1} + \frac{1}{1} + \frac{1}{1} = 3$
* **Equivalent Resistance:** $R_{eq} = \frac{1}{3} \approx$ **$0.33\,\Omega$**

---

### **3. Two in Parallel, then in Series with the Third**

In this "mixed" circuit, you first find the equivalent resistance of the two parallel resistors, then add the third one to that result.

* **Step A (Parallel pair):** $R_p = \frac{1 \cdot 1}{1 + 1} = 0.5\,\Omega$
* **Step B (Add the third in series):** $0.5 + 1 = 1.5$
* **Equivalent Resistance:** **$1.5\,\Omega$**

---

### **4. Two in Series, then in Parallel with the Third**

Here, you first calculate the resistance of the two resistors in series, and then treat that branch as being in parallel with the final resistor.

* **Step A (Series pair):** $R_s = 1 + 1 = 2\,\Omega$
* **Step B (Parallel with the third):** $\frac{1}{R_{eq}} = \frac{1}{2} + \frac{1}{1} = \frac{1}{2} + \frac{2}{2} = \frac{3}{2}$
* **Equivalent Resistance:** $R_{eq} = \frac{2}{3} \approx$ **$0.67\,\Omega$**

---

### **Summary of Unique Values**

By combining three $1\,\Omega$ resistors, you can achieve the following four unique equivalent resistances:

1. **$3\,\Omega$** (Series)
2. **$1.5\,\Omega$** (Two parallel + one series)
3. **$0.67\,\Omega$** (Two series + one parallel)
4. **$0.33\,\Omega$** (Parallel)
