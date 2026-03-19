# 🛣️ 3. Path Intersection: The Near Miss

In physics, there is a crucial difference between **sharing a space** and **sharing a moment**. This problem explores the geometry of two moving objects: Alice and Bob.

---

### 🏃 The Movement Profiles

* **Alice's Path $A(t)$:** $(2+t, 8-3t)$  
    *Starts at $(2, 8)$, moving right and sharply downwards.*
* **Bob's Path $B(t)$:** $(2t-1, 2t+2)$  
    *Starts at $(-1, 2)$, moving right and upwards.*



---

### 🔍 The Geometry: Where do the roads cross?

To find if their "footprints" ever overlap, we don't care if they are there at the same time. We just want to find a coordinate $(x, y)$ that satisfies both path equations.

1.  **Match X-coordinates:** $2 + t_1 = 2t_2 - 1 \implies \mathbf{t_1 = 2t_2 - 3}$
2.  **Match Y-coordinates:** $8 - 3t_1 = 2t_2 + 2$

By substituting Alice's time ($t_1$) into the second equation:
$$8 - 3(2t_2 - 3) = 2t_2 + 2$$
$$8 - 6t_2 + 9 = 2t_2 + 2$$
$$17 - 6t_2 = 2t_2 + 2 \implies 8t_2 = 15 \implies \mathbf{t_2 = 1.875}$$

Plugging $t_2$ back in gives us Alice's time: **$t_1 = 0.75$**.

> **The Intersection Point:** By plugging $t_1$ into $A(t)$ or $t_2$ into $B(t)$, we find the coordinates:
> $$\mathbf{P = (2.75, 5.75)}$$

---

### ⚠️ The Verdict: Intersection vs. Collision

Here is the twist. While the **paths** cross at $(2.75, 5.75)$, do the **people** meet?

* **Alice** reaches the crossing point at **$t = 0.75$ seconds**.
* **Bob** reaches the crossing point at **$t = 1.875$ seconds**.



**Conclusion:** Alice passes through the intersection long before Bob even gets there. They share the same ground, but they are separated by **1.125 seconds** of time. 

**Result:** ✅ Intersection | ❌ Collision

---

### 📏 Proximity: How close were they?

Since they don't collide, we could calculate the **Minimum Distance** between them by minimizing the distance function $D(t) = \sqrt{(x_A-x_B)^2 + (y_A-y_B)^2}$. This would tell us exactly how "near" this near-miss actually was!
