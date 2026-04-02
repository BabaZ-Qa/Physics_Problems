```python?code_reference&code_event_index=2
m1 = 5
m2 = 10
F = 45
mu = 0.2
g = 9.8

# Normal force on m1 (top block)
N1 = m1 * g
# Kinetic friction between m1 and m2
fk1 = mu * N1

# Normal force on m2 (bottom block) from the floor
N2 = (m1 + m2) * g
# Kinetic friction between m2 and floor
fk2 = mu * N2

# Net force on m2
F_net = F - fk1 - fk2
a2 = F_net / m2

print(f"{N1=}, {fk1=}")
print(f"{N2=}, {fk2=}")
print(f"{F_net=}, {a2=}")


```
```text?code_stdout&code_event_index=2
N1=49.0, fk1=9.8
N2=147.0, fk2=29.400000000000002
F_net=5.800000000000001, a2=0.5800000000000001

```
To solve for the acceleration of the $10\text{ kg}$ block, we need to analyze the forces acting on it while considering the constraints of the system.

### 1. Identify the Forces
There are two blocks:
* **Block 1 ($m_1 = 5\text{ kg}$):** Stationary (tied to the wall).
* **Block 2 ($m_2 = 10\text{ kg}$):** Pulled by a force $F = 45\text{ N}$ and moving relative to both the floor and Block 1.



### 2. Calculate the Normal Forces
The normal forces are required to find the magnitude of the frictional forces.
* **Normal force between the blocks ($N_1$):** This is equal to the weight of the top block.
    $$N_1 = m_1 \cdot g = 5\text{ kg} \times 9.8\text{ m/s}^2 = 49\text{ N}$$
* **Normal force between the bottom block and the floor ($N_2$):** This is the total weight of both blocks pushing down on the floor.
    $$N_2 = (m_1 + m_2) \cdot g = (5 + 10)\text{ kg} \times 9.8\text{ m/s}^2 = 147\text{ N}$$

### 3. Calculate the Frictional Forces
Since the $10\text{ kg}$ block is moving, it experiences kinetic friction ($\mu_k = 0.2$) at two surfaces:
* **Friction from the top block ($f_{k1}$):** Acts against the motion of the $10\text{ kg}$ block.
    $$f_{k1} = \mu_k \cdot N_1 = 0.2 \times 49\text{ N} = 9.8\text{ N}$$
* **Friction from the floor ($f_{k2}$):** Acts against the motion of the $10\text{ kg}$ block.
    $$f_{k2} = \mu_k \cdot N_2 = 0.2 \times 147\text{ N} = 29.4\text{ N}$$

### 4. Apply Newton's Second Law to the 10 kg Block
The net force ($F_{net}$) on the $10\text{ kg}$ block is the applied force minus the two opposing frictional forces.
$$F_{net} = F - f_{k1} - f_{k2}$$
$$F_{net} = 45\text{ N} - 9.8\text{ N} - 29.4\text{ N}$$
$$F_{net} = 5.8\text{ N}$$

Now, use $F = m \cdot a$ to find the acceleration ($a$):
$$a = \frac{F_{net}}{m_2}$$
$$a = \frac{5.8\text{ N}}{10\text{ kg}}$$
$$a = 0.58\text{ m/s}^2$$

**Result:** The acceleration of the $10\text{ kg}$ block is **$0.58\text{ m/s}^2$**.
