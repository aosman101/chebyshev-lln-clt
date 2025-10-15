# Chebyshev, LLN & CLT (Data Science)

This lab notebook explores foundational probability concepts and their empirical behaviour:
- Building an **idealised binomial distribution** (Pascal’s triangle) and coin-flip experiments
- The **Law of Large Numbers (LLN)**: sample means stabilizing as n grows
- The **Central Limit Theorem (CLT)**: distribution of sample means
- **Chebyshev’s inequality** on a discrete die, plus **tail-probability checks** for Uniform, Normal, and Gamma distributions

> Notebook: `lab05_chebyshev_lln_clt.ipynb` (rename your original “Lab5 solutions.ipynb” to this filename)

---

## Contents

1. **Idealised population distribution (Binomial)**
   - Recursive binomial coefficients (Pascal’s triangle)
   - Visualising distribution and zoomed ranges
2. **Law of Large Numbers (LLN)**
   - Repeated sampling with fixed mean/variance (`np.random.seed(1)` used for reproducibility)
   - Error behaviour vs. sample size
3. **Central Limit Theorem (CLT)**
   - Sampling distributions of the mean
   - Histogram/plots of sample means
4. **Chebyshev’s Inequality (Die example)**
   - Expected value and variance of a fair die
   - Comparing empirical probability outside ±a with `Var(X)/a²`
5. **Tail Probability Comparisons**
   - Functions for **Uniform**, **Normal**, and **Gamma** tails
   - Verifying Chebyshev’s bound vs. actual tail probabilities (`scipy.stats`)

---

## Structure

├─ chebyshev_lln_clt.ipynb   # main lab notebook.

├─ README.md.

└─ (optional) requirements.txt     # pin versions if you like.
