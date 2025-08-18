# Practicum 2025

The principal health-related question I am interested in answering is: What are the health impacts of air pollutants and their complex "mixture effects"? Specifically, I aim to study the associations between mortality as the outcome of interest with the mixture of ozone, PM2.5, and NO2 levels, as the exposure of interest in order to create models to predict the effects of such exposures on this outcome. I plan to use a combined approach using weighted quantile sum (WQS) regression with the help of quantile g-computation to look at the differences in mortality at the county level based on the exposure mixture level. Additionally, this project will focus on counties within New York state and the following year range: 2000-2016. 

## I. Overview
Long-term exposure to O3, PM2.5, and NO2 has been consistently associated with
all-cause mortality; however, the mixture effects of these pollutants are lesser-known.1 The
project aim is to investigate the overall effect of long-term exposure to PM2.5, NO2, and O3 as a
mixture of exposure species on all-cause mortality at the county-level in New York State from
2000-2016.

Mortality was measured as the total count of deaths in each county per month. Daily
exposure concentrations for 1km x 1km grid cells were acquired using high-resolution,
predictive models, which were aggregated by county and averaged by month.2 Covariates
included demographic, environmental, and socioeconomic variables. To estimate the exposure
mixture effects, two approaches were used: weighted quantile sum (WQS) regression and
quantile g-computation. WQS regression involves categorically transforming the exposures
defined by quantiles and creating an exposure index from the weighted average of the
transformed exposures, which is then used in a generalized linear model. Quantile g-computation
is an extension of WQS regression that reduces bias and can apply directional heterogeneity to
resulting regression models and the effect estimates. I performed the data processing
and analysis for this project, aided by data sourcing and suggestions from my practicum advisor, Dr. Xiao Wu.
