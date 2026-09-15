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

## Citation and Acknowledgments

This code was developed by Ali Reza Payandeh.

If you use this workflow in research, please acknowledge the repository and cite this:

Payandeh, A. R., Simard, M., Jensen, D., Campbell, A. D., van Deventer, H., & Christensen, A. (2026). A fully satellite-driven workflow for hydrodynamic modeling in data-scarce coastal systems: integrating ICESat-2, Sentinel-2, SWOT and reanalysis models. Frontiers in Remote Sensing, 7, 1751006. https://doi.org/10.3389/frsen.2026.1751006


The workflow uses publicly available Earth observation data from:

Sentinel-2, operated by the European Space Agency through the Copernicus Programme
ICESat-2, operated by NASA

Sentinel-2 surface reflectance used in the example was processed using ACOLITE.

Satellite_Derived_Bathymetry.ipynb

and run the notebook from top to bottom.
