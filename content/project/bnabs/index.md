---
date: "2020-07-13"
external_link: ""
image:
  caption: 'ROC curves for a proposed VRC01 neutralization sensitivity predictor. Inset: 3D structure of the HIV Envelope protein with colored areas based on identified important features and groups using our proposed variable importance measure. From Magaret et al. (2019)'
  focal_point: Smart
links:
slides:
summary: Assessing neutralization sensitivity of HIV-1 viruses to broadly neutralizing antibodies.
tags:
- variable-importance
- machine-learning
- biostatistics
- infectious-diseases
- semiparametric-inference
title: Broadly Neutralizing Antibodies
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

The broadly neutralizing antibody VRC01, developed by the Vaccine
Research Center of the National Institute of Allergy and Infectious
Diseases, is currently being evaluated in the [Antibody Mediated
Prevention](https://ampstudy.org/) study (AMP). While the primary goal
of AMP is to assess the preventative efficacy of VRC01, a key secondary
goal is to determine if this efficacy differs based on characteristics
of the HIV virus. There are many possible locations on the HIV genome
that we might be interested in; if we simply did a statistical test for
association at each possible location, and then appropriately accounted
for this multiple testing, then we would have low power to detect
effects. To prepare for AMP, we used data on HIV viruses from the
[Compile, Neutralize, and Tally NAb
Panels](https://www.hiv.lanl.gov/components/sequence/HIV/neutralization/main.comp)
database. Our goals were to: (i) develop a score that performed well for
predicting whether or not an HIV virus was sensitive to neutralization
by VRC01, and (ii) to identify groups of HIV genome features that were
important in predicting neutralization sensitivity. This project is
joint work with [Craig Magaret](https://www.linkedin.com/in/camagaret/),
[David Benkeser](https://www.benkeserstatistics.com/#!), Peter Gilbert,
and others.

We next extended the methods used for the VRC01 analysis to combinations
of antibodies – a prevention strategy involving multiple bnAbs is likely
to be much more effective than a strategy with a single bnAb. Sohail
Nizam joined the team for this project. The software is implemented as a
Docker container.
