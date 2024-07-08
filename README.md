# Basic_Nueral_Network

### Objective
The primary objective is to predict the output value y based on two input features x1 and x2 using a basic neural network model with the equation y=3x1+4x2. The neural network will be trained using a feed-forward and back-propagation mechanism to minimize the error between the predicted and actual values.

### Methodology
1. Activation Functions:
● Define the sigmoid function, a popular activation function used in neural
networks.
● Define the tanh function, which is another common activation function that
returns values between -1 and 1.
● Define the relu function, which returns positive values as they are and
zeroes out negative values.
2. Sample Data:
● Use the following sample data for training:
x1=3, x2=2, yactual=17
3. Feed Forward:
● Initialize the random weights w1 and w2 between 1 and 10.
● Predict the output ypred using the equation ypred= x1 x w1 + x2 x w2
4. Error Calculation:
● Compute the squared error as error = (yactual-ypred)*(yactual-ypred)
5. Back Propagation:
● Compute the gradients of the error with respect to the weights.
● Update the weights using the computed gradients and a learning rate.
6. Training:
● The above steps (Feed Forward to Back Propagation) are performed
iteratively (20 times in this example) to refine the weights and minimize
the error.
7. Visualization:
● Plot the progression of the error across epochs.
● Plot the progression of ypreds across epochs.

### Expected Outcome
After sufficient training, the predicted ypred should be close to the actual value yactual=17. The error graph should show a declining trend, indicating that the model is learning and improving its predictions over time.
