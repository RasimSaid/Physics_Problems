# 🚀 Section 1: Mechanics I - An Illustrated Journey

Welcome to the Solutions Lab! We're breaking down complex mechanics problems using math, logic, and visual aids. Let's make physics clear and engaging.

---

## 🎯 1. Projectile Motion: The Path of an Arrow

We are studying an object fired from the ground with significant power. The math isn't just numbers; it's the DNA of the object's flight path.

**Scenario Parameters:**
* **Initial Velocity ($v_0$):** $100 \text{ m/s}$ (That's $360 \text{ km/h}$!)
* **Launch Angle ($\theta$):** $37^\circ$
* **Constants:** $g \approx 9.8 \text{ m/s}^2$
* *(Trig Approximation: $\sin 37^\circ \approx 0.6$, $\cos 37^\circ \approx 0.8$)*

### 🔍 Part A: The DNA of Motion (Differential Equations)

We divide the universe of this motion into two independent axes. Gravity is our only force, and it only pulls downwards ($y$). The object moves horizontally ($x$) by inertia alone.

The core of the motion can be visualized as two orthogonal acceleration vectors. Gravity acts ONLY in the negative vertical direction. Horizontal acceleration is zero because there is no air resistance.

$$
\underbrace{ \vec{a} = \left( 0, -g \right) }_{\text{Acceleration Vector}} \quad \xrightarrow{\text{Divided Component-wise}} \quad \begin{cases} \mathbf{ \frac{d^2x}{dt^2} = 0 } & \text{(Uniform Velocity Horizontal)} \\ \mathbf{ \frac{d^2y}{dt^2} = -g } & \text{(Constant Gravity Vertical)} \end{cases}
$$

### ⏱️ Part B: Chronos (Time of Flight, $t_f$)

When does the journey end? When the vertical position ($y$) returns to zero. We solve for time $t$. The flight duration depends solely on the initial *vertical* power ($v_0 \sin\theta = 60 \text{ m/s}$).

$$y(t) = (v_0 \sin\theta)t - \frac{1}{2}gt^2$$
$$0 = t \left( v_0 \sin\theta - \frac{1}{2}gt \right)$$

This gives us two times: $t=0$ (launch) and the final time $t_f$:

$$\mathbf{t_f = \frac{2v_0 \sin\theta}{g}} = \frac{120}{9.8} \approx \mathbf{12.24 \text{ s}}$$

---
### 🏔️ Part C: Summit (Maximum Height, $H_{max}$)

This is the object's highest potential energy. It occurs exactly at the apex, where the object momentarily stops moving UP ($v_y = 0$).

A stylized diagram of a projectile trajectory. The peak of the arc is marked as 'Summit'. The vertical displacement is labeled $H_{max}$. Horizontal displacement is labeled $R/2$. Arrows indicate the velocity vector at the peak ($v_{peak} = v_{0x}$). At this point, the vertical velocity component $v_y$ is exactly zero, as shown by the vector breakdown.

$$v_y^2 = (v_0 \sin\theta)^2 - 2g \Delta y$$
$$0 = (60)^2 - 2(9.8)H_{max}$$
$$\mathbf{H_{max}} = \frac{60^2}{19.6} = \frac{3600}{19.6} \approx \mathbf{183.67 \text{ m}}$$

The maximum vertical power is $v_{0y} = 60 \text{ m/s}$. Using the kinetic energy analogy ($mgh = \frac{1}{2}mv_y^2$), we get $H = v_y^2 / 2g$, which confirms the formula. $183.67$ meters is approximately the height of a 60-story building!

---
### 📏 Part D: Horizon (Range, $R$)

The horizontal distance traveled. Since the object moves horizontally at a constant speed ($v_{0x} = v_0 \cos\theta = 80 \text{ m/s}$), the range is simply **(horizontal speed)** $\times$ **(flight time)**.

$$R = v_{0x} \cdot t_f = (v_0 \cos\theta) \left( \frac{2v_0 \sin\theta}{g} \right)$$

$$\mathbf{R} = \frac{v_0^2 \sin(2\theta)}{g} = \frac{100^2 \cdot \sin(74^\circ)}{9.8} \approx \mathbf{980.8 \text{ m}}$$

A simple illustration showing the horizontal dimension of the projectile's flight. A large horizontal arrow covers the entire trajectory from launch point to landing point. It is labeled "RANGE ($R$) = $980.8$ m". Below the range arrow, the initial horizontal velocity is shown: $v_{0x} = 80 \text{ m/s}$ ($288 \text{ km/h}$). The text highlights that horizontal velocity is constant during the entire flight, enabling the simple calculation $R = v_{0x} \cdot t_f$.

That's almost a full kilometer (0.61 miles)!

---

## 📈 Visualizing the Full Path

Combining all our results into a unified visual model:

A comprehensive, annotated diagram of the projectile's trajectory. A smooth parabolic curve tracks the flight. The apex is clearly marked as $H_{max} = 183.67$ m. The landing point is marked as $R = 980.8$ m. The launch angle $\theta=37^\circ$ and initial velocity vector $v_0 = 100 \text{ m/s}$ are prominent. Velocity vectors are included at several points, showing their magnitude decreasing towards the apex and increasing afterwards, while the horizontal component remains visibly constant. Gravity vectors (g) point downwards throughout. Text labels summarize key data points like $v_{0x} = 80$ m/s, $v_{0y} = 60$ m/s, and $t_f = 12.24$ s.

With this, we have fully mapped the mechanics of the projectile's flight.

---
