# END2.0_Learning

**What is a neural network neuron?**
A neural network has a set of neurons. A neuron is a small memory storage or a signal, that takes in input weights from other neurons and returns an output weight after using the weights and activation function. Neuron is a function that takes in outputs of the all the neurons in the previous layer and spits out a number between 0 & 1, after an activation function.

**What is the use of the learning rate?**
Learning rate is a configurable hyperparameter used in the training of neural networks, that has a small positive value ranging from 0.0 to 1.0.  The learning rate controls how quickly the model is adapted to the problem. A small LR requires more training epochs, while the larger LR result in rapid changes and require fewer training epochs.

**How are weights initialized?**
The weight initilizations for neural networks are important and are initilized randomly. However, there are few standard ways we can randomly initilize the weights for effective model training process based on the Activation function used in the nodes.
For Sigmoid/ TanH activation we use Xavier initilization where we will assume that our layer’s activations are normally distributed around zero.
The xavier initialization method is calculated as a random number with a uniform probability distribution (U) between the range -(1/sqrt(n)) and 1/sqrt(n), where n is the number of inputs to the node.
He Weight initilization is calculated as a random number with a Gaussian probability distribution (G) with a mean of 0.0 and a standard deviation of sqrt(2/n), where n is the number of inputs to the node.

**What is "loss" in a neural network?**
Loss is a prediction error of the Neural net, it is used to calculate the gradients, which are then used to update weights of the neural net. The method to calculate neural net is called Loss function.

What is the "chain rule" in gradient flow?
