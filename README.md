# MNIST-classification


Build classifiers using Keras and TensorFlow to solve the classifcation problem for Fashion MNIST data using Neural Network.

Accessed performance of the model with different optimizers (SGD, RMSProp,Adagrad and Adam) using RELU function on the fashion MNIST.

### To Execute:

Download the ipynb file and run it in Jupyter Notebook.


### Steps:

1) Load the data and standardize the inputs for model traning 

2) Setup the model with one hidden layers with activation function which is RELU in the first part and leaky ReLU in the second part 

3) Compile the model with optimizer of choice, loss function and the metrics 

4) Train the model and calculate the accuracy for the training data 

5) Predict the values for the test data and calculate the accuracy of the test data ReLU has 87.26% test accuracy and Leaky ReLU has 87% test accuracy
