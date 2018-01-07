## Quick tutorials to build Artificial Neural Networks with Watson Data Platform

**Note:** These tutorials are modified versions of the ones that already exist elsewhere (not initially created by myself). Links to the sources of the originals are indicated in each notebook.

## 1. Some concepts & terminology

**Feed-Forward Neural Networ (FFN)**
- https://en.wikipedia.org/wiki/Feedforward_neural_network
- The first and simplest type of artificial neural network
- Information moves only in one direction (forward) from the input nodes, through the hidden nodes (if any) to the output nodes.
- There are no cycles or loops in this network
- Alternative to e.g build a logistic regression classifier with scikit-learn.

**Convolutional Neural Network (CNN)**
- https://en.wikipedia.org/wiki/Convolutional_neural_network
- A type of a Feed-Forward ANN that is typically applied to analyze images (computer vision)
- Basically, CNN learns the image recognition filters that were traditionally hand-developed.

**Recurrent Neural Network (RNN)**
- https://en.wikipedia.org/wiki/Recurrent_neural_network
- Connections between units form a directed cycle
- RNN's can use their internal memory to process arbitary sequences of inputs
- This makes them applicaple to tasks such as unsegmented, connected handwriting recognition or speech recognition

**What is TensorFlow?**
- https://github.com/tensorflow/tensorflow
- TensorFlow is an open source computation framework for machine learning, originally developed at Google 

**What is Theano?**
- http://www.deeplearning.net/software/theano/
- Theano is a set of open source computation libraries for deep learning, created for Python

**What is Keras?**
- https://keras.io/
- Keras is an open source Neural Network library, written in Python, to implement higher level APIs for Neural Networks
- Mainly used for fast experimentation of Neural Networks!
- Same code can run on CPU or GPU
- User-friendly API for quick prototyping deep learning models
- In addition to implementing FFN's, Keras has built-in support also for convolutional networks (CNN, computer vision), recurrent networks (RNN, for sequence processing and combination of both
- Supports arbitary network architectures: multi-input or multi-output modes, layer sharing, model sharing etc.
- Keras is appropriate for building essentially any deep learning model, from a memory network to a neural Turing machine
- Can run on top of multiple backends, including TensorFlow, Theano etc.

## 2. Tutorial: Introduction to Keras
1. Sign up (if not already) & sign in to IBM Watson Data Platform: https://dataplatform.ibm.com
2. Click "New project"
3. Enter project name "Data Science" and leave other settings to defaults. Click "Create"
4. Go to "Assets" tab
5. On the "Notebooks" section, click "New notebook"
6. Select "From URL", type name "Intro to Keras" and paste the following Notebook URL:
https://github.com/jruponen/ann-with-wdp/blob/master/Introduction%20to%20Neural%20Networks%20with%20Keras.ipynb
7. Click "Create Notebook" and in a moment you should now have the "Hello World to Keras" Notebook open.

Follow the instructions on the Notebook to proceed.
**Note:** To clear all results and start from scratch, do the following:
1. From Notebook top menu, select: Cell > All Output > Clear
2. Proceed step-by-step through each cell with the "Run" button on the toolbar

## 3. Tutorial: Detect handwritten digits with Keras
1. Sign in to IBM Watson Data Platform and go to your project
2. Go to "Assets" tab
3. On the "Notebooks" section, click "New notebook"
4. Select "From URL", type name "Intro to Keras" and paste the following Notebook URL:
https://github.com/jruponen/ann-with-wdp/blob/master/Detect%20handwritten%20digits%20with%20Keras.ipynb
5. Click "Create Notebook" and in a moment you should now have the "Building a simple neural network..." Notebook open.

Follow the instructions on the Notebook to proceed.
**Note:** To clear all results and start from scratch, do the following:
1. From Notebook top menu, select: Cell > All Output > Clear
2. Proceed step-by-step through each cell with the "Run" button on the toolbar
