# 🌀 7. Elimination of Time: The Geometry of Motion

In physics, we often describe motion using time ($t$) as a bridge. But what if we want to see the **pure shape** of the path? By eliminating time, we reveal the mathematical "sculpture" the object leaves behind in space.

---

### 🛠️ Part A: Carving the Path (Eliminating $t$)

We start with two parametric equations:
1.  $x = 2t^2 \implies t = \sqrt{\frac{x}{2}}$
2.  $y = 3t^3$

By substituting the time derived from $x$ into $y$, the "bridge" of time vanishes:
$$y = 3 \left( \sqrt{\frac{x}{2}} \right)^3 = 3 \left( \frac{x}{2} \right)^{3/2}$$

To make it look cleaner, we can square both sides:
$$\mathbf{y^2 = \frac{27}{8}x^3}$$



> **The Result:** This is a **Semi-cubical Parabola**. The object doesn't just curve; it accelerates its curving as it moves further from the origin.

---

### ⚡ Part B: The Kinetic Signature (Velocity & Acceleration)

While the path is a static shape, the movement along it is dynamic.

#### 1. Velocity ($\vec{v}$): The Instantaneous Direction
$$\vec{v}(t) = \left( \frac{dx}{dt}, \frac{dy}{dt} \right) = \mathbf{(4t)\hat{i} + (9t^2)\hat{j}}$$
* **Magnitude:** $|\vec{v}(t)| = \sqrt{(4t)^2 + (9t^2)^2} = \mathbf{\sqrt{16t^2 + 81t^4}}$
* *Observation:* As $t$ increases, the speed grows rapidly!

#### 2. Acceleration ($\vec{a}$): The Changing Force
$$\vec{a}(t) = \frac{d\vec{v}}{dt} = \mathbf{4\hat{i} + (18t)\hat{j}}$$
* **Magnitude:** $|\vec{a}(t)| = \sqrt{4^2 + (18t)^2} = \mathbf{\sqrt{16 + 324t^2}}$



---

### ❓ Is the Acceleration Constant?

**The Verdict: No.**

Look closely at the acceleration vector $\vec{a}(t) = 4\hat{i} + 18t\hat{j}$. 
* The horizontal component ($4$) is constant.
* The vertical component ($18t$) is **linearly increasing with time**.

This means that as the object moves, the "engine" or "force" pushing it upwards is getting stronger and stronger every second. It’s not just moving; it’s experiencing an ever-growing vertical surge!

---
