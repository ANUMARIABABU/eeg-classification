# eeg-classification
  EEG signal classification using eeg dataset
    Here we define a model of the Neural Convolution Network (CNN) for the analysis of EEG signals. This can be achieved through the      Inserting CNN Classification layers.
   
   CONVOLUTIONAL NEURAL NETWORK:
     Convolution neural network is a type of deep learning neural network. They are also called artificial neural networks, artificial shift invariant or space invariant based on their common weight design and invariance translation characteristics. 
   Convolution Neural Network consisting of a layer of input and output as well as several hidden layers.  The hidden layer consists of a series of convolution layers that converge with the product of a multiplication or other line. The activation function is usually a RELU layer, followed by additional convolution layers, such as pooling layers, completely linked layers and normalization as followed.
 
 IMPLEMENTATION:
 The features are extracted from the classification dataset using the extraction technique of FFT functionality. Then these features are added for classification into our cnn model. First, the process is building a sequential model. Second, CONV1D creates the first layer of cnn that uses relu activation, batch normalization, and dropout layer. Similarly, the second layer is built using the same layers in which 50 percent of the neurons drop after the second layer and 20 percent of the neurons drop randomly after the first layer.  Next data is transformed to vectors using the flattening layer. Here we add flattening layer, dense layer that uses the function of relu activation and the layer of dropout uses the function of sigmoid activation. Following the development of the model learning curve, training and testing accuracy should be saturated either over fitting or under fitting and 82.01 percent accuracy.  When adding maxpooling layer to the model, the accuracy would increase to 84 percent. We have used batch size of 256.
 
