This problem has two distinct parts: first, finding the secondary voltage, and second, finding the primary current. We will use two different transformer rules to solve them.

---

### Part 1: Finding the Secondary Voltage ($V_s$)

The relationship between the number of turns and the voltage is a direct proportion.

#### The Formula

$$\frac{V_p}{V_s} = \frac{N_p}{N_s}$$

Where:

* $N_p$ = primary turns (**1000 turns**)
* $N_s$ = secondary turns (**200 turns**)
* $V_p$ = primary voltage (**120 V**)
* $V_s$ = secondary voltage (what we need to find)

#### Step-by-Step Solution for Voltage

**Step 1: Rearrange the formula to solve for $V_s$**


$$V_s = V_p \times \frac{N_s}{N_p}$$

**Step 2: Plug in the values and calculate**


$$V_s = 120 \times \frac{200}{1000}$$

Simplify the fraction $\frac{200}{1000} = 0.2$ (this means it's a 5:1 step-down transformer):


$$V_s = 120 \times 0.2 = 24\text{ V}$$

> **Result 1:** The secondary voltage is **24 V**.

---

### Part 2: Finding the Primary Current ($I_p$)

In an ideal transformer, power in equals power out ($P_p = P_s$). Because $P = V \times I$, if voltage goes *down*, the current must go *up* by the exact same factor. This means current is **inversely** proportional to the number of turns.

#### The Formula

$$\frac{I_p}{I_s} = \frac{N_s}{N_p}$$

Where:

* $I_s$ = secondary current (**3 A**)
* $I_p$ = primary current (what we need to find)

#### Step-by-Step Solution for Current

**Step 1: Rearrange the formula to solve for $I_p$**


$$I_p = I_s \times \frac{N_s}{N_p}$$

**Step 2: Plug in the values and calculate**


$$I_p = 3 \times \frac{200}{1000}$$

$$I_p = 3 \times 0.2 = 0.6\text{ A}$$

*(Alternative check using power: $P_s = 24\text{ V} \times 3\text{ A} = 72\text{ W}$. Therefore, $I_p = \frac{72\text{ W}}{120\text{ V}} = 0.6\text{ A}$. The math holds up perfectly!)*

---

### Final Answer

* Secondary Voltage ($V_s$) = **24 V**
* Primary Current ($I_p$) = **0.6 A**
