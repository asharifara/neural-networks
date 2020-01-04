# Neural Networks using Scikit-Learn
Building Neural Networks

1. MLP Regression for numeric data (using scikit-learn)
2. MLP Classification for numeric data (using scikit-learn)
3. MLP Classification for Text data (using scikit-learn)
4. MLP Classification for Image data (using scikit-learn)
5. Dimensionality Reduction using Restricted Boltzmann Machines



## Selection of layers and neurons :
How to choose the number of layers and neurons in the neural network 

1. The input layer (depends on the number of features in the dataset)
2. hidden layers:
    it depends on the complexity of the problem. 
    if the problem is a linear relationship, then we do not need to have hidden layer
    if the problem has a simple Non-linear relationship, then we only need to have one(1) hidden layer.
    if there is a Non-linear relationship between input and output, we can use 2 or more.

The number of hidden neurons also can be varied and there is no fixed rule for choosing the number of hidden neurons in the hidden layer, but 
there are some rules :
    - (number of inputs + output ) * (2/3)
    - not more than twice of the input layer size

3. output layer (depends on the number of classes in the prediction class ex. 0 and 1 to find out an email is spam or not)


