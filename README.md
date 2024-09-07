# Image-Classification-with-CNNs

I dive into image classification using CNNs, applying it to the popular MNIST dataset. This tutorial covers everything you need to know to build a robust CNN model from scratch, all the way to achieving impressive accuracy rates. Here’s a glimpse of what’s included:

Data Preprocessing: 
Starting with the MNIST dataset, I loaded, normalized, and reshape the data to make it ready for CNN input. Using the `OneHotEncoder`, we convert labels into a format suitable for multi-class classification.

CNN Architecture: 
I’ve built a comprehensive CNN model using TensorFlow and Keras, featuring multiple convolutional and pooling layers. The model architecture includes:
Two Conv2D layers for feature extraction
MaxPooling layers to downsample the feature maps
Fully connected Dense layers to finalize the classification

Visualizing Layers: 
A key highlight of this exercise is visualizing the intermediate layers, including convolutional filters and feature maps. This helps in understanding how the model interprets and extracts features at each stage.

Model Performance: 
After training the model, it achieved over 99% accuracy on the test set after just 8 epochs! I've also explored predictions, accuracy, and errors through confusion matrices and visual comparisons between actual and predicted labels.

Advanced Visualization: 
I delved into visualizing CNN kernels and feature maps to understand the spatial hierarchies captured by the network. It’s fascinating to see how the layers detect edges, textures, and patterns from input images.
