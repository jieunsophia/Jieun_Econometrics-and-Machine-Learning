## Cressie-Read Power Divergence for Moment-Based Estimation in Machine Learning

### Jieun Lee* and Anil Bera**

*Department of Economics, Emory University. E-mail: jieun.lee@emory.edu; jieunlee.sophia@gmail.com

**Department of Economics, University of Illinois Urbana-Champaign. E-mail: abera@illinois.edu

#### Abstract
We interpret the Cressie–Read power divergence (CRPD) estimation for moment-based models from a machine-learning (ML) perspective, bridging econometrics and ML. CRPD is known to outperform GMM in finite samples—an important concern in ML, where high-dimensional settings effectively reduce the effective sample size per parameter despite large nominal datasets. In classical statistics, the CRPD power parameter is typically fixed a priori and treated as an index selecting among estimators. We show that it instead serves as a learning hyperparameter shaping finite-sample performance, acting as a curvature parameter that governs the geometry of the loss function and enters the second-order behavior of both the structural estimator and its associated Lagrange multipliers. Monte Carlo simulations demonstrate the consistency of our proposed estimator and show that the power parameter adapts to distributional features, affecting second-order bias and coverage distortion. An empirical illustration based on Owen (1988)’s classical example highlights the practical implications.

Keywords: Moment-based estimation; Cressie–Read power divergence; Generalized empirical likelihood; Finite-sample behavior; Hyperparameter.

JEL codes: C12, C13, C14.
