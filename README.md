# MNIST Handwritten Digit Classification Using CNN 

This is educationally oriented example of convolutional neural network (CNN) usage for image classification. 
All the code is in Python 3.6 and it comes in Jupyter notebook format. All phases of a machine learning development are covered from loading the data, exploring the data, scaling the data, building the CNN model, training the model, saving and loading the trained model and finally running predictions using the model. 

This program requires few additional packages to normal Python environment:
* __Numpy__ for processing data arrays.
* __Matplotlib__ for plotting diagrams.
* __Keras__ for the neural network programming API
* __Tensorflow__ or __Tensorflow-GPU__ for the neural network processing. 

Note that Tensorflow is not imported in the notebook code. Keras is wrapper on top of Tensorflow, so Tensorflow is used by the Keras package.

The neural network model can be trained using a average PC CPU, so no GPU is required for running this example. The model achieves about 99.2% accuracy on the MNIST test set. 