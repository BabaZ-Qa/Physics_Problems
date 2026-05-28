To find the equivalent resistance ($R_{eq}$) of the mixed circuit, we can break it down step by step, starting from the innermost branches and working outward. Every individual resistor has a value of $R = 5\ \Omega$.

---

### Step 1: The Inner Series Branch

Looking at the middle vertical branch, there are two resistors connected directly in series with each other.


$$R_{series1} = 5\ \Omega + 5\ \Omega = 10\ \Omega$$

### Step 2: The Parallel Combination with the Bottom Resistor

This $10\ \Omega$ combination is connected in series with the bottom horizontal inner resistor ($5\ \Omega$), forming a loop with the top-left section. Let's combine this entire inner right-and-bottom branch first:


$$R_{inner\_branch} = R_{series1} + 5\ \Omega = 10\ \Omega + 5\ \Omega = 15\ \Omega$$

Now, looking at the left side of the circuit, the leftmost vertical resistor ($5\ \Omega$) and the top horizontal resistor ($5\ \Omega$) are in series with each other:


$$R_{left\_top} = 5\ \Omega + 5\ \Omega = 10\ \Omega$$

This left-top combination ($10\ \Omega$) is in parallel with our inner branch ($15\ \Omega$):


$$R_{parallel1} = \frac{10 \times 15}{10 + 15} = \frac{150}{25} = 6\ \Omega$$

### Step 3: The Outer Right Branch

Looking at the far-right vertical branch, there are two resistors connected in series:


$$R_{series2} = 5\ \Omega + 5\ \Omega = 10\ \Omega$$

### Step 4: Parallel Combination of the Upper Network

The entire upper network we simplified in Step 2 ($R_{parallel1} = 6\ \Omega$) is connected in parallel with this outer right branch ($10\ \Omega$):


$$R_{parallel2} = \frac{6 \times 10}{6 + 10} = \frac{60}{16} = 3.75\ \Omega$$

### Step 5: Final Total Equivalent Resistance

Finally, this entire upper combination ($3.75\ \Omega$) is connected in series with the very bottom horizontal resistor ($5\ \Omega$) across the main terminals.


$$R_{eq} = 3.75\ \Omega + 5\ \Omega = 8.75\ \Omega$$

---

### Final Answer

$$R_{eq} = 8.75\ \Omega$$
