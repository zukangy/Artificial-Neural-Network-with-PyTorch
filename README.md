# ArtificialNeuralNetwork with PyTorch

The motivation behind this project is to simplify the process of constructing an artificial neural network with PyTorch. When I first learned to scratch a ANN with PyTorch, I needed to manually increase lines of code to increase the complexity of the ANN model. I was convinced that the manual way can be modified to take a list or a dictionary with the configurations of each layer in the neural network as input arguments, and a custom neural network will be auto-created accordingly. 

### Artificial neural network CPU and GPU versions.

For the GPU version, only the accuracy compuation changes.
In order to run this model on GPU, we only need to change the model and the traning tensor to GPU, which we can do outside of the ANN class.
