# Santiago Pascual

**Quantitative Research · Scientific Computing · Applied Mathematics**

Based in Buenos Aires, Argentina, I am preparing for undergraduate studies in Physics at the University of Buenos Aires (UBA).

My interests lie at the intersection of mathematics, statistics, financial markets and software engineering. My projects explore systematic decision-making, numerical experimentation, statistical validation and reproducible scientific computing.

I am developing independent programming proficiency in Python and C++, alongside strengthening my mathematical and scientific foundations.

## Selected Projects

### [DÉDALO I — Systematic Futures Research](https://github.com/santiago-pascual/DEDALO-I)

*Flagship quantitative research project · Ongoing*

An independent quantitative research project investigating systematic intraday trading on Micro E-mini Nasdaq-100 futures (MNQ).

- Five-strategy historical research portfolio (P5-R2), combining mean reversion, regime-dependent signals, opening-range breakout and noise-band momentum.
- Causal regime inference using hidden Markov models.
- Matched portfolio comparisons, statistical robustness testing and dependence-aware bootstrap analysis.
- Execution-cost sensitivity, simulated account lifecycles and economic feasibility research.
- Documented simulated execution architecture, checkpoint recovery and operational monitoring.

The extended historical research reference contains 3,858 reconstructed trades from May 2021 to October 2026, reporting $34,893 in net simulated P&L after modeled trading costs.

The matched adaptive-sizing comparison between P4-R2 and P5-R2 reported a 46.98% increase in simulated net P&L and an improvement in daily P&L Sharpe from 1.206 to 1.560.

The research includes 64 historical execution-stress scenarios, paired statistical resampling and 20,000 simulation paths in a separate economic feasibility study.

These results represent historical research evidence, not actual trading income or independently certified forward performance. Full causal reproduction, native execution equivalence and economic feasibility remain open research questions. The available economic evidence does not currently support real-money commitment.

The public repository contains selected research findings, scientific methodology, architectural documentation, limitations and a reproducible synthetic-data demonstration. The operational implementation remains private.

### [ARCHÉ — Quantitative Equity Research](https://github.com/santiago-pascual/ARCHE)

*Exploratory quantitative research · Scientific review and documentation*

My first quantitative finance research project, investigating statistical learning, equity ranking, market regime modeling and portfolio construction.

- Financial time-series analysis and statistical feature engineering.
- Volatility estimation, portfolio construction and exposure management.
- Comparative historical analysis against equity benchmarks.
- Backtest overfitting diagnostics, data leakage investigation and research governance.

A subsequent scientific audit identified important limitations involving data leakage, survivorship bias, historical model selection, performance measurement and reproducibility.

The original codebase was generated entirely through AI, with my contribution focused on defining research questions, exploring methodologies, comparing experiments and evaluating results.

ARCHÉ is preserved as an exploratory research prototype and a record of my transition toward more rigorous quantitative research, rather than a validated investment system.

### [ALPHA AGRO — NASA Space Apps Challenge 2026](https://github.com/santiago-pascual/ALPHA-AGRO)

*Scientific computing · Earth system research*

An independent scientific computing project developed during my solo participation in the 2026 NASA Space Apps Challenge.

The project investigates long-term modeled soil-water storage across the Argentine Pampas using NASA Earth observation and land-surface-model datasets.

- Twenty years of monthly GLDAS data, covering 2006–2025.
- Regional and spatial trend estimation across 867 valid grid cells.
- Statistical inference, uncertainty quantification and multiple-testing correction.
- Retrospective predictive evaluation using statistical and machine-learning models.
- Interactive scientific visualization through a React and TypeScript application.

The estimated regional soil-water trend was −2.83 mm per decade, with a 95% confidence interval of −23.69 to +18.03 mm per decade. The evidence does not establish statistically significant regional drying.

All 18 recorded pre-holdout predictive model selections favored seasonal climatology over more complex alternatives.

The project emphasizes transparent reporting of uncertainty and negative findings. Its experimental outlook interface does not establish operational forecasting capabilities or field-level agricultural recommendations.

### [KineOS — Clinical Operations Software Engineering](https://github.com/santiago-pascual/KineOS-Showcase)

*Proprietary commercial software · Active development*

KineOS is a clinical operations application under development for a physiotherapy clinic in Argentina.

The project focuses on full-stack architecture, relational database design, authentication, authorization, data integrity and privacy-aware software engineering.

- Next.js, React, TypeScript, PostgreSQL and Supabase.
- Authentication, protected navigation and role-based access control.
- Relational database architecture, integrity constraints and audit mechanisms.
- Automated engineering validation and security-oriented development.

