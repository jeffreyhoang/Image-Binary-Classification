# Cat vs Dog Image Classification using Keras CNN

This project implements a Convolutional Neural Network (CNN) using Keras to classify images of cats and dogs. The model performs binary classification, where it predicts whether an input image contains a cat or a dog. The dataset used for training consists of labeled images from the Cats vs Dogs dataset.

## Key Layers
- **Conv2D**: Extracts features from the input images using convolution.
- **MaxPooling2D**: Reduces the dimensionality of the feature maps.
- **Flatten**: Converts the 2D feature maps into a 1D vector.
- **Dense**: Fully connected layer for classification.
- **ReLU**: Outputs the final probability for binary classification.