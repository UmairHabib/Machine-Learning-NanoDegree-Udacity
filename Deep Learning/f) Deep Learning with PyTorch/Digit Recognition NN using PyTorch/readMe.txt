In this example, we will use PyTorch to find out probability distribution of given image. Given an image it will calculate its probability of prediction.

We have used MNIST dataset of digits which has 28 by 28 pixels for each image.

We will use forward pass for finding error i.e. Mean Squared Error and backward propagation to calculate gradients. In this we have used 784 neurons on input layer, 128 on first hidden layer and 64 on second hidden layer. At output layer, we have used 10 neurons for classification of digits using probability distribution.
