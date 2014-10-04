Cluster-analysis-of-image-RGB-colors
====================================

R scripts and results for reducing colors in images using K-Means++ 

The code in this repository takes a JPEG image as an input and then finds 1,2,3, ...256 color centers of the RGB colors in the image.  It outputs a series of images. The first image is 1 color only, the second has 2 colors etc.  The number of colors in each image is shown in the upper right corner of each frame.  The script produces 29 frames.  With the addition of the original image a 30 frame animated GIF can be produced.  The animated GIF examples in this repository were converted into GIFs from still images using <a href="http://gifmaker.me/" rel="nofollow">gifmaker.me/</a>.

I used k-means++ instead of standard k-means clustering due to the number of pixels with RGB values very close to one another, which caused a problem with convergence.

To view the animated GIF open it in a browser.

I took the original "Newport_seafood" phot in Newport Oregon in Feb 2010.
