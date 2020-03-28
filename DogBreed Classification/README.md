# DogBreed Classification

A pipeline is created to process user-supplied images.
There are 2 types of images that get classified. 
The first are dog images, which estimate the breed of the canine.
The second are images of a person, which classifies a breed of canine that resembles the humane.
Other images won't get classified.

For creating the CNN pytorch and python is used.
# Architecture

- 5 Convolutional Layers: - Begining with 16, 32, 64, 128, 256 Filters used with a Relu Activation Function with a padding of 1, kernel size of 3 and stride of 1
- Pooling Layer: used with each convolutional Layer to reduce dimensions
- 5 Normalization Batch: after each Conv. Layer batch normalization is used for the filter
- 2 linear Layers at the End: the first gets activated with a Relu function
- Dropout Layer: is used with a probability of 0.5