The current implementation establishes the application's technical foundation. Complete clinical workflows, security acceptance and production deployment remain pending.

The public repository is a documentation-only engineering case study. The proprietary implementation remains private.

### [Quantitative Risk Analytics — C++](https://github.com/santiago-pascual/cpp-quant-risk-dashboard)

*Numerical software · C++17*

A dependency-free C++17 command-line application for single-asset historical return and risk analysis.

- Simple and logarithmic returns, compound growth and sample variance.
- Historical and rolling volatility, annualization and calendar CAGR.
- Sharpe and Sortino ratios, maximum drawdown, historical Value at Risk and Expected Shortfall.
- Validated chronological CSV ingestion and configurable numerical analysis.
- CMake, CTest and GitHub Actions continuous integration.

Independent NumPy and pandas reference calculations validate 15 scalar metrics and five exported time series.

This project forms part of my structured effort to develop programming fundamentals, numerical accuracy and software testing practices. Its scope is single-asset historical analysis, not a complete portfolio risk management system.

### [Monte Carlo Simulation — C++](https://github.com/santiago-pascual/Montecarlo-Simulation)

*Stochastic simulation · C++17*

A reproducible Monte Carlo simulator for studying fixed-dollar stochastic trading outcomes under an independent Bernoulli model.

- Configurable simulation parameters and reproducible random seeds.
- Terminal wealth distributions, empirical quantiles and expected outcomes.
- Exact analytical validation of terminal wealth moments using a binomial model.
- Path-dependent drawdown and capital-loss probability analysis.
- Automated mathematical tests, CMake and GitHub Actions continuous integration.

The project investigates the relationship between analytical probability distributions and numerical simulation, while documenting the limitations of independent outcomes, constant probabilities and simplified financial assumptions.

## Research Interests

- Systematic trading and empirical asset pricing
- Probability theory and stochastic processes
- Statistical learning and time-series analysis
- Portfolio construction and risk modeling
- Numerical methods and scientific computing
- Computational physics

## Technical Development

### Programming

Currently developing independent proficiency in **Python** and **C++**, with an emphasis on programming fundamentals, numerical methods, software architecture and testing.

### Research and Engineering Technologies

| Area | Technologies and methods |
| --- | --- |
| Scientific computing | NumPy, SciPy, pandas, statsmodels |
| Statistical learning | scikit-learn, XGBoost, hidden Markov models |
| Quantitative research | Time-series analysis, Monte Carlo simulation, bootstrap methods, portfolio risk modeling |
| Scientific data processing | NetCDF, geospatial grid analysis, structured data pipelines |
| Visualization | Matplotlib, Leaflet, Recharts |
| Full-stack development | Next.js, React, TypeScript |
| Database architecture | PostgreSQL, Supabase, relational database design, data integrity constraints |
| Application security | Authentication, authorization, role-based access control, row-level security |
| Numerical software | C++17, Python reference implementations |
| Build and testing | CMake, CTest, pytest, automated numerical validation |
| Development workflows | Git, GitHub, GitHub Actions, VS Code |

These technologies reflect tools and methods used across my projects, including AI-assisted development. Their inclusion does not imply independent mastery of every language, library or methodology.

## Current Work

- Continuing DÉDALO I research, statistical validation and causal execution analysis.
- Investigating economic feasibility under execution costs, funding constraints and account lifecycle restrictions.
- Preparing quantitative research for academic publication.
- Developing KineOS as a proprietary clinical operations software product.
- Developing independent programming proficiency through structured C++ and Python projects.
- Strengthening foundations in mathematics, probability, statistics and physics in preparation for undergraduate studies at UBA.

## Research Philosophy

I approach quantitative research as an empirical discipline. A model is only as useful as the evidence supporting it, the assumptions underlying it and its ability to generalize beyond the observations used to develop it.

My work emphasizes:

- Reproducible experiments and transparent methodology.
- Explicit assumptions, uncertainty and scientific limitations.
- Independent numerical verification where possible.
- Careful separation of historical simulation, reconstructed evidence and forward observations.
- Honest reporting of negative findings, failed hypotheses and unresolved questions.
- Maintainable software architecture, data integrity and responsible engineering.

The objective is not simply to develop more complex models, but to develop a better understanding of when and why they work — and when they do not.

## Development and Authorship

My projects involve AI-assisted research, software development and documentation. My contributions include defining research questions, establishing requirements, directing development, evaluating methodologies and interpreting experimental results.

I distinguish project experience from independently demonstrated programming proficiency and do not claim independent authorship of every software component.

My current objective is to strengthen the mathematical, scientific and programming foundations necessary to conduct increasingly independent research and software development.
