# PCA-implementation

1. You are provided a subset of original dataset of faces with labels. <a> <b>.jpg
image is bth image of ath class.
2. Please find the link to the dataset here: https://bit.ly/39eUAJi.
3. Perform PCA over all the images in the dataset. You may downscale the image
and convert it to grayscale for ease of computation.
4. We can reconstruct the image back using a small number of components. Plot a
graph showing the total mean square error over all train images vs the number of
principal components used to reconstruct. Include this plot in your submission.
(Use a reasonable range for number of components)
5. Decide N, the number of principal components required such that the reconstructed
images will have mean squared error less than 20% over all train images. Display
those N principal components as reconstructed images. You will see some base
structures of the faces. Include these images in your report.
6. Use scatterplots to examine how the images are clustered in the 1D, 2D and 3D
space using the required number of principal components.
