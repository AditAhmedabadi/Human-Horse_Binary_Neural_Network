# Human-Horse_Binary_Neural_Network
This is a Binary ConvNet Neural Network used to classify horses and humans. Made using convolutions , max poolings, flatten and dense layers using TensorFlow and Keras API.

The dataset is from kaggle

I have used 3 Convolution Layers of 16,32,64 filters of 3x3 dimension and 3 2x2 Max Poolings after every convolution layer. Then I used a flatten layer followed by a 512
hidden dense layer , followed by a 1 neuron output layer which uses sigmoid activation function (1/1+e^-x).

The optimizer used is RMSProp with learning rate of 0.001 and binary crossentropy loss. 

Fed the Neural Network 150x150 pixel images by preprocessing images using ImageDataGenerator in keras.preprocessing.image

Approx 98% accuracy on train data and approx 75% validation accuracy with loss of ~2.

Used 5 random images and classifier predicted each one correctly.
