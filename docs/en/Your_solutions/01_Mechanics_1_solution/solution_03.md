## 3. Path Intersection

Paths: $A(t) = (2+t, 8-3t)$ and $B(t) = (2t-1, 2t+2)$.

* **Intersection Check:** We look for $t_1$ and $t_2$ such that $A(t_1) = B(t_2)$.
    1. $2 + t_1 = 2t_2 - 1 \implies t_1 = 2t_2 - 3$
    2. $8 - 3t_1 = 2t_2 + 2$
    Substitute (1) into (2): $8 - 3(2t_2 - 3) = 2t_2 + 2 \implies 17 - 6t_2 = 2t_2 + 2 \implies 8t_2 = 15 \implies t_2 = 1.875$.
    Then $t_1 = 2(1.875) - 3 = 0.75$.
* **Result:** The paths intersect at point **(2.75, 5.75)**. However, since $t_1 \neq t_2$, they reach this point at different times; therefore, they **do not collide**.

---
