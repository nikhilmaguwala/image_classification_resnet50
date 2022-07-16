# Image Classification Using Resnet 50

We have used Resnet 50 for image classification.

Built Basic Classifier with [MATLAB](https://www.mathworks.com/products/matlab.html).

The network has an image input size of 224-by-224-by-3.


# Usage

This Requires [MATLAB](https://www.mathworks.com/products/matlab.html) (R2018b and above) and the [Deep Learning Toolbox](https://www.mathworks.com/products/deep-learning.html).

This NN have three functions:
- resnetLayers: Creates an untrained network with the network architecture of ResNet-50
- assembleResNet: Creates a ResNet-50 network with weights trained on ImageNet data
- Predict: Demonstrates how to classify an image using a trained ResNet-50 network