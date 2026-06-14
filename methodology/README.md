# Methodology

This folder documents the methodological workflow followed in the Bachelor's Thesis project.

## Overview

The project was based on the comparison of broad-line quasars detected in different regions of the electromagnetic spectrum: optical, X-ray and far-infrared.

The main goal was to analyse whether far-infrared-detected quasars show different X-ray spectral properties compared with quasars not detected in the far-infrared.

## Data catalogues

The analysis used three main types of astronomical data:

* Optical quasar data from the SDSS DR12Q catalogue.
* X-ray source data from XMM-Newton / XMM2ATHENA catalogues.
* Far-infrared data from Herschel/SPIRE at 250 microns.

Raw catalogues are not included in this repository.

## Workflow

The main steps of the analysis were:

1. Selection of optical, X-ray and far-infrared catalogues.
2. Identification of relevant source identifiers, such as SRCID and OBJID.
3. Cross-matching between optical and X-ray catalogues.
4. Cross-matching with far-infrared sources using positional information.
5. Construction of multi-wavelength detection regions.
6. Classification of sources according to their detection in optical, X-ray and far-infrared bands.
7. Analysis of redshift, X-ray luminosity, far-infrared flux and X-ray spectral properties.
8. Statistical comparison between far-infrared-detected and non-detected subsamples.

## Tools

The main tool used for catalogue manipulation, cross-matching and visualization was TOPCAT.

Python was used only for selected statistical calculations, especially the Kolmogorov-Smirnov test.

## Multi-wavelength regions

The sources were classified according to their detection in different wavelength bands:

* Optical only
* X-ray only
* Far-infrared only
* Optical + X-ray
* Optical + far-infrared
* X-ray + far-infrared
* Optical + X-ray + far-infrared

This classification allowed the comparison of different subsamples and the study of possible observational biases.

## Notes

This repository does not aim to present a fully automated Python pipeline. Instead, it documents a scientific data analysis workflow based mainly on astronomical catalogue tools and statistical interpretation.
