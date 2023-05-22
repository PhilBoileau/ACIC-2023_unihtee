# ACIC 2023 Presentation: A Nonparametric Framework for treatment Effect Modifier Discovery in High Dimensions

### Authors

Philippe Boileau, Ning Leng, Nima Hejazi, Mark van der Laan and Sandrine Dudoit

### Abstract

Current approaches for uncovering treatment effect modifiers are limited to
low-dimensional data or data with weakly correlated confounders, or are
restricted to simple data-generating processes. We develop a general framework
for defining model-agnostic treatment effect modifier variable importance
parameters applicable to high-dimensional data with arbitrary correlation
structure, deriving nonparametric estimators of these parameters, and
establishing these estimators’ asymptotic properties. We showcase this framework
by deriving absolute and relative treatment effect modifier variable importance
parameters for data-generating processes with continuous, binary and
time-to-event outcomes with binary exposures and potentially high dimensional
confounders. One-step, estimating equation and targeted maximum likelihood
estimators for each parameter are provided. Certain estimators are proven to be
double-robust under non-stringent conditions. All are asymptotically linear
under reasonable entropy constraints on the data-generating process and
consistency-rate requirements on the nuisance parameter estimators. Numerical
experiments with moderate- and high-dimensional confounders demonstrate that
these estimators’ asymptotic guarantees, like false discovery rate control, are
approximately achieved in realistic sample sizes for observational and
randomized studies alike.

### Related Papers

- [A flexible approach for predictive biomarker
  discovery](https://academic.oup.com/biostatistics/advance-article/doi/10.1093/biostatistics/kxac029/6647929)
  by Boileau et al. (2022)
- [A nonparametric framework for treatment effect modifier discovery in high
  dimensions](https://arxiv.org/abs/2304.05323) by Boileau et al. (2023+)

### Related R Packages

- [uniCATE](https://github.com/insightsengineering/uniCATE)
- [unihtee](https://github.com/insightsengineering/unihtee)
