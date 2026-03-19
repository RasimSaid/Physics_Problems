# 🧭 4. Vector Calculus: The Anatomy of a Trajectory

Position is where you are, velocity is where you're going, and acceleration is how your "going" is changing. Let's break down the object's DNA using the power of derivatives.

---

### 📍 The Position Vector $\vec{r}(t)$
The object follows a path defined by:
$$\vec{r}(t) = \underbrace{(3t^2)}_{\mathbf{x(t)}} \hat{i} + \underbrace{(5t - 8t^2)}_{\mathbf{y(t)}} \hat{j}$$

* **X-axis:** The object moves rightward with increasing speed ($t^2$ dependence).
* **Y-axis:** It's a tug-of-war! It starts by moving up ($5t$) but eventually gets pulled down by a stronger quadratic force ($-8t^2$).



---

### ⚡ The Velocity Vector $\vec{v}(t)$
Velocity is the **rate of change** of position. We find it by taking the first derivative:
$$\vec{v}(t) = \frac{d\vec{r}}{dt} = \frac{d}{dt}(3t^2)\hat{i} + \frac{d}{dt}(5t - 8t^2)\hat{j}$$

$$\mathbf{\vec{v}(t) = (6t)\hat{i} + (5 - 16t)\hat{j}}$$

* **Interpretation:** Notice how the horizontal velocity grows linearly, while the vertical velocity starts positive ($5$) and becomes increasingly negative. At $t = 5/16$ seconds, the object reaches its peak vertical height!



---

### 🏎️ The Acceleration Vector $\vec{a}(t)$
Acceleration tells us about the **forces** acting on the object. We take the derivative of velocity:
$$\vec{a}(t) = \frac{d\vec{v}}{dt} = \frac{d}{dt}(6t)\hat{i} + \frac{d}{dt}(5 - 16t)\hat{j}$$

$$\mathbf{\vec{a}(t) = 6\hat{i} - 16\hat{j}}$$



### 💡 Key Insight: Constant Force
Unlike the position and velocity, the **acceleration is constant**. 
* Magnitude: $|\vec{a}| = \sqrt{6^2 + (-16)^2} = \sqrt{36 + 256} \approx \mathbf{17.09 \text{ m/s}^2}$
* This suggests a steady engine push to the right ($6\hat{i}$) and a strong, constant downward pull ($-16\hat{j}$), similar to gravity but much stronger!

---
