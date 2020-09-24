# CIFAR10-on-MobileNets

Our primary objective, was to build an image classifier on the CIFAR - 10 dataset, which worked on MobileNets, an efficient and recently developed architecture which has significantly lesser training time for a minute tradeoff in accuracy of the classifier, which is targeted at applications in embedded or mobile devices. We built the image classifier using a Convolutional Neural Network combined with a Feedforward Neural Network for classification purposes.

# The network

![Our Network](https://i.imgur.com/ZUFRJZn.png)

# Conclusion and Future Work

| Width Multiplier | Accuracy achieved(%) |
|-----------------| ----------------------|
|1.0 MobileNet|71.2 |
|0.8 MobileNet|69.2|
|0.6 MobileNet|70.7|
|0.4 MobileNet|68.3|
|0.2 MobileNet|68.1|

We were able to build an artificial convolutional neural network that can recognize images with an accuracy of 71.2% using TensorFlow. We did so by pre-processing the images to make the model more generic, split the dataset into a number of batches and finally build and train the model.
