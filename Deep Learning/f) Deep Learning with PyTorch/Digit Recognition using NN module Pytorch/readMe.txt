In this example, I have used pytorch framework for creating Neural Network for digit recognition. This dataset contain 28 x 28 pixels of images and we will use batch size of 64 images.

It will have 784 inputs and 2 hidden layers. The size of hidden layer is 256 units along with 256 bias. The output layer will have 10 output neurons along with 10 bias. We will use sigmoid for activation and softmax function which will take image as input and provide probability distribution of different outputs.

For creating NN, I have used nn module of Pytorch.
