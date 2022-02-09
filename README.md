# Approaches to Oil & Gas Horizontal Well EUR Estimation

This project will demonstrate and compare methods for estimating horizontal well EUR (estimated ultimate recovery), herein treated as EUR/ft (EUR per foot of laterally drilled wellbore). The methods use commonly available data for individual horizontal wells in a given field, and aim to honor first principles relating to the mechanics of reservoir productivity.

<ul>
  <li>The first method ('regression_frequentist.ipynb') uses a frequentist approach to mixed linear & non-linear regression. This method is straightforward and useful for analysts more comfortable with a frequentist approach to statistical estimation.

  <li>Later phases will add Bayesian statistical and ML-based approaches, then compare the results, implementations, and relative advantages between the approaches.
</ul>

Note that while these methods are applied to EUR/ft (assuming such EURs have been reliably estimated outside this process), the methods are equally applicable to more "hard data" parameters like 6-month cumulative produced volume per foot.
