<h1 align='center'>Code for the paper "Underdamped Langevin MCMC with third order convergence"</h1>
<h2 align='center'>by Maximilian Scott, Dáire O'Kane, Andraž Jelinčič and James Foster</h2>

The paper is available at TBA.

This repository is based on the Diffrax package by Patrick Kidger, which is available at [github.com/patrick-kidger/diffrax](https://github.com/patrick-kidger/diffrax).
The documentation for Diffrax can be found at [docs.kidger.site/diffrax](https://docs.kidger.site/diffrax).

For results regarding the strong order of convergence of QUICSORT compared to some other solvers,
see `notebooks/langevin_order.ipynb`.

The main entry point for the Bayesian Logistic Regression example is in `mcmc/progressive_run.py`.
Pregenerated plots can be found in `mcmc/progressive_results/good_plots/`.
For an experiment showing the strong order of convergence on the Bayesian Logistic Regression model, see `notebooks/logreg_order.ipynb`.

To use the code, clone this repository and install the requirements:

```bash
git clone https://github.com/your-username-here/ThirdOrderLMC.git
cd ThirdOrderLMC/
pip install -e .
```