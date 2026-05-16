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