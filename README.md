# MNIST_with_KERAS

The data files train.csv and test.csv contain gray-scale images of hand-drawn digits, from zero through nine.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.

The training data set, (train.csv), has 785 columns. The first column, called "label", is the digit that was drawn by the user. The rest of the columns contain the pixel-values of the associated image.

Tried doing with the below Layers and combinations
1)softmax classifier
2)MLP + Sigmoid activation + SGDOptimizer
3)MLP + Sigmoid activation + ADAM
4)MLP + ReLU +SGD
5)MLP + ReLU + ADAM 
6)MLP + Batch-Norm on hidden Layers + AdamOptimizer
7)MLP + Dropout + AdamOptimizer
8)Hyper-parameter tuning of Keras models using Sklearnfor SIgmoid and Relu
