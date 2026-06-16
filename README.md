# YilanBay_Lagrangian_Backtracking

Python workflows used for backward-in-time Lagrangian particle tracking of fish eggs collected in Yilan Bay, northeastern Taiwan.

This repository accompanies the manuscript:

"Inferring spawning locations of Scomber japonicus, Scomber australasicus, and Trachurus japonicus in Yilan Bay, Northeastern Taiwan through molecular egg identification, developmental staging, and Lagrangian particle tracking"

---

## Repository structure

### notebooks/

Google Colab notebooks used for particle-tracking simulations.

Contents include:

- Station 9 Scomber japonicus
- Station 9 Trachurus japonicus
- Station 15 Trachurus japonicus
- 6-h, 12-h, and 18-h backtracking analyses
- Hourly-current sensitivity analyses
- Figure 8 reconstruction workflow

### results/

Simulation summary tables exported as CSV files.

### data/

Current datasets were downloaded from the Copernicus Marine Service (CMEMS).

Files include:

- CMEMS_YilanBay_20240324_20240328_6hour_depth.nc
- CMEMS_YilanBay_20240324_20240328_1hour.nc

---

## Software requirements

- Python 3
- Google Colab
- xarray
- numpy
- pandas
- scipy
- matplotlib
- cartopy
- shapely

---

## Reproducibility

All analyses can be reproduced by:

1. Opening the corresponding notebook in Google Colab.
2. Uploading the required CMEMS NetCDF dataset.
3. Running all notebook cells.

---

## License

MIT License
