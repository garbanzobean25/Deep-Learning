#CNN Architechture
##Part 1:
Implement a CNN architecture that consists of 3 convolutional layers followed by a fully connected layer of 1000 units.
Each convolutional layer consists of a sublayer of 5x5 convolutional filters with stride 1 followed by a sublayer of 2x2 max-pool units with stride 2.
Each neuron applies ReLU activation function.
Task: Evaluate and plot the average training loss per epoch versus the number of epoches for the training dataset, for the following optimization algorithms:
- Mini-batch gradient descent
- Mini-batch AdaGrad
- Mini-batch RMSProp
- Mini-batch gradient descent with Nesterov’s momentum
- Mini-batch Adam
In addition, show the results by adding dropout.

##Part 2:
Design and implement a convolutional neural network for the CIFAR10 image classification task 
aiming to achieve a high test accuracy. Evaluate the classification accuracy by reporting 
top-1 and top-5 test error rates.
