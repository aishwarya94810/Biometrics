# Biometrics project description

Our aim is to build a fingerprint recognition biometric system relying on fingerprint spatial characteristics and carry out a thorough performance evaluation in verification mode.

## LIBRARIES AND PACKAGE USED
Python Programming languge was used for this project. 
Some of the python packages used are: 
NumPy
Scikit Learn
Open CV
Matplotlib
Pandas


## STEPS FOLLOWED:
Intensity Scaling: Intensity scalingcan be just as you say: multiplying all intensities by a scalar value. This will obviously change the histogram, but will do nothing like histogram equalization (it will just scale the x-axis of the histogram, barring some binning effects)

Contrast Enhancement: An image processing technique in which the contrast of the image, or the difference in color and light between parts of it, is touched up in order to improve its perception by human eye.

Contrast Limited Adaptive Histogram Equalization: This MATLAB function enhances the contrast of the grayscale image I by transforming the values using contrast-limited adaptive histogram equalization.

Gauss Smoothing: It shows how to apply different Gaussian smoothing filters to images using Imgaussfilt. Gaussian smoothing filters are commonly used to reduce noise.

Binarization Using Dynamic Thresholding: This system uses a different threshold value for each pixel of the image. If the contrast of this area is low, the pixel is binarized using a global pre- calculated threshold value, otherwise, when the contrast is high, the local threshold value is calculated and used.

Thinning: It is the process of feature extraction to see the results.

## Matching algorithm

The point matching algorithm relies on the fingerprints spatial characteristics and uses relatives distances between a singular core point and the minutiae features. More specifically, we will implement the approach described in this [paper][1].

## Performance evaluation

We will assess the perfomance of our system in verification mode using the single template configuration. FMR and FNMR, TMR and TNMR rates are also used to evaluate the performance.

##  DATASET USED
We used open source data which is provided in the following link. It consists of different types of format. We ran our algorithm on two formats (.png and .bmp) to get the results.
http://www.advancedsourcecode.com/fingerprintdatabase.asp


## Sources

Paper referred:
“Fingerprint Matching Using Spatial Characteristics Akinyokun Oluwole C., Alese Boniface K., and Iwasokun Gabriel B.”
Open Source references:
• https://github.com/rtshadow
• https://github.com/Antoninj/biometrics-project
Datasets:
http://www.advancedsourcecode.com/fingerprintdatabase.asp
