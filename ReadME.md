# Dataset Description

This repository provides the dataset and near-real-time detection results associated with the paper:

**Prior-guided deep learning for near-real-time forest disturbance mapping using Sentinel-1 SAR time series**

## Data Description

### Near-real-time detection results

The folders `Site*_Res` contain the near-real-time forest disturbance detection results of all compared methods for each study site in 2020, stored in `.tif` format, where `*` denotes the site identifier.

The folders `PDF_Res`, `PDFsavg_Res`, and `RCR_Res` contain the detection results of the three baseline methods (PDF, PDFsavg, and RCR), respectively, also stored in `.tif` format.

### Value definition

All `.tif` images represent near-real-time detection maps:

- Pixel value `0`: no forest disturbance detected in 2020.
- Pixel value `> 0`: the detected disturbance date represented as the day of year (DOY).

## Notes

The provided results are intended to support reproducibility and further research on near-real-time forest disturbance monitoring using Sentinel-1 SAR time series.


## License

This work is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).
To view a copy of this license, visit https://creativecommons.org/licenses/by/4.0/

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
