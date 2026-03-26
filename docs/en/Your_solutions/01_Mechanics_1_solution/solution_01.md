Let’s solve this classic **projectile motion** problem step by step.

---

# 1. Set up the motion

Given:

* Initial velocity: ( v_0 = 100 , \text{m/s} )
* Launch angle: ( \theta = 37^\circ )
* Gravity: ( g = 9.8 , \text{m/s}^2 )
* No air resistance

Resolve the velocity into components:

[
v_{0x} = v_0 \cos\theta = 100 \cos 37^\circ \approx 100(0.8) = 80 , \text{m/s}
]

[
v_{0y} = v_0 \sin\theta = 100 \sin 37^\circ \approx 100(0.6) = 60 , \text{m/s}
]

---

# 2. Differential equations of motion

### Horizontal direction (x-axis)

No acceleration:

[
\frac{d^2 x}{dt^2} = 0
]

Integrate:
[
\frac{dx}{dt} = v_{0x} = 80
]
[
x(t) = 80t
]

---

### Vertical direction (y-axis)

Acceleration due to gravity:

[
\frac{d^2 y}{dt^2} = -g = -9.8
]

Integrate:
[
\frac{dy}{dt} = 60 - 9.8t
]

[
y(t) = 60t - 4.9t^2
]

---

# 3. Time of flight

The projectile lands when ( y = 0 ):

[
0 = 60t - 4.9t^2
]

Factor:
[
t(60 - 4.9t) = 0
]

[
t = \frac{60}{4.9} \approx 12.24 , \text{s}
]

---

# 4. Maximum height

At maximum height:
[
v_y = 0
]

[
60 - 9.8t = 0
\Rightarrow t = \frac{60}{9.8} \approx 6.12 , \text{s}
]

Now substitute into ( y(t) ):

[
y_{\text{max}} = 60(6.12) - 4.9(6.12)^2
]

[
y_{\text{max}} \approx 367.2 - 183.6 = 183.6 , \text{m}
]

---

# 5. Range

Range = horizontal distance at total time:

[
R = x(t_{\text{flight}}) = 80 \times 12.24
]

[
R \approx 979.2 , \text{m}
]

---

# ✅ Final Answers

* **Differential equations:**

  * ( \frac{d^2 x}{dt^2} = 0 )
  * ( \frac{d^2 y}{dt^2} = -9.8 )

* **Time of flight:**
  [
  \boxed{12.24 , \text{s}}
  ]

* **Maximum height:**
  [
  \boxed{183.6 , \text{m}}
  ]

* **Range:**
  [
  \boxed{979.2 , \text{m}}
  ]

---

If you want, I can also derive the **trajectory equation ( y(x) )** or solve it symbolically without approximations.
