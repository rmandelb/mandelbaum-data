This README file describes the data files associated with [this
paper](http://adsabs.harvard.edu/abs/2012arXiv1207.1120M) from 2013 on cosmological parameter
constraints from lensing and clustering in the SDSS.

The data provided are the Upsilon_gm(R_0=2 Mpc/h) and Upsilon_gg (R_0=4 Mpc/h) used for the fits in
that paper.  This corresponds to the data shown in Figure 6 (bottom panel) and Figure 8 (middle
panel); however, the data in the figures was rebinned for easier viewing.  The data in these files
was used for the actual cosmological parameter fits, and has more radial bins within the same range
of radii.

The data files are those starting with "jointdata" and the covariance matrices are in the FITS files
starting with "jointcov".  The filenames indicate the sample, i.e., "mainL5", "LRG", and
"LRG-highz".

The file format for the jointdata* files is as follows: The clustering data are given first,
followed by the lensing data.  For example, in jointdata.upsgg4.upsgm2.LRG.lenswt.calib.out, the
first 14 lines are clustering data and the rest is lensing.  In both cases, the first column is
transverse separation R (comoving Mpc/h).  For clustering, the second column is Upsilon_gg in
comoving Mpc/h; for lensing, the second column is Upsilon_gm in h M_{sun}/(comoving pc)^2.

The jointcov* files contain a FITS image of the covariance matrix.
