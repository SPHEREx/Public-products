# Public-products

This repository contains a few public files summarizing forecasted instrument performances. 

- *Point_Source_Sensitivity_v28_base_cbe.txt* contains the point source sensitivity (AB magnitude, 5 sigma) over the full sky and deep fields, assumed to be two 100 sq. deg. field at the north and south ecliptic poles. The sensitivity is given per spectral channel  defined to be delta_lambda = the integral width, of which there are 96. For the filters delta_lambda is quite close to FWHM.  For Nyquist sampling, i.e. two samples per spectral channel, multiply by sqrt(2). 
- *Surface_Brightness_v28_base_cbe.txt* contains the surface  brightness noise level (nW/m^2/sr per pixel, 1 sigma) over the full sky and deep fields, assumed to be two 100 sq. deg. field at the north and south ecliptic poles. The sensitivity is given per spectral channel  defined to be delta_lambda = the integral width, of which there are 96.  For the filters delta_lambda is quite close to FWHM.  For Nyquist sampling, i.e. two samples per spectral channel, multiply by sqrt(2). 
- *galaxy_density_v28_base_cbe.txt* contains SPHEREx forecasted galaxy number density and bias for fives samples for multiple galaxy redshift bins. Each line corresponds to a subsample defined by galaxy redshift uncertainty, respectively sigma(z)/(1+z) <= 0 - 0.003, 0.003 - 0.01, 0.01 - 0.03, 0.03 - 0.1, 0.1 - 0.2  (the worst redshift uncertainty is assumed for each bin).
- *FWHM_v28_base_cbe.txt* contains the effective FWHM (optical PSF plus pointing jitter) as a function of wavelength.

Pixels are squared with width of 6.2 arcsec. The sensitivities above assume the full 2 year nominal mission. More detailed about the mission and its design can be found on the SPHEREx mission website [https://spherex.caltech.edu].

Please contact Olivier (olivier.dore@caltech.edu) if you have any question. Please add "Courtesy NASA/JPL-Caltech" if you use the graphics in presentation.
