This directory contains data from [this paper from
2015](http://adsabs.harvard.edu/abs/2016MNRAS.457.3200M) about the galaxy halo mass vs. stellar mass
relation for locally brightest galaxies, split into red and blue subsamples.

The two subdirectories contain the lensing signals for LBGs and all Main sample galaxies,
respectively.  These data are shown in Figures 7, 8, and 9 of the paper.  In each subdirectory, the
file name indicates the color sample ("red" or "blue").  For LBGs, since the samples for blue
galaxies at high stellar mass were small, the data were shown rebinned for high stellar mass; the
file containing the rebinned data has "rebin" in the filename.

The data files contain a single column with the transverse separation in physical Mpc/h, followed by
pairs of columns that have DeltaSigma and its 1-sigma uncertainty (h Msun/(physical pc)^2).  The
stellar mass bins for those columns are given in the proper order in the header line.
