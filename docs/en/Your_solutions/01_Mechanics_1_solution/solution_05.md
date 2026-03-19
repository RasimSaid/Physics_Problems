# 🌊 5. Relative Velocity: Outsmarting the Current

When moving in a medium like water or air, your **resultant velocity** is the vector sum of your engine's power and the environment's force. To go directly North across a flowing river, you can't just point North—you have to fight the drift.

---

### 🚣 The Strategic Setup
* **River Velocity ($v_r$):** $2 \text{ m/s}$ (flowing East $\rightarrow$)
* **Boat Speed ($v_b$):** $5 \text{ m/s}$ (relative to water)
* **Goal:** A perfect Northward trajectory (Zero drift).



---

### 📐 The Calculation: Finding the "Crab" Angle

To keep the boat from being swept East, the boat must head **West of North** at an angle $\theta$. The horizontal component of the boat's velocity ($v_b \sin\theta$) must exactly cancel the river's speed ($2 \text{ m/s}$).

$$5 \cdot \sin\theta = 2$$
$$\sin\theta = \frac{2}{5} = 0.4$$
$$\mathbf{\theta = \arcsin(0.4) \approx 23.58^\circ}$$

> **Kaptan'ın Notu:** Pruvayı kuzeyden batıya doğru tam **23.58°** kırmalısın. Bu açı, akıntının seni rotandan saptırmasını engelleyen "denge açısı"dır.

---

### ⏱️ The Crossing: How Fast are we Actually Moving?

Since some of your engine's power is spent fighting the current, your **effective speed** ($v_{resultant}$) straight across the river is slightly less than your maximum $5 \text{ m/s}$. We find this using the vertical component:

$$v_y = v_b \cdot \cos(23.58^\circ)$$
$$v_y = 5 \cdot 0.916 \approx \mathbf{4.58 \text{ m/s}}$$

**Time to Cross (200m wide river):**
$$t = \frac{\text{Distance}}{\text{Effective Speed}}$$
$$t = \frac{200}{4.58} \approx \mathbf{43.6 \text{ s}}$$



---

### 💡 Result Summary
* **Steering Angle:** $23.58^\circ$ West of North.
* **Resultant Speed:** $4.58 \text{ m/s}$ (directly North).
* **Total Time:** $43.6$ seconds.

Without the river, it would take only $40$ seconds ($200/5$). The river "costs" us an extra $3.6$ seconds of travel time!
