# Ph.D. 2024 Admission Project

Repository Structure:

- **Read Me Document**: This document provides a concise overview of the key results derived from the design analyses for the three experiments.

- **Datasets**: Contains the blibliography (.bib) and datasets (.csv) from our previous experiment used to perform power analysis in the first experiment.

- **Experiment 1 (ICP) Folder**: Contains PDF, HTML, and Rmd files of the complete Design Analysis of Study 1 on the Illusion of Causality.

- **Experiment 2 (CFM) Folder**: Includes PDF, HTML, and Rmd files of the complete Design Analysis of Study 2 on the Conjunction Fallacy.

- **Experiment 3 (SSI) Folder**: Consists of PDF, HTML, and Rmd files of the complete Design Analysis of Study 3 on the Sample Size Insensitivity.


# Design Analysis key results

## 1. Illusion of Causality Propagation (ICP)

Participants will assume the role of medical personnel and will be exposed to two sets of scenarios, where they will evaluate the effectiveness of a medicine to treat a disease at one hospital and then assess another medicine at a different hospital. Based on these assessments, participants can form opinions regarding the effectiveness of the two medicines and decide whether to adopt one, the other, both, or neither for a third hospital. In one of four experimental conditions, participants will compare two scenarios in the following sequence: one scenario will feature an illusory medicine (I), while the other will involve a genuinely effective medicine (E). This sequence of scenarios will be denoted as S(I,E).

We hypothesize that the second evaluation of the illusory medicine in condition S(I,E) will be lower than the first evaluation of the illusory medicine in the same condition S(I,E). We believe that comparing the illusory medicine to the effective one will diminish the perceived effectiveness of the illusory medicine, leading participants to update their previous belief about its effectiveness.

* H0: First evaluation of I in S(I,E) = Second evaluation of I in S(I,E)
* H1: First evaluation of I in S(I,E) > Second evaluation of I in S(I,E)

Thus, a paired sample t-test is required to try to support that data are unlikely under the null-point hypothesis. This hypothesis serves as the foundation for our Design Analysis. It must be noticied that a null result would be very interesting, supporting the idea of the existence of an assessment inertia in the illusion frame. Additionally we are planning to compute Bayes Factor for assessing if data are more likely under the null model (BF01) or the alternative model (BF10).

A power analysis, based on an estimated Cohen’s d effect size of 0.48, indicates a required sample size of n=28 for each group. However, we intend to recruit a minimum of 40 participants for each of the four groups, i.e., S(I,E), S(E,I), S(I,N), S(N,I)., to increase our power above 0.90. The Type M error is calculated to be 1.06, suggesting that, on average, statistically significant results exaggerate the inputted effect size by approximately 6%. Given our unidirectional hypothesis, the Type S error is anticipated to be 0. This error pertains to the probability of obtaining a statistically significant result in the opposite direction to the expected one.

<img width="820" alt="image" src="https://github.com/StefanoDallaBona/Ph.D.2024AdmissionProject/assets/145267546/62b24d15-97cf-470e-ba1d-1bd39a545c56">

## 3. Conjunction Fallacy (CF)

This study aims to uncover the cognitive processes behind the conjunction fallacy (CF) by utilizing a Multinomial Processing Tree (MPT) model. We hypothesize that in a condition where the application of a mathematical rule is more salient, individuals are less likely to rely on heuristic processes and more inclined to apply a mathematical rule. Therefore, we expect the parameter $h$ for the heuristic process in the MPT model to be significantly reduced $(h-d)$ in the "Mathematical" condition compared to a classical "Heuristic" condition.

* H0: The probability parameter $h$ in the heuristic condition equals the probability parameter $h$ in the second condition.
* H1: The probability parameter $h$ in the heuristic condition is greater than the probability parameter $h$ in the second condition.

### 3.1 MPT Model

<img width="633" alt="image" src="https://github.com/StefanoDallaBona/Ph.D.2024AdmissionProject/assets/145267546/e1fbbde2-c54c-4435-826f-2d3654787ada">

<img width="580" alt="image" src="https://github.com/StefanoDallaBona/Ph.D.2024AdmissionProject/assets/145267546/3f24fc2a-e95e-4506-bdbd-635102b8f476">


### 3.2 Power analysis
Given a hypothesized parameter difference of 0.6 between $h_1$ and $h_2$, we aim to recruit 100 participants for each condition to achieve a statistical power above 0.8.

<img width="657" alt="image" src="https://github.com/StefanoDallaBona/Ph.D.2024AdmissionProject/assets/145267546/7cb32577-f79a-4c04-a08f-1965f624c79c">


## 3. Sample Size Insensivity (SSI)

We posit that presenting the SSI task in a disfluent second language may enhance individuals’ ability to provide correct responses to the task. Accordingly, we formulate two hypotheses:

* H0: The proportion of correct responses in the ‘no-FLE’ condition equals the proportion in the ‘FLE’ condition.
* H1: The proportion of correct responses in the ‘no-FLE’ condition is less than that in the ‘FLE’ condition.
In this context, ‘no-FLE’ refers to the control group completing the task in their native language, where the Foreign Language Effect (FLE) is not expected, while ‘FLE’ refers to the experimental group performing the task in a disfluent second language, where the FLE is expected.

We are seeking to reject the null hypothesis by employing a One-Tailed Two-Proportion Z test. Furthermore, to explore differences in proportions, we derived Bayesian priors to compute Bayesian posterior distributions for both conditions (see DX figure).

A power analysis, based on an estimated Cohen’s h effect size of 0.25, indicates a required sample size of n=200 for each group. Hence, we intend to recruit a minimum of 200 participants (see SX figure) for each group (i.e., disfluent second language vs. fluent mother tongue). The Type M error is calculated to be 1.17, suggesting that, on average, statistically significant results exaggerate the inputted effect size by approximately 17%. Given our unidirectional hypothesis, the Type S error is anticipated to be 0. This error pertains to the probability of obtaining a statistically significant result in the opposite direction to the expected one.

<img width="859" alt="image" src="https://github.com/StefanoDallaBona/Ph.D.2024AdmissionProject/assets/145267546/f90dafd0-9394-45ac-baad-d3a96c303a39">

