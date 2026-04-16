## Task 4 — Poisson Model (Arrival of Events)

### 1. Description of the random experiment
The experiment consists of counting the number of error reports received by a web service during a fixed time interval (e.g., one hour).

The reports occur randomly over time, and the average number of reports per hour is known to be 3.

---

### 2. Sample space \( \Omega \)

The sample space consists of all possible numbers of error reports in the interval:

\[
\Omega = \{0, 1, 2, 3, \dots\}
\]

---

### 3. Probability distribution

Let:
\[
X = \text{number of error reports in one hour}
\]

Then \( X \) follows a **Poisson distribution**:

:contentReference[oaicite:0]{index=0}

for:
\[
k = 0,1,2,\dots
\]

---

### 4. Interpretation of the parameter \( \lambda \)

The parameter \( \lambda \) represents the **average number of events (error reports) in a given time interval**.

In this case:
\[
\lambda = 3
\]

for one hour, meaning:
- On average, the web service receives **3 error reports per hour**.

Thus, \( \lambda \) is both:
- the mean (expected value), and
- the variance of the Poisson distribution over one hour.
