## Task 2 — Hypergeometric Model (Sampling from a Batch)

### 1. Description of the random experiment
The experiment consists of randomly selecting 4 components from a batch of 20 components:
- 5 defective (D)
- 15 functional (F)

The selection is done **without replacement**, so probabilities change after each draw.

---

### 2. Definition of the random variable \( X \)

Let:
\[
X = \text{number of defective components in the selected sample of 4}
\]

---

### 3. Possible values of \( X \)

The number of defective items drawn cannot exceed:
- the total drawn (4), or
- the total defective available (5)

Thus:
\[
X \in \{0, 1, 2, 3, 4\}
\]

---

### 4. Probability distribution of \( X \)

This follows a **hypergeometric distribution**:

\[
P(X = k) = \frac{\binom{5}{k} \binom{15}{4 - k}}{\binom{20}{4}}, \quad k = 0,1,2,3,4
\]

Explicitly:

- \( P(X = 0) = \dfrac{\binom{5}{0}\binom{15}{4}}{\binom{20}{4}} \)
- \( P(X = 1) = \dfrac{\binom{5}{1}\binom{15}{3}}{\binom{20}{4}} \)
- \( P(X = 2) = \dfrac{\binom{5}{2}\binom{15}{2}}{\binom{20}{4}} \)
- \( P(X = 3) = \dfrac{\binom{5}{3}\binom{15}{1}}{\binom{20}{4}} \)
- \( P(X = 4) = \dfrac{\binom{5}{4}\binom{15}{0}}{\binom{20}{4}} \)

---

### 5. Definition of success

In the hypergeometric model, a "success" is defined as selecting a defective component.

Thus:
- Success = Defective component
- Failure = Functional component

The random variable \( X \) counts the number of successes (defective components) in the sample of 4.
