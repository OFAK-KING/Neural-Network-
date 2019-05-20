# Neural-Network-
This project implements a two-layer neural network (i.e. one hidden layer). Use this network to perform handwritten digit recognition task using the Semeion digit dataset. This digit archive is available here:  https://archive.ics.uci.edu/ml/datasets/Semeion+Handwritten+Digit  Neural Network structure: NN (neural network) will have one hidden layer with n hidden units (n should be a parameter of your program function) and 10 output units. The network should be fully connected.   Activation function: Hidden and output units should use the sigmoid activation function.   Bias unit: Every hidden and output unit should have a weighted connection from bias unit, whose value should be set to 1.  Output: The output units should correspond to one of 10 classes (1 to 9). Set the target value t k  for output unit k to 0.9 if input class is the kth class, 0.1 otherwise.   Training: Use backpropagation with SGD to train the network. Set the learning rate to 0.1.  Question 1: Experiment with varying the number of hidden units. (Each sub- question below is worth 10 points = 50 points total)   

1a. Conduct experiments with n = 20, 50 and 100. (Hint: remember to include bias unit weights).  Train network for 50 epochs. After each epoch, record accuracy on training set AND test set for network. After training is complete, create a confusion matrix for each of the trained networks, summarizing results on the test set.    

1b. Give a plot of both training and test accuracy as a function of epoch number (graph both of these on sample plot).  

1c. Discuss results. How does number of hidden units affect the final accuracy on the test data?   

1d. Discuss results. How does number of hidden units affect number of epochs needed for training to converge?   

1e. Is there any evidence that any of the networks overfit to the training data? If so, what is the evidence?   

Question 2: 

Experiment with varying the amount of training data. (Each subquestion below is worth 10 points = 50 points total)    

2a. Conduct experiments by fixing number of hidden units to 100. Instead  of using all of the training examples, train two networks, using respectively one  quarter and one half of the training examples for training. Make sure that in each  case training data is approximately balanced among the 10 different classes.   Train network for 50 epochs. After each epoch, record accuracy on training set AND test set for network. After training is complete, create a confusion matrix for each of trained networks, summarizing results on the test set.   

2b. Give a plot of both training and test accuracy as a function of epoch number  (graph both of these on sample plot).   

2c. Discuss results. How does size of training data affect the final accuracy on the test data?   

2d. Discuss results. How does size of training data affect number of epochs needed for training to converge?    

2e. Is there any evidence that any of networks overfit to the training data? If  so, what is the evidence?

Question 3: Experiment with features and hyperparameters of the model to increase the accuracy of the best model from
previous experiments. 

Document what changes you needed to make to achieve these results.
