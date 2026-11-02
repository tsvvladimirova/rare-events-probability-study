# When Does the Unlikely Become Likely?

*A Mathematical Investigation of Rare Events Using Probability, Python Simulations and Statistical Analysis*

## Project Overview

This project investigates how the probability of observing a rare event at least once changes as the number of independent trials increases.

The investigation combines probability theory, mathematical modelling, Python simulations, and statistical analysis.

## Research Question

How does the number of independent trials affect the probability of observing a rare event at least once?

## Objectives

- Develop and explain a mathematical model for the probability of at least one occurrence.
- Formulate hypotheses before conducting experiments.
- Implement simulations in Python.
- Compare theoretical predictions with simulation results.
- Analyze the results and discuss the assumptions and limitations of the model.

## Mathematical Model

The probability of observing an event at least once in $n$ independent trials, where the probability of the event in each trial is $p$, is given by:

$$
P(\text{at least one occurrence})=1-(1-p)^n
$$

The project uses $p=0.2$ for illustrative purposes. The model can also be applied to rarer events, provided that its assumptions are satisfied.

## Research Hypotheses

- **H1 - Effect of the Number of Trials:** Increasing the number of independent trials increases the probability of observing the event at least once, for a fixed per-trial probability between 0 and 1.
- **H2 - Theoretical and Simulated Probabilities:** Empirical probability estimates generally approach the theoretical probability as the number of simulation repetitions increases.
- **H3 - Random Variation:** Independent simulation runs produce different empirical estimates, and the estimation error does not necessarily decrease with every additional run.

## Methodology

The project combines mathematical derivations with Python experiments. The theoretical probability is calculated using the mathematical model and compared with empirical estimates obtained through repeated random simulations. Statistical measures and visualizations are used to analyze the results.

## Key Findings

The results demonstrate that the probability of observing an event at least once increases with the number of independent trials. Simulation experiments are generally consistent with the theoretical model, while individual estimates vary because of randomness. Increasing the number of repetitions improves the stability of estimates in general, but does not guarantee a smaller error at every step.

## Tools and Technologies

- Python
- Jupyter Notebook
- Matplotlib
- Python `random` and `statistics` modules
- Probability theory and statistical analysis