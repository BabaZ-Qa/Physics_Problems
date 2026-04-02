To solve for the motion of an object thrown vertically with linear air resistance (drag), we must account for both gravity and a resistive force proportional to velocity.

### 1. Analytical Solution of the Equation of Motion

The given equation is a first-order linear differential equation:
$$m\frac{dv}{dt} = -mg - kv \implies \frac{dv}{dt} = -g - \frac{k}{m}v$$

Let $\rho = \frac{k}{m}$. The equation becomes $\frac{dv}{dt} = -(g + \rho v)$. We solve this using separation of variables:
$$\frac{dv}{g + \rho v} = -dt$$

Integrating both sides:
$$\frac{1}{\rho} \ln(g + \rho v) = -dt + C$$
$$\ln(g + \rho v) = -\rho t + C' \implies g + \rho v = e^{-\rho t + C'}$$

Using the initial condition $v(0) = v_0$:
$$g + \rho v_0 = e^{C'} \implies g + \rho v(t) = (g + \rho v_0)e^{-\rho t}$$

**The velocity function $v(t)$ is:**
$$v(t) = \left(v_0 + \frac{mg}{k}\right) e^{-\frac{k}{m}t} - \frac{mg}{k}$$

To find the position $x(t)$, we integrate $v(t)$ with $x(0) = 10$:
$$x(t) = 10 + \int_{0}^{t} v(t') dt'$$
$$x(t) = 10 + \frac{m}{k} \left(v_0 + \frac{mg}{k}\right) (1 - e^{-\frac{k}{m}t}) - \frac{mg}{k}t$$

---

### 2. Determine the Maximum Height

The maximum height ($H_{max}$) occurs when the velocity becomes zero ($v(t_{up}) = 0$).

1.  **Find the time to reach the top ($t_{up}$):**
    $$0 = (v_0 + \frac{g}{\rho})e^{-\rho t_{up}} - \frac{g}{\rho} \implies e^{\rho t_{up}} = 1 + \frac{\rho v_0}{g}$$
    $$t_{up} = \frac{m}{k} \ln\left(1 + \frac{kv_0}{mg}\right)$$

2.  **Calculate $H_{max}$:**
    Substitute $t_{up}$ into the $x(t)$ equation:
    $$H_{max} = 10 + \frac{mv_0}{k} - \frac{m^2g}{k^2} \ln\left(1 + \frac{kv_0}{mg}\right)$$

---

### 3. Comparison with the Case Without Drag

In a vacuum (no drag, $k=0$):
* **Velocity:** $v(t) = v_0 - gt$
* **Height:** $H_{max} = 10 + \frac{v_0^2}{2g}$
* **Symmetry:** The time to rise equals the time to fall.

**With Drag:**
* **$H_{max}$ is lower** because energy is dissipated as heat.
* **$t_{up}$ is shorter** because drag acts in the same direction as gravity during the ascent.
* **Terminal Velocity:** Unlike the vacuum case, the object will eventually reach a constant terminal velocity ($v_t = \frac{mg}{k}$) during its fall.



---

### 4. Numerical Simulation (Python)

We can use the Euler method to simulate this motion numerically.

```python
import matplotlib.pyplot as plt

# Constants
m = 1.0       # mass (kg)
g = 9.81      # gravity (m/s^2)
k = 0.1       # drag coefficient
v0 = 20.0     # initial velocity (m/s)
x0 = 10.0     # initial height (m)
dt = 0.01     # time step
t_max = 5.0   # total simulation time

# Initialization
t, x, v = [0], [x0], [v0]

# Numerical integration (Euler Method)
for i in range(int(t_max/dt)):
    # Calculate acceleration: a = -g - (k/m)v
    a = -g - (k/m) * v[-1]
    
    # Update velocity and position
    new_v = v[-1] + a * dt
    new_x = x[-1] + v[-1] * dt
    
    # Stop if it hits the ground (optional)
    if new_x < 0: break
        
    v.append(new_v)
    x.append(new_x)
    t.append(t[-1] + dt)

# Plotting
plt.figure(figsize=(10, 5))
plt.subplot(1, 2, 1)
plt.plot(t, x, label='With Drag')
plt.title('Position vs Time')
plt.xlabel('Time (s)')
plt.ylabel('Height (m)')
plt.grid(True)

plt.subplot(1, 2, 2)
plt.plot(t, v, color='red')
plt.title('Velocity vs Time')
plt.xlabel('Time (s)')
plt.ylabel('Velocity (m/s)')
plt.grid(True)

plt.tight_layout()
plt.show()
```
