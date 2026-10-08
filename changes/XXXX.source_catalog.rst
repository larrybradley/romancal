Integrate the L3 PSF model exactly over the ``pixfrac`` and output-pixel
boxes instead of using discrete box kernels, which made the model too
broad and rounded box widths that are not an integer number of grid points.
