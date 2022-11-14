### Climate Model Simulation Crashes (Failures)

#### Problem
Numerical climate model simulations are highly complex and in some cases prone to fail or crash due to a variety of reasons. This project attempts to classify simulation outcomes based solely on the values of the physical parameters used in each simulation run.

#### Jupyter Notebooks and scripts
* Stage 1 includes code for data acquisition and initial exploratory data analysis.
* Stage 2 includes code for classification modeling: i.e., model optimization, testing, and performance results.

#### Dataset
The dataset includes 540 climate model simulation outcomes and climate parameter values used in each run. Only 46 out of the 540 simulation runs failed due to numerical reasons caused by the climate parameter values used in the run.

The dataset may be found here:
* https://archive.ics.uci.edu/ml/machine-learning-databases/00252/

#### Business Case
Running a complex numerical simulation is a capital heavy endeavor, each simulation run consumes large amounts of resources (e.g., time, energy, dollars, compute). Decreasing the number of simulations runs that are likely to fail will help reduce capital waste.


