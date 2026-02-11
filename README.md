<div align="center">
  <h1>Yuvraj Malik</h1>
  <h3>Quant Developer | Applied Mathematics | Systems Engineer</h3>

  <p>
    <b>Salt Lake City, UT</b> • 
    <a href="https://yuvraj-malik.netlify.app/">Portfolio ↗</a> • 
    <a href="https://www.linkedin.com/in/yuvrajmalik/">LinkedIn ↗</a> • 
    <a href="mailto:yuvrajmalik2046@gmail.com">Email</a>
  </p>

  <p>
    I build production-grade systems that <i>learn, scale, and resist failure</i>. <br>
    My work sits at the intersection of <b>Low-Latency Systems (Rust/C++)</b>, <b>Statistical Learning</b>, and <b>Market Microstructure</b>.
  </p>

  <p>
    <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
    <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
    <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  </p>
</div>

---

## 🚀 Flagship Engineering

### 1. The Terminal: Quant Analytics Platform
> **Stack:** Rust (Core), Python (FastAPI), React, PyTorch, Black-Scholes

A high-performance hybrid trading platform designed for sophisticated market analysis.
* **Rust-Powered Backtester:** Engineered a `pyo3` binding to a Rust core, enabling lightning-fast simulation of tick-level strategies over multi-year datasets.
* **Market Entropy Engine:** Implements **Shannon Entropy** on rolling correlation matrices (S&P 500 sectors) to detect regime shifts (Stable vs. Chaotic) in real-time.
* **Bayesian Signal Fusion:** Uses a Bayesian inference engine to combine **News Sentiment (LSTM)** with volatility signals for dynamic conviction sizing.
* **Real-Time Greeks:** Renders live options chains with Delta/Gamma/Theta calculations via a custom Black-Scholes implementation.

### 2. Air Quality Forecasting via Geometric Deep Learning
> **Award:** 🏆 NVIDIA's Choice Award (Breath of Fresh Air Hackathon)

Solved the "spatial correlation" problem in air quality forecasting using Graph Neural Networks.
* **Model:** Built a **GCN-LSTM** (Graph Convolutional Network + LSTM) to model air sensors as a graph, capturing non-Euclidean spatial dependencies.
* **Impact:** Improved forecasting accuracy ($R^2$) from **0.642 to 0.872**, outperforming standard time-series baselines.
* **Optimization:** Optimized training pipelines on NVIDIA GPUs using mixed-precision tensors.

### 3. Maximum-Entropy Variational Inequality Solver
> **Context:** COMAP MCM 2026 (Outstanding Winner Nominee - Team 2618069)

A custom numerical optimization engine built to solve inverse problems with rigid inequality constraints.
* **The Math:** Implemented the **Mirror-Prox (Extragradient)** algorithm to solve monotone Variational Inequalities (VIs) with $O(1/t)$ convergence.
* **The Application:** Reconstructed hidden "Fan Vote Shares" from binary elimination data (Dancing with the Stars), successfully converging on high-entropy distributions where standard solvers failed.

---

## 🔬 Selected Research

### **Linear Convergence of Projected Extragradient Methods**
* **Submission:** COLT 2026 (Computational Learning Theory)
* **Problem:** Gradient Descent-Ascent (GDA) often oscillates or diverges in continuous games (e.g., GAN training).
* **Contribution:** We analyzed Tseng’s **Forward-Backward-Forward (FBF)** scheme, providing a self-contained proof of last-iterate linear convergence. We introduced novel "symmetric Jacobian certificates" to verify stability conditions and extended guarantees to stochastic settings with high-variance feedback.

### **Classifying Market Crashes via Spectral Entropy**
* **Focus:** Econophysics / Random Matrix Theory
* **Methodology:** Analyzing the eigen-entropy of financial correlation matrices (S&P 500, 2008–2024). The study isolates "critical events" (crashes) by detecting breakdown in the dominant market mode, serving as a signal for regime-switching algorithms.

---

## 🏆 Competitive Achievements

| Event | Rank / Award | Details |
| :--- | :--- | :--- |
| **Lucid Software Global Programming** | **1st Place** | Outperformed 500+ competitors (incl. PhDs) with a parallelized heuristic search in Rust. |
| **MIT iQuHACK 2026** | **Top 6% (Global)** | **Rank 35/600**. Built a quantum "peak-finder" pipeline to extract high-prob bitstrings from 46-qubit circuits. |
| **NVIDIA AI Hackathon** | **NVIDIA's Choice** | Won "Best Model" for the GCN-LSTM air quality forecaster ($R^2=0.872$). |
| **ICPC Rocky Mountain Regional** | **Rank 8 (Top 10)** | Top University of Utah team. Solved 8/12 algorithmic problems under strict time constraints. |

---

## 🔧 Technical Arsenal

* **Languages:** Python, Rust, C++, Java, SQL, Julia, R.
* **Quant & ML:** PyTorch, NumPy/Pandas, Scikit-learn, PyO3, Polars.
* **Math:** Convex Optimization, Stochastic Processes, Graph Theory, Random Matrix Theory.
* **Infrastructure:** Docker, Linux (Arch/Debian), Git, CI/CD, Grafana.

---

<div align="center">
  <i>"Don’t just learn code. Build with it, break it, and push it to the limit."</i>
</div>
