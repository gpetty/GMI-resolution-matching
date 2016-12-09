# GMI-resolution-matching
Coefficients for matching resolutions of channels of the Global Precipitation Measurement (GPM) Microwave imager (GMI) according to 
procedures and results described by 

Petty, G. W. and Bennartz, R.: Field-of-view characteristics and resolution matching for the Global Precipitation Measurement (GPM) 
Microwave Imager (GMI), Atmos. Meas. Tech. Discuss., doi:10.5194/amt-2016-275, in review, 2016. 

Each target pixel (numbered from zero) has a variable-length list of coefficients corresponding to a relative scan position (first column)
and an absolute pixel position (second column) for contiguous pixels contributing to the weighted average.  
There are separate files for forward viewing and reverse viewing geometry.

The file name identifies first the channel frequency to which the coefficients are to be applied and then the 
target frequency whose EFOV is to be matched. 

For example, in the file name
GMI1_F_FOVMatchW10.65_to_18.70.wgts  , the 'F' indicates that these coefficients are for the GMI when it is in the forward-viewing 
orientation, and they are for deconvolving the 10.65 GHz channels to approximate the resolution of the 18.70 GHz channels.

When using, verify that all coefficients for a given target pixel sum to unity.
