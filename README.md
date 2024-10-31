This project revises the idea of my Bsc thesis to train a denoising neural network by creating artificial training data.
We reduced the problem to its essence by using very small input images (i.e. ~16x16p) and added random straight lines.
Afterwards, we corrupted a copy of the image with noise. The corrupted images would serve as input to the network whereas the uncorrupted ones acted as labels.
This notebook enables to experiment rather freely with the model architecture and image properties.
There are no restrictions as to changing sizes of the inputs enroute. 
