This directory contains data from [this paper from
2006](http://adsabs.harvard.edu/abs/2006MNRAS.368..715M) about the galaxy halo mass vs. stellar mass
relation. 

The three subdirectories each contain the data and theoretical signal used to plot the corresponding
figure.  All data filenames begin with "rebin" and all theoretical signal filenames begin with
"fitavgsig.hh".  In the fig1/ directory, the filename includes the stellar mass bin ("sm1", "sm2",
etc.) and either "lowfdev" or "highfdev", where "lowfdev" is frac_dev<0.5 (late types).  In the
fig2/ directory, the filename includes the luminosity bin.  In the fig3/ directory, the filename
includes the luminosity bin and either "highden" for high density or "lowden" for low density.

The files that contain the signal from the data have 3 columns:
1. R (transverse separation in comoving kpc/h)
2. \Delta\Sigma (in h*Msun/(comoving pc)^2)
3. Error on \Delta\Sigma

The files that contain the theoretical signal have four columns, but
only the first two are important:
1. R (transverse separation in comoving Mpc/h) - note that this is
not in kpc/h like the data
2. \Delta\Sigma (in h*Msun/(comoving pc)^2)
