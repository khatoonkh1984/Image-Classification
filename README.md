


Image classification is a supervised learning problem. Image classification applications are used in many areas, such as medical imaging, object identification in satellite images, traffic control systems, brake light detection, and machine vision. A convolutional neural network (CNN or ConvNet) is a network architecture for deep learning that learns directly from data. CNNs play a major role in image processing problems tasks like localization, segmentation, and video analysis for recognizing obstacles in self-driving cars.

How can this principle be implemented in a Convolutional Neural Network?

The work happens in the so-called convolution layer. To do this, we define a filter that determines how large the partial images we are looking at should be. We also define a step length that decides how many pixels we continue to calculate, i.e., how close the partial images are to each other. By taking this step, we have reduced the dimensionality of the image. The next step is the pooling layer. From a purely computational point of view, the same thing happens here as in the convolution layer, with the difference that we only take the average or maximum value from the result, depending on the application. It preserves small features in a few pixels, which are crucial for the task solution. Finally, there is a fully-connected layer, as we already know it from regular neural networks. Now that we have reduced the dimensions of the image.

