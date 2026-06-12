# quasar-fir-xray-analysis
Analysis of far-infrared and X-ray properties of quasars using astronomical catalogues and statistical tests.
# Far-Infrared and X-ray Properties of Broad-Line Quasars

Bachelor's Thesis project in Physics focused on the analysis of far-infrared and X-ray properties of broad-line quasars.

This repository documents the methodology, figures and statistical analysis developed during the project. The main workflow was carried out using astronomical catalogue analysis tools, especially TOPCAT, while Python was used for selected statistical testing.

## Project overview

The aim of this project was to investigate whether broad-line quasars detected in the far-infrared show significant differences in their X-ray spectral properties compared with non-detected sources.

The analysis combined information from optical, X-ray and far-infrared catalogues in order to compare different subsamples of quasars and study possible relationships between AGN activity and host-galaxy properties.

## Scientific context

Quasars are extremely luminous active galactic nuclei powered by accretion onto supermassive black holes. Their emission across different wavelength bands provides information about different physical processes:

* Optical data: spectroscopic identification and redshift information.
* X-ray data: high-energy processes close to the supermassive black hole.
* Far-infrared data: dust, cold gas and star-formation-related emission in the host galaxy.

## Data sources

The project was based on public astronomical catalogues, including:

* SDSS DR12Q optical quasar catalogue
* XMM-Newton / XMM2ATHENA X-ray catalogue
* Herschel/SPIRE far-infrared data at 250 microns

Raw catalogues are not included in this repository.

## Methodology

The work included:

* Selection and comparison of optical, X-ray and far-infrared samples.
* Cross-matching between astronomical catalogues.
* Construction of Venn regions according to multi-wavelength detections.
* Analysis of redshift and X-ray luminosity distributions.
* Study of far-infrared fluxes.
* Comparison of X-ray spectral properties.
* Application of the Kolmogorov-Smirnov statistical test.

## Tools used

* TOPCAT for catalogue manipulation, cross-matching and visualization.
* Python for statistical testing.
* Scientific literature review for astrophysical interpretation.

## Main results

The analysis suggested that redshift and X-ray luminosity comparisons are affected by observational selection biases related to the limitations of optical and X-ray surveys.

However, the direct comparison of X-ray spectral properties between far-infrared-detected and non-detected quasars did not show statistically significant differences between the subsamples.

## Repository structure

```text
report/        Final thesis report or summary
figures/       Main figures and plots from the analysis
methodology/   Explanation of the catalogue workflow and cross-matching strategy
statistics/    Statistical testing, including the Kolmogorov-Smirnov test
data/          Description of the data sources used
```

## Skills demonstrated

* Scientific data analysis
* Astronomical catalogue handling
* Multi-wavelength astrophysical analysis
* Statistical comparison of samples
* Data visualization
* Critical interpretation of observational biases
* Scientific writing

## Future improvements

* Reproduce selected parts of the analysis in Python.
* Add cleaner versions of the main plots.
* Include a simplified workflow diagram.
* Add a short technical summary in Spanish and English.
