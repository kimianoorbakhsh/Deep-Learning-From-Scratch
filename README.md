# Deep-Learning
My implementations of some deep learning algorithms (In Progress)
## Deep-Neural-Network.py
An impementation of an L-layer neural network with this pattern : [LINEAR->RELU]*(L-1)->LINEAR->SIGMOID 
## CNN-Model-From-Scratch.py
Implement convolutional and pooling layers in numpy, including both forward propagation and backward propagation.
## Convolution-Tensorflow.py
Implements a three-layer ConvNet in Tensorflow: CONV2D -> RELU -> MAXPOOL -> CONV2D -> RELU -> MAXPOOL -> FLATTEN -> FULLYCONNECTED (The older version of Tensorflow is used here)
## Resnet-Impelementation.py
Implementation of the popular ResNet50 the following architecture: CONV2D -> BATCHNORM -> RELU -> MAXPOOL -> CONVBLOCK -> IDBLOCK*2 -> CONVBLOCK -> IDBLOCK*3 -> CONVBLOCK -> IDBLOCK*5 -> CONVBLOCK -> IDBLOCK*2 -> AVGPOOL -> TOPLAYER WITH KERAS
