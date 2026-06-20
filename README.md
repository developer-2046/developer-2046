<div align="center">
  <h1>Yuvraj Malik</h1>
  <h3>Math Undergraduate · University of Utah · Spring 2027</h3>

  <p>
    <b>Salt Lake City, UT</b> · 
    <a href="https://developer-2046.github.io/">Portfolio</a> · 
    <a href="https://www.linkedin.com/in/yuvrajmalik/">LinkedIn</a> · 
    <a href="mailto:yuvrajmalik2046@gmail.com">Email</a>
  </p>

  <p>
    I work on stochastic variational inequalities and apply them to equilibrium problems across financial, machine learning, and quantum settings.
  </p>
</div>

---

## Research

### Projected Forward–Backward–Forward for Stochastic Variational Inequalities
*Sole-authored. Under review at Computational Optimization and Applications (Springer).*

Develops last-iterate convergence theory for the projected Forward–Backward–Forward (FBF) method applied to stochastic monotone variational inequalities. Main contributions:
- Explicit characterization of the noise floor under sub-Gaussian oracle perturbations: iterates converge geometrically to a neighborhood of the solution whose size scales as step size × noise variance / strong monotonicity constant.
- Identifies a projection-bias phenomenon in the natural two-call oracle for projected VI methods and provides a modified analysis recovering optimal rates.
- High-probability bounds via sub-Gaussian concentration in the Banach-space setting.

### Shared Risk-Capital Constraints in Dynamic Option Dealer Hedging
*Sole-authored. Submitting to Mathematics and Financial Economics (Springer).*

Applies variational equilibrium theory to multi-dealer option hedging under a shared balance-sheet constraint. Multiple dealers manage option books and trade the underlying to hedge, drawing on a common risk-capital resource. Formulated as a shared-constraint generalized Nash game.
- Proves existence and uniqueness of the variational equilibrium.
- Derives comparative statics for the common multiplier and an envelope formula linking the multiplier to contract-level premia.
- Obtains a first-order implied-volatility wedge from the equilibrium pricing rule.
- Structural simulations illustrate how tighter shared capacity suppresses hedging and produces larger wedges for contracts with higher marginal risk-capital intensity.

### HMM-Based Probabilistic Structural Embedding of Financial Crises
*First-author with H.K. Pharasi. Submitting to Physical Review E.*

Develops a probabilistic structural embedding for financial market crises across major international equity markets. Pipeline includes rolling correlation matrices, spectral features, Mantegna minimum spanning trees, Louvain community detection, and Gaussian HMM inference with BIC-based state selection. Cross-market structural similarity is measured via Jensen–Shannon and Frobenius distances between learned state distributions.

---

## Selected Projects

### The Terminal — Quant Analytics Platform
*Stack: Rust (core), Python (FastAPI), React, PyTorch*

A research platform integrating a Rust-based tick-level backtester with a Python analytics layer.
- Built a `pyo3` binding to a Rust core for backtesting multi-year tick datasets; benchmarked ~1.5× faster than equivalent Python implementations.
- Implemented a market entropy module computing Shannon entropy on rolling correlation matrices of S&P 500 sector indices to detect regime shifts.
- Bayesian signal combination layer fusing news sentiment (LSTM) with realized volatility for conviction sizing.
- Live options chain with Delta/Gamma/Theta from a custom Black-Scholes implementation.

### Hybrid Quantum Amplitude Estimation for Option Pricing
*Stack: Qiskit, Python, NumPy*

Pricing pipeline combining quantum amplitude estimation (QAE) with randomized quasi-Monte Carlo (RQMC) for European option pricing.
- Hybrid QAE/RQMC achieves ~45× variance reduction relative to standard Monte Carlo at comparable shot counts.
- Implements IQAE (Iterative Quantum Amplitude Estimation) and benchmarks against classical RQMC baselines.

### Air Quality Forecasting with Graph Neural Networks
*Award: NVIDIA's Choice — Breath of Fresh Air Hackathon*

GCN-LSTM model treating air quality sensors as a graph to capture spatial correlation alongside temporal dynamics. Trained on NVIDIA GPUs with mixed-precision tensors.

### Mirror-Prox Solver for Inverse Voting Problem
*Context: COMAP MCM 2026*

Custom numerical solver for monotone variational inequalities applied to recovering hidden distributions from binary outcome data. Implements the Mirror-Prox (extragradient) algorithm with O(1/t) convergence on the gap function. Applied to reconstructing fan vote shares from elimination outcomes in a structured inverse problem.

---

## Competitions

| Event | Result |
| :--- | :--- |
| Intercollegiate Math Tournament (ICMT) 2026 | Team: 5th · Individual: 11th · Power Round: 5th · Constellation Round: 7th |
| Lucid Software Global Programming Competition | 1st place, 500+ competitors |
| MIT iQuHACK 2026 | Top 6% global (35/600) |
| ICPC Rocky Mountain Regional | 8th (top University of Utah team) |
| NVIDIA Breath of Fresh Air Hackathon | NVIDIA's Choice Award |

---

## Technical

**Languages:** Python, Rust, C++, Java, SQL  
**Libraries:** PyTorch, NumPy, Pandas, scikit-learn, PyO3, Qiskit  
**Mathematics:** Convex optimization, stochastic processes, variational inequalities, random matrix theory, monotone operator theory, to calculus, SDEs, martingales, Black-Scholes, Heston, Monte Carlo, randomized
QMC, Greeks, variational inequalities.
**Tools:**  Linux, Git, LaTeX, FastAPI, pyo3, Plotly.
