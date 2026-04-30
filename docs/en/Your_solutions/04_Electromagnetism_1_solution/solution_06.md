# 6. Electric field from a system of charges

Two point charges are given:

- $+q$ at $(-a, 0)$  
- $+2q$ at $(a, 0)$  

We use Coulomb’s law in vector form:

$$
\vec E(\vec r) = \frac{1}{4\pi \varepsilon_0} \sum_i q_i \frac{\vec r - \vec r_i}{|\vec r - \vec r_i|^3}
$$

---

## 1. Electric field expressions

### General point $(x, y)$

Position vectors:

- $\vec r_1 = (-a, 0)$  
- $\vec r_2 = (a, 0)$  
- $\vec r = (x, y)$  

Vectors from charges:

$$
\vec r - \vec r_1 = (x+a, y)
$$
$$
\vec r - \vec r_2 = (x-a, y)
$$

Thus:

$$
\vec E(x,y) = \frac{1}{4\pi \varepsilon_0} \left[
q \frac{(x+a, y)}{\left((x+a)^2 + y^2\right)^{3/2}} +
2q \frac{(x-a, y)}{\left((x-a)^2 + y^2\right)^{3/2}}
\right]
$$

---

### Along the y-axis $(0, y)$

Set $x=0$:

$$
\vec E(0,y) = \frac{1}{4\pi \varepsilon_0} \left[
q \frac{(a, y)}{(a^2 + y^2)^{3/2}} +
2q \frac{(-a, y)}{(a^2 + y^2)^{3/2}}
\right]
$$

Components:

$$
E_x = -\frac{q a}{4\pi \varepsilon_0 (a^2+y^2)^{3/2}}
$$

$$
E_y = \frac{3q y}{4\pi \varepsilon_0 (a^2+y^2)^{3/2}}
$$

---

### Along the x-axis $(x, 0)$

Set $y=0$:

$$
E_x = \frac{1}{4\pi \varepsilon_0} \left[
\frac{q(x+a)}{|x+a|^3} + \frac{2q(x-a)}{|x-a|^3}
\right], \quad E_y = 0
$$

---

## 2. Conditions for zero components

### Condition for $E_y = 0$

$$
E_y \propto y \Rightarrow y = 0
$$

---

### Condition for $E_x = 0$ (on y-axis)

$$
E_x = -\frac{q a}{4\pi \varepsilon_0 (a^2+y^2)^{3/2}} \neq 0
$$

No solution.

---

### Condition for $\vec E = 0$

From $E_y = 0 \Rightarrow y=0$

Solve on x-axis:

$$
\frac{1}{(x+a)^2} = \frac{2}{(x-a)^2}
$$

$$
(x-a)^2 = 2(x+a)^2
$$

$$
x^2 - 2ax + a^2 = 2x^2 + 4ax + 2a^2
$$

$$
0 = x^2 + 6ax + a^2
$$

$$
x = -3a \pm 2\sqrt{2}a
$$

---

## 3. Numerical calculation

Given:

- $a = 0.2\,\text{m}$
- $y = 0.3\,\text{m}$
- $q = 2\times 10^{-6}\,\text{C}$
- $k = 9\times 10^9$

Compute:

$$
a^2 + y^2 = 0.13
$$

$$
(0.13)^{3/2} \approx 0.0469
$$

### $E_x$

$$
E_x \approx -7.67 \times 10^4 \ \text{N/C}
$$

### $E_y$

$$
E_y \approx 3.45 \times 10^5 \ \text{N/C}
$$

### Final vector

$$
\vec E(0,0.3) \approx (-7.67\times10^4, \ 3.45\times10^5)\ \text{N/C}
$$

---

## 4. Limit $y \gg a$

$$
(a^2 + y^2)^{3/2} \approx y^3
$$

$$
E_x \approx -\frac{kqa}{y^3}
$$

$$
E_y \approx \frac{3kq}{y^2}
$$

---

### Interpretation

- Field behaves like a single charge $3q$
- $E_x \ll E_y$
- Field becomes nearly vertical
