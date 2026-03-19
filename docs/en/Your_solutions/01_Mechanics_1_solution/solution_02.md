# 🎯 2. Range Optimization: Finding the "Sweet Spot"

Physics often asks: *How can we get the most out of what we have?* In projectile motion, if your power (initial velocity $v_0$) is fixed, your only "lever" to pull is the launch angle $\theta$.



[Image of projectile range for different angles]


### 🧪 The Mathematical Proof

The Range formula is a product of horizontal survival and vertical airtime:
$$R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}$$

To find the absolute peak of this function, we look for the point where the "slope" of the range change becomes zero. We take the derivative with respect to the angle $\theta$:

1.  **Differentiate:**
    $$\frac{dR}{d\theta} = \frac{v_0^2}{g} \cdot \frac{d}{d\theta}(\sin(2\theta))$$
    $$\frac{dR}{d\theta} = \frac{v_0^2}{g} \cdot 2\cos(2\theta)$$

2.  **Set to Zero (Optimization):**
    To find the maximum, we set $\frac{dR}{d\theta} = 0$:
    $$\frac{2v_0^2}{g} \cos(2\theta) = 0 \implies \cos(2\theta) = 0$$

3.  **Solve for $\theta$:**
    The cosine function is zero at $90^\circ$:
    $$2\theta = 90^\circ \implies \mathbf{\theta = 45^\circ}$$

---

### 💡 The Intuition: The Tug-of-War

Why 45°? Why not 30° or 60°? Think of it as a balance between two competing needs:

* **Low Angles (e.g., 20°):** You have massive horizontal speed, but you hit the ground too soon. You have the "speed" but no "time."
* **High Angles (e.g., 70°):** You stay in the air for a long time, but you have very little horizontal progress. You have the "time" but no "speed."
* **The 45° Balance:** This is the perfect compromise where the horizontal and vertical velocity components are exactly equal ($v_x = v_y$). 



### 📊 Symmetry Observation
An interesting property of the range formula $\sin(2\theta)$ is its symmetry. Notice that:
* Launch at **30°** $\rightarrow \sin(60°) \approx 0.866$
* Launch at **60°** $\rightarrow \sin(120°) \approx 0.866$

Complementary angles ($\theta$ and $90^\circ - \theta$) will always land at the **same spot**, but **45°** stands alone at the peak of the curve as the unique maximum.

---
