To find the equivalent resistance of this mixed circuit, we need to simplify the network step by step, working from the innermost or most isolated combinations outward to the main terminals.

Every resistor in the network has a value of $R = 5\ \Omega$. Let's break down the configuration:

---

### **Step 1: Simplify the Left-Hand Loop**

Look closely at the leftmost loop of the circuit. Notice where the connection points (nodes) are located:

* There is a node on the bottom wire.
* There is another node on the top wire.

Between these two nodes, the current can split into two parallel paths:

1. **Path 1 (Left branch):** Contains exactly **1 resistor**.
2. **Path 2 (Loop branch):** The current goes through the top resistor, then down through two vertical resistors in series, and then through the bottom resistor.

Let's calculate the total resistance of **Path 2**:

* These 4 resistors are connected back-to-back in a single line, meaning they are in series.

$$R_{\text{path2}} = 5\ \Omega + 5\ \Omega + 5\ \Omega + 5\ \Omega = 20\ \Omega$$



Now, **Path 1** ($5\ \Omega$) and **Path 2** ($20\ \Omega$) are connected in parallel between the same two nodes:


$$R_{\text{left\_loop}} = \frac{R_{\text{path1}} \times R_{\text{path2}}}{R_{\text{path1}} + R_{\text{path2}}}$$

$$R_{\text{left\_loop}} = \frac{5 \times 20}{5 + 20} = \frac{100}{25} = 4\ \Omega$$

---

### **Step 2: Combine with the Right Branch**

Now, the entire left section we just simplified to $4\ \Omega$ connects directly to the right branch. Looking at the top junction node:

* The current splits between the entire **Left Loop** and the **Right Branch**.
* The **Right Branch** consists of **2 vertical resistors in series**.

Let's calculate the resistance of the right branch:


$$R_{\text{right}} = 5\ \Omega + 5\ \Omega = 10\ \Omega$$

Since the simplified Left Loop ($4\ \Omega$) and the Right Branch ($10\ \Omega$) are in parallel between the upper junction and the lower return wire, we combine them:


$$R_{\text{upper\_parallel}} = \frac{R_{\text{left\_loop}} \times R_{\text{right}}}{R_{\text{left\_loop}} + R_{\text{right}}}$$

$$R_{\text{upper\_parallel}} = \frac{4 \times 10}{4 + 10} = \frac{40}{14} \approx 2.857\ \Omega$$

---

### **Step 3: Add the Final Series Resistor**

We are now left with one final simplified block ($R_{\text{upper\_parallel}} = \frac{40}{14}\ \Omega$) connected in series with the very last resistor located on the bottom wire before reaching the right-hand terminal.

Since they are in series, we simply add their values together:


$$R_{\text{eq}} = R_{\text{upper\_parallel}} + R_{\text{bottom}}$$

$$R_{\text{eq}} = \frac{40}{14} + 5 = \frac{40}{14} + \frac{70}{14} = \frac{110}{14}\ \Omega$$

---

### **Final Answer**

$$R_{\text{eq}} \approx 7.86\ \Omega$$
