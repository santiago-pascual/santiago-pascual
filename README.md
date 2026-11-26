# Santiago Pascual

**Quantitative Research · Scientific Computing · Applied Mathematics**

I am an independent researcher and aspiring quantitative researcher based in Buenos Aires, Argentina, currently preparing for undergraduate studies in Physics at the University of Buenos Aires (UBA).

My interests lie at the intersection of mathematics, statistics, software engineering and financial markets. I develop research projects focused on systematic decision-making, numerical experimentation, statistical validation and reproducible scientific computing.

I am currently developing independent programming proficiency in Python and C++, alongside strengthening my mathematical and scientific foundations.

## Selected Projects

### [DÉDALO I — Systematic Futures Research](https://github.com/santiago-pascual/DEDALO-I)

*Flagship research project · Ongoing*

An independent quantitative research project investigating systematic intraday trading on Micro E-mini Nasdaq-100 futures (MNQ).

The research examines multi-strategy portfolio construction, causal regime inference, historical execution modeling and economic feasibility under realistic trading and funding constraints.

- Five-strategy historical research portfolio (P5-R2), combining mean reversion, regime-dependent signals and breakout methodologies.
- Matched portfolio comparisons, statistical robustness testing and dependence-aware bootstrap analysis.
- Execution-cost sensitivity, simulated account lifecycles and risk engineering.
- Documented simulated execution architecture, checkpoint recovery and operational monitoring.

The extended historical reference contains 3,858 reconstructed trades from May 2021 to October 2026, reporting $34,893 in net simulated P&L after modeled trading costs. Matched historical comparisons also investigate the incremental contribution of the fifth strategy.

These results are historical research evidence, not actual trading income or independently certified forward performance. Full causal reproduction, native execution equivalence and economic feasibility remain open research questions.

The public repository contains selected research findings, methodology, architectural documentation, scientific limitations and a reproducible synthetic-data demonstration. The operational implementation remains private.

### [ARCHÉ — Quantitative Equity Research](https://github.com/santiago-pascual/ARCHE)

*Exploratory research framework · Scientific review and documentation*

My first quantitative finance research project, formerly known as The Machine Project.

ARCHÉ explores statistical learning, equity ranking, market regime modeling, volatility estimation, portfolio construction and exposure management.

- Comparative historical portfolio analysis against equity benchmarks.
- Statistical feature engineering and financial time-series modeling.
- Exposure constraints, risk-adjusted performance and drawdown analysis.
- Backtest overfitting diagnostics, data leakage investigation and research governance.

A subsequent scientific audit identified limitations involving data leakage, survivorship bias, historical model selection and reproducibility.

The project was originally developed using AI-generated code, with my contribution focused on research design, methodology exploration and experimental evaluation.

ARCHÉ is preserved as an exploratory research prototype and a record of my transition toward more rigorous quantitative research, rather than a validated investment system.

### [ALPHA AGRO — NASA Space Apps Challenge 2026](https://github.com/santiago-pascual/quant-alpha-agro)

*Scientific computing · Earth system research*

An independent scientific computing project developed during my solo participation in the 2026 NASA Space Apps Challenge.

The project investigates long-term modeled soil-water storage across the Argentine Pampas using NASA Earth observation and land-surface-model datasets.

- Twenty years of monthly GLDAS observations, covering 2006–2025.
- Regional and spatial trend estimation across 867 valid grid cells.
- Statistical inference, uncertainty quantification and multiple-testing correction.
- Retrospective predictive evaluation using statistical and machine-learning models.
- Interactive scientific visualization through a React and TypeScript application.

The estimated regional soil-water trend was −2.83 mm per decade, with a 95% confidence interval of −23.69 to +18.03 mm per decade. The evidence does not establish statistically significant regional drying.

The retrospective predictive research compares more complex models against seasonal climatology and persistence. All 18 recorded pre-holdout model selections favored seasonal climatology.

