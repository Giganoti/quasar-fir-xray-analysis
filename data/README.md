# Data

Raw astronomical catalogues are not included in this repository.

This project was based on public astronomical catalogues covering three wavelength ranges: optical, X-ray and far-infrared. These datasets were used to compare broad-line quasars detected in different bands and to study possible differences in their physical and spectral properties.

## Main data sources

The analysis used three main types of data:

* **SDSS DR12Q**
  Optical quasar catalogue used for spectroscopic identification and redshift information.

* **XMM-Newton / XMM2ATHENA**
  X-ray catalogue used to study spectral properties such as flux, luminosity, hydrogen column density and photon index.

* **Herschel/SPIRE 250 microns**
  Far-infrared data used to identify FIR detections and analyse emission related to dust and star formation in the host galaxy.

## Why the raw data are not included

The original catalogues are not uploaded to this repository because they are external scientific datasets and may contain large files. The purpose of this repository is to document the workflow, methodology, figures and statistical interpretation of the Bachelor's Thesis project.

## Data handling

The analysis involved selecting relevant catalogue columns, cross-matching sources between optical and X-ray catalogues, matching them with far-infrared detections using positional information, and classifying the resulting sources according to their detection in one or more wavelength bands.
