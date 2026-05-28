# Kirchhoff’s Laws – Ammeter Current Calculation

## Problem

Calculate the current flowing through the ammeter in the circuit below.

- \( \mathcal{E}_1 = 9\text{ V} \)
- \( \mathcal{E}_2 = 4.5\text{ V} \)
- Internal resistances: \( r_w = 1\Omega \)
- \( R_1 = 10\Omega \)
- \( R_2 = 20\Omega \)

---

# Step 1 — Define Currents

Let:

- \( I_2 \) = current through the ammeter and \(R_2\)
- \( I_1 \) = current in the outer loop

Using Kirchhoff’s Voltage Law (KVL), we write equations for both loops.

---

# Step 2 — Inner Loop Equation

Components in the inner loop:

- \(4.5\text{ V}\) battery
- internal resistance \(1\Omega\)
- resistor \(20\Omega\)

Applying KVL:

\[
4.5 - I_2(1+20) + V = 0
\]

Simplify:

\[
V = 21I_2 - 4.5
\]

---

# Step 3 — Outer Loop Equation

Components in the outer loop:

- \(9\text{ V}\) battery
- internal resistance \(1\Omega\)
- resistor \(10\Omega\)

Applying KVL:

\[
V = 9 - I_1(1+10)
\]

Simplify:

\[
V = 9 - 11I_1
\]

---

# Step 4 — Voltage Across \(R_1\)

Current through \(R_1\):

\[
I_{R_1} = I_1 - I_2
\]

Voltage across \(R_1\):

\[
V = 10(I_1 - I_2)
\]

Now substitute into both equations:

## Equation (1)

\[
10(I_1-I_2)=21I_2-4.5
\]

\[
10I_1 - 31I_2 = -4.5
\]

---

## Equation (2)

\[
10(I_1-I_2)=9-11I_1
\]

\[
21I_1 - 10I_2 = 9
\]

---

# Step 5 — Solve the System

We now solve:

\[
\begin{cases}
21I_1 - 10I_2 = 9 \\
10I_1 - 31I_2 = -4.5
\end{cases}
\]

Result:

\[
I_2 \approx 0.31\text{ A}
\]

---

# Final Answer

\[
\boxed{I = 0.31\text{ A}}
\]

So, the current flowing through the ammeter is:

## **0.31 A**
