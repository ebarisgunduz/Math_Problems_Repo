## Task 10 — Multinomial Model

Given:
- \( n = 6 \) (number of selections)
- Probabilities:
  - Strawberry: \( p_1 = 0.4 \)
  - Lemon: \( p_2 = 0.35 \)
  - Mint: \( p_3 = 0.25 \)

We want:
- \( X_1 = 3 \) (strawberry)
- \( X_2 = 2 \) (lemon)
- \( X_3 = 1 \) (mint)

---

### Multinomial probability formula

\[
P = \frac{6!}{3! \, 2! \, 1!} (0.4)^3 (0.35)^2 (0.25)^1
\]

---

### Step-by-step calculation

\[
\frac{6!}{3!2!1!} = \frac{720}{6 \cdot 2 \cdot 1} = 60
\]

\[
(0.4)^3 = 0.064
\]

\[
(0.35)^2 = 0.1225
\]

\[
(0.25)^1 = 0.25
\]

Now multiply:

\[
P = 60 \cdot 0.064 \cdot 0.1225 \cdot 0.25
\]

\[
P \approx 60 \cdot 0.00196 \approx 0.1176
\]

---

### Final answer

\[
\boxed{P \approx 0.1176}
\]
