## Task 3 — Geometric Model (Waiting for the First Event)

### 1. Description of the random experiment
The experiment consists of observing consecutively printed pages until the first printing error appears.

Each page can be:
- Correct (C)
- Contains an error (E)

The probability of an error on each page is \( p \), and pages are independent.

---

### 2. Sample space \( \Omega \)

The sample space consists of sequences where the first error appears at position \( k \):

\[
\Omega = \{ E, \; CE, \; CCE, \; CCCE, \; \dots \}
\]

This can be written more generally as:
\[
\Omega = \{ C^{k-1}E \;|\; k = 1,2,3,\dots \}
\]

---

### 3. Probability distribution

Let:
\[
X = \text{number of pages observed until the first error}
\]

Then \( X \) follows a **geometric distribution**:

:contentReference[oaicite:0]{index=0}

for:
\[
k = 1,2,3,\dots
\]

---

### 4. Definition of success

In the geometric model, a "success" is defined as the first occurrence of the event of interest.

Thus:
- Success = A page contains a printing error (E)
- Failure = A page is correct (C)

The random variable \( X \) counts the number of trials (pages) needed to obtain the first success.
