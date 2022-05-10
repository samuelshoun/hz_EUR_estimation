# Approaches to Oil & Gas Horizontal Well EUR Estimation

This project will demonstrate and compare methods for estimating horizontal well EUR (estimated ultimate recovery), herein treated as EUR/ft (EUR per foot of laterally drilled wellbore). The methods use commonly available data for individual horizontal wells in a given field, and aim to honor first principles relating to the mechanics of reservoir productivity.

<ul>
  <li>The first method ('regression_frequentist.ipynb') uses a frequentist approach to mixed linear & non-linear regression. This method is straightforward and useful for analysts more comfortable with a frequentist approach to statistical estimation.

  <li>The second method ('bayesian_estimation.ipynb') uses PyMC3 to treat EUR/ft and its influencing factors as random variables, solving for the likely distributions for those variables given the data. This method ideally suits oil & gas exploration & production, since it allows for more robust quantification of uncertain outcomes. Those outcomes can be passed through relevant cost functions to better inform investment decisions.
    
  <li>Next I will try a couple ML-based approaches to see if I can minimize the deterministic prediction error for individual well results.
</ul>

Note that while these methods are applied to EUR/ft (which assumes such EURs have been reliably estimated outside this process), the methods are equally applicable to more "hard data" parameters like 6-month cumulative produced volume per foot.
