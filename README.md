# MNIST---Digit-Classifier

The classifier is a simple convolutional neural network to classify the images of digits of the MNIST-dataset. The model uses Tensorflow 2.0

The loss and accuracy acheived on the test data is as follows: loss: 0.40 - accuracy: 0.98

Model Architecture: Input Data Shape: 28x28x1 

Layer 1:

Convolutional Layer Filters: 32

Filter shape: 3x3

Activation Function: ReLu

Max Pooling Pool shape: 2x2


Classification:

Flatten

Dense Layer1  Size: 128

Activation Function: Relu

Dense Layer2 Size:10

Activation Function: Softmax

Optimizer: Adam, Loss: Categorical Crossentropy, Metrics: Accuracy
