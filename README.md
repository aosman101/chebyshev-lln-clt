# Chebyshev, LLN & CLT (Data Science)

This lab notebook examines fundamental concepts of probability and their practical applications.
- Building an **idealised binomial distribution** (Pascal’s triangle) and coin-flip experiments.
- The **Law of Large Numbers (LLN)**: sample means stabilising as n grows.
- The **Central Limit Theorem (CLT)**: distribution of sample means.
- **Chebyshev’s inequality** on a discrete die, plus **tail-probability checks** for Uniform, Normal, and Gamma distributions.

> Notebook: `chebyshev_lln_clt.ipynb`.

---

## Contents

1. **Idealised population distribution (Binomial)**
   - Recursive binomial coefficients (Pascal’s triangle).
   - Visualising distribution and zoomed ranges.
2. **Law of Large Numbers (LLN)**
   - Repeated sampling with fixed mean/variance (`np.random.seed(1)` used for reproducibility).
   - Error behaviour vs. sample size.
3. **Central Limit Theorem (CLT)**
   - Sampling distributions of the mean.
   - Histogram/plots of sample means.
4. **Chebyshev’s Inequality (Die example)**
   - Expected value and variance of a fair die.
   - Comparing empirical probability outside ±a with `Var(X)/a²`.
5. **Tail Probability Comparisons**
   - Functions for **Uniform**, **Normal**, and **Gamma** tails.
   - Verifying Chebyshev’s bound vs. actual tail probabilities (`scipy.stats`).

---

## Structure

├─ chebyshev_lln_clt.ipynb # Primary laboratory notebook.

├─ README.md.

└─ (optional) requirements.txt # You can pin the versions.
