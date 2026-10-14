# DS-A2 — Inference and Uncertainty Report

**Student:** [your name]  
**Repository commit/tag:** [fill after committing checked files]  
**Execution environment:** [Python and package versions from notebook]  

## Research question and estimand
[State the question, unit, estimand Δ, H0/H1, alpha, and why the minimum meaningful effect is appropriate.]

## Simulation design and method
[Describe synthetic data generation, seed, sample sizes, noise/effect grid, Welch interval/test, bootstrap method, number of repetitions, and counterexample.]

## Results: estimate and uncertainty
[Insert actual baseline estimate and both intervals from `results/baseline_inference.csv`. Discuss whether intervals include zero and practical meaning. Do not equate p-value with effect size.]

## Sampling distribution
[Insert `figures/sampling_distribution.png`. Discuss center, spread, bias, and empirical/theoretical standard error.]

## Power and Monte Carlo uncertainty
[Insert power figure(s). Compare sample size, effect size, and noise. Discuss null rejection rate and Monte Carlo SE.]

## Assumption-violating counterexample
[Report actual Type I error, interval coverage, and interval widths from `results/counterexample_results.csv`. Explain how the counterexample changes or does not change your conclusion.]

## Independent verification
[Describe one independent calculation, values compared, and tolerance. Complete the AI-use log.]

## Limitations and conclusion
[Discuss simulation-only scope, model assumptions, finite repetitions, conditional power, and significance versus practical importance. Give a conclusion supported by outputs only.]
