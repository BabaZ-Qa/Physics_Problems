GitHub profilindeki dökümanına ekleyebileceğin, elektromanyetik dalga analizinin adım adım çözümünü aşağıda bulabilirsin:

---

## 6. EM Wave Analysis
**Problem:** An electromagnetic wave has its electric field component described by:
$$E_y(x,t) = 100 \sin(10^7 x - \omega t)\text{ V/m}$$
Determine the direction of propagation, the wavelength ($\lambda$), the angular frequency ($\omega$), and the equation for the magnetic field component ($B_z$).

### Solution:
*   **Electric Field Amplitude ($E_0$):** $100\text{ V/m}$
*   **Wave Number ($k$):** $10^7\text{ rad/m}$
*   **Speed of Light ($c$):** $\approx 3 \times 10^8\text{ m/s}$

---

### Step 1: Direction of Propagation
The general form of a wave is $f(kx - \omega t)$. 
*   Since the variable in the sine function is $(10^7 x - \omega t)$, the wave is traveling in the **positive x-direction** ($+x$).

---

### Step 2: Calculate Wavelength ($\lambda$)
**Formula:** $\lambda = \frac{2\pi}{k}$
1. $\lambda = \frac{2\pi}{10^7}$
2. **Result:** $\lambda \approx 6.28 \times 10^{-7}\text{ m}$ (or $628\text{ nm}$)

---

### Step 3: Calculate Angular Frequency ($\omega$)
**Formula:** $\omega = c \cdot k$
1. $\omega = (3 \times 10^8) \cdot 10^7$
2. **Result:** $\omega = 3 \times 10^{15}\text{ rad/s}$

---

### Step 4: Equation for Magnetic Field ($B_z$)
**1. Find Amplitude ($B_0$):**
Using $B_0 = \frac{E_0}{c}$:
$B_0 = \frac{100}{3 \times 10^8} \approx 3.33 \times 10^{-7}\text{ T}$

**2. Determine Direction and Phase:**
In an EM wave, $\vec{E}$ and $\vec{B}$ are perpendicular to each other and to the direction of propagation. Since $\vec{E}$ is in the $y$ direction and propagation is in $x$, $\vec{B}$ must be in the **z-direction**. It oscillates in phase with $E_y$.

**Equation:**
$$B_z(x,t) = 3.33 \times 10^{-7} \sin(10^7 x - 3 \times 10^{15} t)\text{ T}$$

---
