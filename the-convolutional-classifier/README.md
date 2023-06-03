# The Convolutional Classifier

A convnet used for image classification consists of two parts: a convolutional base and a dense head.

![image](https://storage.googleapis.com/kaggle-media/learn/images/U0n5xjU.png)

The base is used to extract the features from an image. It is formed primarily of layers performing the convolution operation, but often includes other kinds of layers as well. (You'll learn about these in the next lesson.)

The head is used to determine the class of the image. It is formed primarily of dense layers, but might include other layers like dropout.

What do we mean by visual feature? A feature could be a line, a color, a texture, a shape, a pattern -- or some complicated combination.

The whole process goes something like this:

![image](https://storage.googleapis.com/kaggle-media/learn/images/UUAafkn.png)

The features actually extracted look a bit different, but it gives the idea.