This visualization is an auto-encoder run on rotated, black-white images from the data link provided.  I got the code for the autoencoder from DeepLearning.net, modified it to work on the data for this competition, and tweaked the number of output layers.

The summary of the algorithm, and the base code is available here http://deeplearning.net/tutorial/dA.html

I've included the file "dA.py", which runs a denoising autoencoder on input images. However, this particular visualization was generated without noise in the images -- that is, the images were projected into a lower dimensional space such that the reconstruction error when performing the inverse of that operation was minimized, rather than trying to regenerate copies of the original image using censored versions of the images.
