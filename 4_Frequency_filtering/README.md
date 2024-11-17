# Frequency filtering, color
In this project we use Fourier transform to filter images.

The first part of the project consists in the use of $filters$.
The first function used, `idealLowPassFilter(n, m, fc)` returns a 
low pass filter with frequency cutoff $f_c$. 
This function sets to 1 pixels at Euclidean distance $f_c$ from the center. 

The second part studies $linear filtering$ - or - $convolution$. 
Using this techniques, pixels can be manipulated with multiple goals. One example is to use an average pixel value for windows of $2x2$ pixels.  
By definition, the mean filter returns a new value for each pixel in the image, weighted by the contribution made by the pixels that surround it. 
Another filter used, $Gaussian filters$, is used and compared. In this case, the new pixel value output from the study of the window is not found as a simple average but rather the gaussian distribution of the pixel values. 

Finally, the third exercise explores $anti aliasing filtering$. 
Filtering produces a smoother image, which tends to lose higher frequencies and thus possibly "blur" a picture. 
