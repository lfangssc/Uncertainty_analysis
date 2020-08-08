# Uncertainty_analysis
## Quantitative methods

1. Sensitivity analysis.   This assesses how changing inputs to a model or an analysis can affect the results.  It is undertaken by repeatedly rerunning the analysis, incrementally changing target variables on each occasion, either one at a time or in combination  It thus allows the relative effects of different parameters to be identified and assessed.  It is especially useful for analysing the assumptions made in assessment scenarios (e.g. by changing the emissions or to explote best and worst case situations).   The main limitation of sensitivity analysis is that it becomes extremely complex if uncertainties arise through interactions between a large number of variables, because of the large number of permutations that might need to be considered.

2. Taylor Series Approximation.  This is a mathematical technique to approximate the underlying distribution that characterises uncertainty in a process.  Once such an approximation is found, it is computationally inexpensive and so is useful when dealing with  large and complex models for which more sophisticated methods may be infeasible.

3. Monte Carlo simulation.  This is a reiterative process of analysis, which uses repeated samples from probability distributions as the inputs for models.  It thus generates a distribution of outputs which reflects the uncertainties in the models. Monte Carlo simulation is a very useful technique when the assessment concerns the probability of exceeding a specified (e.g. safe) limit, or where models are highly non-linear, but it can be computationally expensive.

4. Bayesian statistical modeling.  The preceding approaches all apply to deterministic models. In practice, many of the parameters in these models have been estimated from data but are then, at least initially, treated as known and fixed entities in the models. Stochastic models estimate the parameters from the data and fit the model in one step, thereby directly incorporating uncertainty in the parameter estimates due to imperfections in the data.  Bayesian modelling goes one step further and incorporates additional uncertainty in the parameters from other sources (expressed in terms of probability distributions).

[Crystalball](https://www.oracle.com/applications/crystalball/): a spreadsheet-based software suite for predictive modeling, forecasting, Monte Carlo simulation and optimization

[IEHIAS](http://www.integrated-assessment.eu/eu/guidebook/methods_uncertainty_analysis.html): case studies


[pandas-montecarlo](https://pypi.org/project/pandas-montecarlo/): python package
