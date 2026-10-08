Integrate the ePSF reference stamps over the native pixels with
``photutils.psf.make_epsf_from_psf`` instead of a discrete box kernel,
which made the PSF models too broad and biased the PSF-fitted fluxes.
