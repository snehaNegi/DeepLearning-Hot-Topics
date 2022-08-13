# DeepLearning-Hot-Topics


[**1.Back Propagation Implementation**](https://github.com/snehaNegi/DeepLearning-Hot-Topics/blob/main/1.%20Implementing%20Backpropagation) 


DataSet used: emotion_classification

**Our Task:**
The above dataset has training/test subject faces with happy/sad emotion are providedin the data. Each image is of 100×100 matrix. 

a. Perform PCA to reduce the dimensionfrom 10000 to K= 12. 

b. Implement a 1 hidden layer deep neural network (layer containing10 neurons) to classify the happy/sad classes. Use the crossentropy error function with softmax output activations and ReLU hidden layer activations.

Perform 20 iterations of back propagation and plot the error on training data as a function of the iteration. What is the test accuracy for this case and how does it change if thenumber of hidden neuron size increased to 15. 

[Implement backpropagation by hand without using any tool].


[**2.Implementing CNN and DNN**](https://github.com/snehaNegi/DeepLearning-Hot-Topics/blob/main/2.%20DNN%20and%20CNN%20implementation)

DataSet used: MNIST data - Download the dataset of hand-written digitshttp://yann.lecun.com/exdb/mnist/ containing 10 classes.
 
**Our Task:** 

The PyTorch package is needed for the following tasks https://pytorch.org/

(a)Implementing DNNs - Use the PyTorch package to implement a DNNmodel with 2and 3 hidden layers. Each hidden layer contains 512 neurons. What is the perfor-mance on the test dataset for this classifier

(b)Implementing CNNs - Use the same package to implement a CNN model with one layer of convolutions (kernel size of 3×3 with a 2-D convolutional layer and having 128 filters) followed by two dense layers of 256 neurons. Compare the performanceof the CNN with the DNN.

(c) Provide your answers with analysis, plots for various choices of hidden layer dimen-sions and filter sizes in the CNN.

[Reduce the number of samples in training data if your computing powers are limited as required by random subsampling]
