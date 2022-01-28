This Assignment shows the comparision of different aspects of a deep learning model.

1.** Vary the number of hidden layers to see the affects on validation and test accuracy.**
General observation :The number of hidden layers is reduced it has a direct impact on the accuracy of the network as with the complex problem having less number of hidden layers it might be possible that network will not be trained properly. On the other hand when the number of hidden layers cross the optimal number of hidden layers (three layers), time complexity increases in orders of magnitude as compared to the accuracy gain.The techniques implementing less than three number of hidden layers mostly had a loss in accuracy while the architecture implementing more than three numbers of hidden layers were found not to be optimal in terms of time complexity.

2. **Vary the number of hidden units or nodes**
General observation : If we use a few hidden units, we will end up getting high training error and high generalization error due to underfitting and high statistical bias.
If we use too many hidden units, we may get low training error but still have high generalization error due to overfitting and high variance.

3.**Use different loss functions and compare**
General observation - The cross-entropy is the best to use in the output layer of your network if it has a sigmoid or softmax nonlinearity.
If instead we assume the target is continuous and normally distributed, and we need to maximize the likelihood of the output of the net under these assumptions,we can use MSE
For classification, cross-entropy tends to be more suitable than MSE.

4.**Use different activation funtion and plot the affects**
