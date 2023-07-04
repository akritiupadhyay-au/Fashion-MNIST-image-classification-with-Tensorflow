# Fashion MNIST image classification with Tensorflow

Fashion-MNIST is a dataset of Zalando's article images consisting of 60,000 training examples and 10,000 test examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes.
There are 10 classes in Fashion-MNIST: T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, and Ankle boot.

I have used a sequential model for the image classification. A TensorFlow sequential model for image classification is a type of neural network that is used to classify images. It is a linear stack of layers, where each layer takes the output of the previous layer as its input. The model described here has one input layer, three hidden layers, and one output layer.

The input layer is responsible for receiving the image data. The flatten function in this layer flattens the image data into a one-dimensional vector. This is done because the hidden layers cannot process multidimensional data.

The three hidden layers use the ReLU activation function. The ReLU function is a non-linear function that helps the model learn more complex relationships between the input data and the output labels.

The output layer uses the Softmax activation function. The Softmax function takes a vector of numbers and outputs a probability distribution over the possible labels. This means that the output layer will output a probability that the image belongs to each of the possible classes.

The TensorFlow Sequential model is a simple but effective model for image classification. It is easy to train and can achieve good accuracy on a variety of image classification tasks.

