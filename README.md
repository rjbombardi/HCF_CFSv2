# HCF_CFSv2

The bcltrigger.f is a subroutine that calculates the Heathed Condensation Framework (HCF; Tawfik et al. 2014,2015a,b) trigger as published in Bombardi et al. (2016).

The files compns_RJB.f and the sascnvn_v_RJB.f are modified versions of the original subroutines used in the Climate Forecast System (CFSv2) model adaped to work

sascnvn_v is the subroutine that calculates the deep convection parameterization commonly know as NewSAS (Han and Pan, 2011).

One can implement the HCF trigger in the operational version of the deep convection parameterization (Old SAS; sascnv_v.f) by simply including the same moddifications made to the NewSAS scheme into the OldSAS scheme. 


Bombardi RJ, Tawfik AB, Manganello JV, Marx L, Shin C-S, Halder S, Schneider EK, Dirmeyer PA, Kinter JL (2016) The heated condensation framework as a convective trigger in the NCEP climate forecast system version 2. JAMES, DOI: 10.1002/2016MS000668

Han, J., and H.-L. Pan 2011: Revision of convection and vertical diffusion schemes in the NCEP global forecast system. Weather Forecasting, 26, 520-533. DOI 10.1175/WAF-D-10-05038.1

Tawfik, A. B., P. A. Dirmeyer, and J. A. Santanello,  2015a: The heated condensation framework. Part I: Description and Southern Great Plains case
study, J. Hydrometeorol., 16, 1929-1945, DOI 10.1175/JHM-D-14-0117.1.

Tawfik, A. B., P. A. Dirmeyer, and J. A. Santanello, 2015b: The heated condensation framework. Part II: Climatological behavior of convective
initiation and land-atmosphere coupling over the Conterminous United States, J. Hydrometeorol., 16, 1946-1961, DOI:10.1175/JHM-D-14-0118.1.

Tyrlis, E., and B. J. Hoskins, 2015: Aspects of a Northern Hemisphere Atmospheric Blocking Climatology. J. Atmos. Sci., 65, 1638-1652. DOI:
http://dx.doi.org/10.1175/2007JAS2337.1

