# Kirchhoff’s Laws — Ammeter Current Calculation

## Problem

Calculate the current flowing through the ammeter.

---

## Given Values

| Quantity             | Value          |
| -------------------- | -------------- |
| $\mathcal{E}_1$      | $9\text{ V}$   |
| $\mathcal{E}_2$      | $4.5\text{ V}$ |
| Internal resistances | $1\Omega$ each |
| $R_1$                | $10\Omega$     |
| $R_2$                | $20\Omega$     |

---

# Step 1 — Define Mesh Currents

Let:

* $I_1$ = current in the outer loop
* $I_2$ = current in the inner loop (through the ammeter)

The resistor $R_1$ is shared by both loops.

Therefore, the current through $R_1$ is:

$$
I_{R_1} = I_1 - I_2
$$

---

# Step 2 — Apply Kirchhoff’s Voltage Law (KVL)

## Outer Loop

Applying KVL clockwise:

$$
9 - 1I_1 - 10(I_1 - I_2) = 0
$$

Expand:

$$
9 - I_1 - 10I_1 + 10I_2 = 0
$$

$$
11I_1 - 10I_2 = 9
$$

---

## Inner Loop

Applying KVL clockwise:

$$
4.5 - 1I_2 - 20I_2 - 10(I_2 - I_1) = 0
$$

Expand:

$$
4.5 - 21I_2 - 10I_2 + 10I_1 = 0
$$

$$
10I_1 - 31I_2 = -4.5
$$

---

# Step 3 — Solve the System

We now solve the system:

$$
\begin{cases}
11I_1 - 10I_2 = 9 \
10I_1 - 31I_2 = -4.5
\end{cases}
$$

Multiply the first equation by $10$:

$$
110I_1 - 100I_2 = 90
$$

Multiply the second equation by $11$:

$$
110I_1 - 341I_2 = -49.5
$$

Subtract the equations:

$$
241I_2 = 139.5
$$

$$
I_2 \approx 0.579\text{ A}
$$

---

# Final Answer

The current through the ammeter is:

$$
\boxed{0.58\text{ A}}
$$
