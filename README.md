# Langebaan Satellite-Derived Bathymetry

Example workflow for generating satellite-derived bathymetry in Langebaan Lagoon, South Africa, using Sentinel-2 imagery, ICESat-2 ATL24 bathymetric observations, and XGBoost.

Developer: Ali Reza Payandeh

## Input data

The example uses:

- Sentinel-2 ACOLITE product:
  `S2B_MSI_2024_11_28_08_59_38_T33HYD_L2R.nc`
- ICESat-2 ATL24 track:
  `atl24x_rgt_228_cycle_5_gt3r.csv`

The ICESat-2 file is included in this repository.

The Sentinel-2 NetCDF file is distributed separately as a GitHub Release asset because of its size.

## Running the example

Download the Sentinel-2 NetCDF file from the Releases section and place it in the same folder as the notebook.

Install the required Python packages:

pip install -r requirements.txt

Then open:

Satellite_Derived_Bathymetry.ipynb

and run the notebook from top to bottom.
