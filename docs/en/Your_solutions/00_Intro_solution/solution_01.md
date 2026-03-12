# Section 0: Mathematical Foundations — Solutions

## 1. Vector Algebra

Given

$$
\vec{a} = [2,1,-3], \quad \vec{b} = [4,-2,1]
$$

### a) Magnitudes of the vectors

The magnitude formula is

$$
|\vec{v}| = \sqrt{x^2 + y^2 + z^2}
$$

For $\vec{a}$:

$$
|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2}
= \sqrt{4+1+9}
= \sqrt{14}
$$

For $\vec{b}$:

$$
|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2}
= \sqrt{16+4+1}
= \sqrt{21}
$$

### b) Dot product

The dot product formula is

$$
\vec{a}\cdot\vec{b} = a_x b_x + a_y b_y + a_z b_z
$$

So,

$$
\vec{a}\cdot\vec{b} = (2)(4) + (1)(-2) + (-3)(1)
= 8 - 2 - 3
= 3
$$

### c) Cross product

The cross product is

$$
\vec{a}\times\vec{b}
=
\begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\
2 & 1 & -3 \\
4 & -2 & 1
\end{vmatrix}
$$

Expanding:

$$
\vec{a}\times\vec{b}
=
\hat{i}(1\cdot1 - (-3)(-2))
-
\hat{j}(2\cdot1 - (-3)(4))
+
\hat{k}(2\cdot(-2) - 1\cdot4)
$$

$$
=
\hat{i}(1-6) - \hat{j}(2+12) + \hat{k}(-4-4)
$$

$$
=
-5\hat{i} - 14\hat{j} - 8\hat{k}
$$

Therefore,

$$
\vec{a}\times\vec{b} = [-5,-14,-8]
$$

### d) Angle between the vectors

Use

$$
\cos\theta = \frac{\vec{a}\cdot\vec{b}}{|\vec{a}||\vec{b}|}
$$

Substitute the values:

$$
\cos\theta = \frac{3}{\sqrt{14}\sqrt{21}}
= \frac{3}{\sqrt{294}}
$$

$$
\theta = \cos^{-1}\left(\frac{3}{\sqrt{294}}\right)
\approx 79.9^\circ
$$

### Final answers for Question 1

$$
|\vec{a}| = \sqrt{14}, \quad |\vec{b}| = \sqrt{21}
$$

$$
\vec{a}\cdot\vec{b} = 3
$$

$$
\vec{a}\times\vec{b} = [-5,-14,-8]
$$

$$
\theta \approx 79.9^\circ
$$

---