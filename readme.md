# 🧮 NITN-StatX (Python)

**NITN-StatX** is an open-source **probabilistic and statistical computing library** built by **NIT Nagaland** Coding Club.  
It provides lightweight, fast, and easy-to-use tools for distributions, hypothesis testing, sampling, Bayesian inference, and time series analysis.

## 🚀 Features
- Common Distributions (Normal, Uniform, Exponential, Poisson)
- PDF, CDF, Quantiles, Random Sampling
- Hypothesis Testing (t-test, Chi-Square, KS)
- MCMC Samplers (Metropolis-Hastings, Gibbs)
- Bayesian Updating (Conjugate Priors)
- Time Series Decomposition, ARIMA Skeleton, Kalman Filter
- Deterministic RNG with seeds

## 🧰 Installation
```bash
pip install nitn-statx
```

## 🧪 Quick Start

```python
from nitn_statx.distributions import Normal
from nitn_statx.stats import t_test

# Normal Distribution
dist = Normal(mu=0, sigma=1)
p_value = dist.cdf(1.96)
samples = dist.sample(1000)

# t-test example
result = t_test([1,2,3], [2,3,4])
print(result)
```

## 📂 Project Structure

```
nitn-statx-py/
├── src/
│   ├── distributions/
│   ├── stats/
│   ├── sampling/
│   ├── bayesian/
│   └── timeseries/
├── tests/
├── examples/
└── README.md
```

## 🤝 Contributing

We welcome contributions from students, alumni, and the open-source community.

1. Fork the repository  
2. Create a new feature branch (`git checkout -b feature/YourFeature`)  
3. Commit your changes (`git commit -m 'Add some feature'`)  
4. Push to the branch (`git push origin feature/YourFeature`)  
5. Open a Pull Request  

Please write unit tests for new functionality and ensure all existing tests pass. Follow PEP 8 style guidelines.

For full details, see our [contribution guidelines](CONTRIBUTING.md) — but note: this project follows a simple, beginner-friendly workflow focused on clarity and correctness.

## 📜 License

This project is licensed under the **MIT License**:

## 🧑‍💻 Maintainers

* NIT Nagaland Coding Club  
* [GitHub Organization](https://github.com/NITN-Coding-Club)
