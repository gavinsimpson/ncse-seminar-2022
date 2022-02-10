# NCSE Seminar 2022

## Quantifying trends in biodiversity with generalized additive models

### Gavin Simpson

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6033546.svg)](https://doi.org/10.5281/zenodo.6033546)

Slides & related R code for a talk that gave as part of the National Centre for
Statistical Ecology seminar series, Feb 9th, 2022.

Rendered slidedeck: https://gavinsimpson.github.io/ncse-seminar-2022/

#### Abstract

Climate change and other human-caused environmental disturbance may lead to
declines in biodiversity. Recently, a number of studies have collated large data
sets of monitoring time series for selected ecosystem or organism groups and
used these data sets to estimate trends in biodiversity, with many studies
identifying large declines in biodiversity across a number of organisms or
ecosystems. These results are not without controversy however; data selection
and quality issues, as well as questions over statistical methodology have lead
to vigorous debate at meetings and in scientific journals.

Typically, trends in biodiversity are estimated using linear effects, via
generalized linear mixed (or hierarchical) models to account for site-to-site
heterogeneity in temporal trends. Additionally, year-to-year variation may
enhance or mask estimated losses or gains in biodiversity over time if the
first observation year in a given series is unusually rich or depauperate.
Using year random effects has been suggested as a mechanism to account for this
potential bias. An alternative – but related – way to model trends in
biodiversity time series is using penalized splines for the trends, leading to
hierarchical generalized additive models (HGAMs; also called structural additive
models). In this talk I’ll introduce HGAMs and penalized splines and their use
for modelling biodiversity trends, and illustrate the approach using an
arthropod time series data set.
