# ParrotaiIPT2018: Week Two Progress Report.
## Foundation of deep Learning
Week two, deep learning was the topic to be covered, and the foundation of deep learning was presented by brother Frederick, and it provide general understanding of deep learning; 

By definition:
Deep Learning is subclass of machine learning algorithm that learn underlying features in data using multiple processing layers with multiple level of abstraction.
Success of deep learning:
  * Automatic colorisation
  * Image captioning
  * Object classification and detection
  * Image style transfer
  * Self driving car.
The difference between deep learning and machine learning is feature discovering and extraction is done automatically in deep learning while in machine learning its not.

### Multilayer Perceptron
perceptron is a simple model of a neuron
structure of a perceptron consist of 
  - input layer
  - activation function
    * sigmoid: output range from 0 to 1
    * tanH: output range from -1 to 1
    * ReLU: output 0 when its negative otherwise its output positive integer.
  - output layer. 

multilayer perceptron is the connection of more than one perceptron units together. consist of first layer which is input layer and pass infprmation to another layer, last layer which is the output layer and in the middle there is hidden layers, perfom computation and transfer layer from input layer. 
The sequence of multilayer perceptron:  
inpt => pre-actn => hd1 => actn => pre-actn => hd2 => actn => pre-actn => outpt => out-actn => output.  
where;
  - inpt == input layer
  - pre-actn == pre-activation fuction
  - hd1 == hidden layer one
  - actn == activation function
  - hd2 == hidden layer two
  - outpt == Output layer
  - out-actn == output activation function
  - output.

Output activation function depend on the type of the problem, for example;
  - Binary classification: where output is element of {0,1} => sigmoid
  - Multiclass calssification: where output is element of {0, k-1} => softmax
  - Regression: where output is element of real numbers => ReLU

#### Training deep neural network
I learned how to train deep neural network which involve several steps;
1. define loss function: the type of loss fucntion you are going to use depend on the type of output you are going to have.For example;
    * Binary classification: use binary class entropy.
    * Multiclass classification: use cross entropy.
    * Regression: use square error loss.

2. compute gradient
3. Solve optimasation problem

### Convolution Neural Networking

## Sequence Model

