# Image_reconstruction_with_Poutyne

In this example, we train a simple convolutional autoencoder (Conv-AE) on the MNIST dataset to learn image reconstruction. The Conv-AE is composed of two parts: an encoder and a decoder. The encoder encodes the input images to extract compact image features. The decoder, on the other hand, decodes the extracted features, to reconstruct the input images.

For this purpose, we use the MNIST dataset, which is directly downloaded from the torchvision.datasets.