The project emphasizes transparent reporting of uncertainty and negative findings. Its experimental outlook interface does not establish operational forecasting capabilities or field-level agricultural recommendations.

### [Quantitative Risk Analytics — C++](https://github.com/santiago-pascual/cpp-quant-risk-dashboard)

*Numerical software · C++17*

A dependency-free C++17 command-line application for single-asset historical return and risk analysis.

- Simple and logarithmic returns, compound growth and sample variance.
- Historical and rolling volatility, annualization and calendar CAGR.
- Sharpe and Sortino ratios, maximum drawdown, historical Value at Risk and Expected Shortfall.
- Validated chronological CSV ingestion and configurable numerical analysis.
- Independent NumPy and pandas reference calculations.
- CMake, CTest and GitHub Actions continuous integration.

The independent numerical validation compares 15 scalar metrics and five exported time series against Python reference calculations.

This project forms part of my structured effort to develop programming fundamentals, numerical accuracy and software testing practices.

### [Monte Carlo Simulation — C++](https://github.com/santiago-pascual/Montecarlo-Simulation)

*Stochastic simulation · C++17*

A reproducible Monte Carlo simulator for studying fixed-dollar stochastic trading outcomes under an independent Bernoulli model.

- Configurable simulation parameters and reproducible random seeds.
- Terminal wealth distributions, empirical quantiles and expected outcomes.
- Exact analytical validation of terminal wealth moments using a binomial model.
- Path-dependent drawdown and capital-loss probability analysis.
- Automated mathematical tests, CMake and GitHub Actions continuous integration.

The project investigates the relationship between analytical probability distributions and numerical simulation, while explicitly documenting the limitations of independent outcomes, constant probabilities and simplified financial assumptions.

## Research Interests

- Systematic trading and empirical asset pricing
- Probability theory and stochastic processes
- Statistical learning and time-series analysis
- Portfolio construction and risk modeling
- Numerical methods and scientific computing
- Computational physics

## Technical Development

### Programming

Currently developing independent proficiency in **Python** and **C++**, with an emphasis on programming fundamentals, numerical methods, software design and testing.

### Research and Engineering Technologies

| Area | Technologies and methods |
| --- | --- |
| Scientific computing | NumPy, SciPy, pandas, statsmodels |
| Statistical learning | scikit-learn, XGBoost, hidden Markov models |
| Scientific data processing | NetCDF, geospatial grid analysis, structured data pipelines |
| Visualization | Matplotlib, React, TypeScript, Leaflet, Recharts |
| Numerical software | C++17, Python reference implementations |
| Build and testing | CMake, CTest, pytest, automated numerical validation |
| Development workflows | Git, GitHub, GitHub Actions, VS Code |

These technologies reflect tools and methods used across my projects, including AI-assisted development. Their inclusion does not imply independent mastery of every language, library or methodology.

## Current Work

- Continuing DÉDALO I research, statistical validation and causal execution analysis.
- Investigating economic feasibility under execution costs, funding constraints and account lifecycle restrictions.
- Preparing independent quantitative research for academic publication.
- Developing independent programming proficiency through structured C++ and Python projects.
- Strengthening foundations in mathematics, probability, statistics and physics.
- Preparing for undergraduate Physics studies at the University of Buenos Aires.

## Research Philosophy

I approach quantitative research as an empirical discipline. A model is only as useful as the evidence supporting it, the assumptions underlying it and its ability to generalize beyond the observations used to develop it.

My work emphasizes:

- Reproducible experiments and transparent methodology.
- Explicit assumptions, uncertainty and scientific limitations.
- Independent numerical verification where possible.
- Careful separation of historical simulation, reconstructed evidence and forward observations.
- Honest reporting of negative findings, failed hypotheses and unresolved questions.

The objective is not simply to develop more complex models, but to develop a better understanding of when and why they work — and when they do not.
