# Build a Basic CNN using Keras

![Image](https://miro.medium.com/max/770/1*1_RWtODBJ1MhYwRSJ-XCbw.png)

This is a beginner's guide to developing a simple convolutional neural network (CNN) using the Keras library in Python. The CNN will be used to perform a basic image classifcation task on the MNIST dataset.

## Environment setup

You will require the following software to perform this task:

- *Python 2.7* (or above)
- *pip* (a python package installer)
- *Keras* (a python library for working with neural nets)
- *NumPy* (a python library to help manage large arrays of data)
- *Matplotlib* (a python library for plotting visualisations)

There is no need to download the image dataset for this particular task as this is contained within the Keras library.

### Environment setup

Given that python and pip have been installed on your machine, use the following terminal commands to install the required libraries:

```
pip install keras
```
```
pip install matplotlib
```
```
pip install numpy
```


## Implementation

The following code can be used to develop a simple CNN in one .py file. Complete code can be found in the net.py file in this repository.

### Library imports

We must firstly import the libraries we earlier installed:

```
# import libraries
from keras.datasets import mnist
from matplotlib import pyplot
```
---

### Data preperation



