# Methodology

This folder describes the methodological workflow followed in the Bachelor's Thesis project.

## Overview

The project focused on the comparison of broad-line quasars detected in different regions of the electromagnetic spectrum: optical, X-ray and far-infrared.

The main objective was to study whether quasars detected in the far-infrared show different X-ray spectral properties compared with quasars not detected in the far-infrared. This comparison was used to explore possible relationships between AGN activity, dust emission and host-galaxy properties.

## Data catalogues

The analysis was based on three main astronomical data sources:

* **SDSS DR12Q**, used as the optical quasar catalogue and as the main source of spectroscopic identification and redshift information.
* **XMM-Newton / XMM2ATHENA**, used to obtain X-ray spectral properties such as flux, luminosity, hydrogen column density and photon index.
* **Herschel/SPIRE 250 microns**, used to identify far-infrared detections and analyse FIR emission.

Raw catalogues are not included in this repository.

## Analysis workflow

The workflow started with the selection of the optical, X-ray and far-infrared catalogues. After identifying the relevant source identifiers, such as `SRCID` and `OBJID`, the optical and X-ray catalogues were cross-matched to identify common sources.

Since the far-infrared catalogue did not provide the same type of direct identifiers, the matching with FIR sources was performed using positional information. This allowed the construction of different multi-wavelength detection regions depending on whether each source was detected in the optical, X-ray and/or far-infrared bands.

Once the subsamples were defined, the analysis focused on comparing their physical and spectral properties, including redshift, X-ray luminosity, far-infrared flux, hydrogen column density and photon index.

## Multi-wavelength classification

The sources were classified according to their detection in one or more wavelength bands:

* Optical only
* X-ray only
* Far-infrared only
* Optical + X-ray
* Optical + far-infrared
* X-ray + far-infrared
* Optical + X-ray + far-infrared

This classification made it possible to compare different subsamples and to identify possible observational selection biases.

## Tools used

The main tool used for catalogue manipulation, cross-matching and visualization was **TOPCAT**.

Python was used only for selected statistical calculations, especially the Kolmogorov-Smirnov test. The project was therefore not developed as a fully automated Python pipeline, but as a scientific data analysis workflow based on astronomical catalogue tools, statistical comparison and astrophysical interpretation.

## Notes

The purpose of this repository is to document the methodology and main results of the Bachelor's Thesis in a clear and accessible way. It is not intended to provide the complete raw data or a fully reproducible pipeline, since the original analysis depended on external astronomical catalogues.

