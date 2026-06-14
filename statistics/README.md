# Statistical Analysis

This folder documents the statistical analysis used in the Bachelor's Thesis project.

## Overview

The project compared different subsamples of broad-line quasars according to their detection in optical, X-ray and far-infrared catalogues.

The main statistical objective was to determine whether some physical properties followed similar or different distributions across the analysed subsamples.

## Kolmogorov-Smirnov test

The Kolmogorov-Smirnov test was used to compare distributions between different groups of quasars.

This non-parametric test was applied to evaluate whether two samples could be considered as coming from the same underlying distribution.

The test was especially useful for comparing properties such as:

* X-ray luminosity
* X-ray flux
* Hydrogen column density, NH
* Photon index

## Use of Python

Python was used for selected statistical calculations, especially the implementation of the Kolmogorov-Smirnov test.

The main analysis workflow was not developed as a full Python pipeline. Most of the catalogue manipulation, cross-matching and visualization work was carried out using TOPCAT.

## Interpretation

The statistical analysis helped identify whether apparent visual differences between histograms were supported by quantitative evidence.

In some cases, the results suggested that differences between samples were strongly affected by observational selection biases. In the direct comparison between far-infrared-detected and non-detected quasars, the X-ray spectral properties did not show statistically significant differences between the analysed subsamples.

## Future improvements

Possible future improvements include:

* Reproducing the statistical tests in a clean Python script.
* Adding a small example dataset.
* Creating a notebook to demonstrate the Kolmogorov-Smirnov test.
* Comparing the results with alternative statistical tests.
