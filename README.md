# JL_Python_tools
python scripts for working with ANHA4 model output
ANHA4basinmask
not used – takes a ANHA2 mask that defines the boundaries between different basins and makes it fit to ANHA4. 

Climatology_N_Nb
calculates N_b using the climatology data from WOA

createANHA4roughness
interpolates the smith and sandwell roughness data onto the ANHA4 grid and loads in IBCAO data (interpolated onto grid in a different script) and puts the two together to create a roughness variable for the whole domain in netCDF format.

createArcticTransects
creates the CAA and CanBar transects and plots N^2, salinity, temperatue, and kappa

depth_contour
not used – function to calculate the thalweg 

Depth_From_Bottom
Calcluates DFB for kappa and plots the results. To change what is calculated, some small modifications need to be made (i.e. to change to shallow vs deep profile calculation)

Flux_calc_exp
Defines the contours for the shelves and sets up to calculated the fluxes across them

fouryravg
calculates the 4 year averages for all the fields. Also has many random pieces that are not used. Was used to experiment then the cleaned version would be implemented in another script.

HCandFWC
Calculates fwc and hc for all three model runs plus anomalies. Need to change what id commented if the depth of the 34.8 isopycnal is wanted to be calculated instead. 

HeatBudget
Takes the different components of the heat budget (heat fluxed in through OSNAP, heat fluxed to the atmosphere and heat content) to determine whether the heat budget is balanced. This is an experimental script, if wanted to be used will need to fiddle a bit with commenting and so forth.

IBCAO_processing1
Load in ibcao data and look at the bathy from this data set.

IBCAO_processing2
Calculate the roughness from the ibcao data, interpolate onto the ANHA4 grid

IBCAO_processing3
NOT USED – attempts to calculte the wave number from the ibcao data

Kappa Histograms 
Plots the histograms of kappa and calculates the kappa stats (mean, median etc)

Kv_estimation
NOT USED
