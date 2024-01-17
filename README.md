# BackpropNN_Covid-PCRtest
This Python code implements a basic back propagation neural network using a hardcoded set of weights for predicting the result of a Polymerase Chain Reaction (PCR) test based on various medical parameters.

Here's a brief overview of the code:

Initialization:
Hardcodes initial weights for the hidden and output layers of the neural network.

Data Loading and Preprocessing:
Loads medical data from a CSV file, including features (X) such as age, blood cell counts, and platelets, and the target output (Y) indicating the PCR test result.

Train-Test Split:
Divides the data into training and testing sets.

Neural Network Architecture:
Defines the architecture of the neural network with one hidden layer.
Uses hyperbolic tangent (tanh) as the activation function for the hidden layer.

Training:
Applies forward propagation and backpropagation for a specified number of epochs to update the weights.

Testing:
Tests the trained neural network on the test set and calculates accuracy.

Confusion Matrix:
Computes and displays a confusion matrix to evaluate classification performance.

Visualization:
Creates scatter plots for each input feature against the actual PCR test result, colored by the network's predicted output.

The code provides insights into the neural network's performance in predicting PCR test results based on the given medical parameters. The visualization helps in understanding how well the network captures the relationships between individual input features and the test outcomes. Note that using hardcoded weights is a simplified example, and typically, weights are learned during training.





