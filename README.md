# 📊 Earth Data Xarray NetCDF → Zarr Demo

A demonstration project showing how to efficiently work with large environmental datasets (e.g., ERA5) using **xarray**, **Dask**, **NetCDF**, and **Zarr**.
This repository includes the following:

- Load large climate / Earth science data with **xarray**
- Efficient chunked computation and visualization via **Dask**
- Convert **NetCDF** files to **Zarr** for faster incremental analysis
- Inspect computation graphs to understand Dask task planning

## Repository Structure

earth-data-xarray-netcdf-zarr-demo/
├── data/ # Example NetCDF (not included)
├── notebooks/ # Jupyter notebooks with demos
├── scripts/ # Example processing scripts
├── dataset/ # Zarr output location
├── .pre-commit-config.yaml # Code quality enforcement
├── pyproject.toml # Build & lint config
├── README.md # This document
└── requirements.txt # Python dependencies


# Installation

## 1. Clone the repository

```bash
git clone https://github.com/samin91/earth-data-xarray-netcdf-zarr-demo.git
cd earth-data-xarray-netcdf-zarr-demo
