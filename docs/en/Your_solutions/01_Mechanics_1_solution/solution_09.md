```python?code_reference&code_event_index=2
# Constants for the fly
m_fly_g = 2
v_fly = 10
m_fly_kg = m_fly_g / 1000
p_fly = m_fly_kg * v_fly

# Constants for the tennis ball
m_ball_g = 60
v_ball = 1
m_ball_kg = m_ball_g / 1000
p_ball = m_ball_kg * v_ball

print(f"Fly: mass = {m_fly_kg} kg, velocity = {v_fly} m/s, momentum = {p_fly} kg*m/s")
print(f"Tennis ball: mass = {m_ball_kg} kg, velocity = {v_ball} m/s, momentum = {p_ball} kg*m/s")


```
```text?code_stdout&code_event_index=2
Fly: mass = 0.002 kg, velocity = 10 m/s, momentum = 0.02 kg*m/s
Tennis ball: mass = 0.06 kg, velocity = 1 m/s, momentum = 0.06 kg*m/s

```
To determine which object has greater momentum, we compare their mass and velocity using the fundamental momentum formula.

### 1. The Momentum Formula
Momentum ($p$) is a vector quantity defined as the product of an object's mass ($m$) and its velocity ($v$):

$$p = m \times v$$

To compare the two objects accurately, we must ensure all units are in the International System of Units (SI): mass in **kilograms (kg)** and velocity in **meters per second (m/s)**.



---

### 2. Object 1: The Fly
* **Mass ($m_1$):** $2 \text{ g} = 0.002 \text{ kg}$
* **Velocity ($v_1$):** $10 \text{ m/s}$

Calculate momentum:
$$p_{fly} = 0.002 \text{ kg} \times 10 \text{ m/s} = \mathbf{0.02 \text{ kg}\cdot\text{m/s}}$$

---

### 3. Object 2: The Tennis Ball
* **Mass ($m_2$):** $60 \text{ g} = 0.060 \text{ kg}$
* **Velocity ($v_2$):** $1 \text{ m/s}$

Calculate momentum:
$$p_{ball} = 0.060 \text{ kg} \times 1 \text{ m/s} = \mathbf{0.06 \text{ kg}\cdot\text{m/s}}$$

---

### 4. Comparison and Conclusion

Now we compare the two values:
* Momentum of the fly: $0.02 \text{ kg}\cdot\text{m/s}$
* Momentum of the tennis ball: $0.06 \text{ kg}\cdot\text{m/s}$

Since $0.06 > 0.02$, the **60-gram tennis ball** has greater momentum than the fly, despite moving ten times slower. This is because the tennis ball's mass is 30 times greater than that of the fly, which more than compensates for its lower velocity.

Would you like to see how much faster the fly would need to move to have the same momentum as the tennis ball?
