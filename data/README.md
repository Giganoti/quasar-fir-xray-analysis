# Data

Raw astronomical catalogues are not included in this repository.

The Bachelor's Thesis analysis was based on public astronomical catalogues from optical, X-ray and far-infrared surveys.

## Data sources

The main data sources used in the project were:

* **SDSS DR12Q**: optical quasar catalogue used for spectroscopic quasar identification and redshift information.
* **XMM-Newton / XMM2ATHENA**: X-ray catalogue used to analyse X-ray spectral properties such as flux, luminosity, hydrogen column density and photon index.
* **Herschel/SPIRE 250 microns**: far-infrared data used to identify FIR detections and analyse far-infrared flux.

## Why raw data are not included

The original catalogues are not included because:

* They may be large files.
* They belong to external astronomical surveys and catalogues.
* The purpose of this repository is to document the workflow, methodology and main results of the Bachelor's Thesis.

## Data handling

The analysis involved:

* Selection of relevant catalogue columns.
* Cross-matching between optical and X-ray catalogues.
* Positional cross-matching with far-infrared sources.
* Classification of sources according to their detection in different wavelength bands.
* Statistical comparison of selected subsamples.
