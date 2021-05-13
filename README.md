# The-Role-of-Arctic-Sea-Ice-in-Climate-Change
Code used to prepare datasets and to evaluate the evolution of sea ice in the Arctic and its impacts on precipitation and temperature.

The various notebooks and codes were used at different steps:

1. Preperation of Data for Analysis 
   Data files from the CMIP6 data base were concatenated merged (for the model mean) to obtain 2000 - 2100 monthly outputs for tas, ta(850), pr and prsn. 
   A different code was used to prepare the sithick and siconc variables as these variables had to be converted from 2D arrays to 1D arrays for analysis.
   Codes are numbered 1 - 7 and include regridding codes, concatenation, multi model mean, seasonal averages and masking of values.
   Code numbered 15 is the regrid code based on the grid defined in methodology for Greenland.

2. Plotting of Data
   After preparation of files for analysis, plots for the decadal difference were created.
   These are numbered 8 - 11 and include seasonal plots for siconc, sithick, tas, ta 850, pr, prsn, prrf.
   Code for annual pr, prsn and prrf is numbered 12.
   
3. PDD Analysis
   PDD Sum analysis was conducted using the PDD function from Seguinot (2019). 
   Code for PDD sum is numbered 13 and includes the plot for the century's PDD trend.
   
4. SMB Estimate
   Calculations for SMB estimates are included in Code 14. This code includes the use of nc files previously prepared in the steps above.
