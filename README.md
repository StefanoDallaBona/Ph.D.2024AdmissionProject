# Ph.D. 2024 Admission Project

This document provides a concise overview of the main results derived from the design analyses conducted for three experiments proposed as part of the admission process to a Ph.D. course in Psychological Science at Padua. This GitHub repository serves as a comprehensive resource for the design analyses conducted for three experiments, along with summaries of main results.

Repository Structure:

* **This document**: The Read Me document provides a concise overview of the key results derived from the design analyses for the three experiments.
*  **Experiment 1 (ICP)** Folder: .PDF file, .html file, .Rmd file of the complete Design Analysis of Experiment 1
*  **Experiment 2 (CFM)** Folder: .PDF file, .html file, .Rmd file of the complete Design Analysis of Experiment 2
*  **Experiment 3 (SSI)** Folder: .PDF file, .html file, .Rmd file of the complete Design Analysis of Experiment 3
* **Dataset**: Dataset from our previous experiment used to perform power analysis in the first experiment.


# 3. Sample Size Insensivity (SSI)
## Design Analysis key results
We posit that presenting the SSI task in a disfluent second language may enhance individuals’ ability to provide correct responses to the task. Accordingly, we formulate two hypotheses:

* H0: The proportion of correct responses in the ‘no-FLE’ condition equals the proportion in the ‘FLE’ condition.
* H1: The proportion of correct responses in the ‘no-FLE’ condition is less than that in the ‘FLE’ condition.
In this context, ‘no-FLE’ refers to the control group completing the task in their native language, where the Foreign Language Effect (FLE) is not expected, while ‘FLE’ refers to the experimental group performing the task in a disfluent second language, where the FLE is expected.

We are seeking to reject the null hypothesis by employing a One-Tailed Two-Proportion Z test. Furthermore, to explore differences in proportions, we derived Bayesian priors to compute Bayesian posterior distributions for both conditions (see DX figure).
<img width="859" alt="image" src="https://github.com/StefanoDallaBona/Ph.D.2024AdmissionProject/assets/145267546/f90dafd0-9394-45ac-baad-d3a96c303a39">

A power analysis, based on an estimated Cohen’s ℎ effect size of 0.25, indicates a required sample size of 𝑛=200 for each group. Hence, we intend to recruit a minimum of 200 participants (see SX figure) for each group (i.e., disfluent second language vs. fluent mother tongue). The Type M error is calculated to be 1.17, suggesting that, on average, statistically significant results exaggerate the inputted effect size by approximately 17%. Given our unidirectional hypothesis, the Type S error is anticipated to be 0. This error pertains to the probability of obtaining a statistically significant result in the opposite direction to the expected one.
