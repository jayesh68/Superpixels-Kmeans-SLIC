# Superpixel generation using k-means and SLIC

## Input Data
<img src="https://github.com/jayesh68/SLIC-Superpixels-Kmeans/blob/main/Data/k-meaninp1.png"/>

## Using K-means to generate superpixels using RGB values
The clustering function takes as input the image and the number of clusters to generate pixelwise plot and the superpixel plot. The pixels are represented by the a (R,G,B) vector. The superpixel plot is formed by calculating the mean pixel value for a class and replacing the pixel value with the mean value.

#### Pixelwise and Superpixel plot for some of the input images
<p float="left">
<img src="https://github.com/jayesh68/SLIC-Superpixels-Kmeans/blob/main/Data/k-meanoutput1.png" width="400" height="400"/>
<img src="https://github.com/jayesh68/SLIC-Superpixels-Kmeans/blob/main/Data/k-meanoutput3.png" width="400" height="400"/>
</p>
