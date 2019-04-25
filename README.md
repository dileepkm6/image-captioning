# Image Captioning

captioning of image with Densenet121 and LSTM

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
1.Install Jupyter Notebook, TensorFlow, and Keras to your development environment.
2.For installing Jupyter Notebook, using Anaconda is very helpful.
3.Once you have installed all, start Jupyter Notebook on your web browser.
```

### Installing

A step by step series of examples that tell you how to get a development env running

```
1.Import Keras on your program and you will see it uses TensorFlow as backend.
2.Import pickle for saving the data
3.import os 
4.Import numpy
```
## Training the model

1.Load traing dataset from traing_data folder(training data is in form of dictionary)
2.Compile the model with adam optimizer
3.Fit the model with traning dataset


## Running the tests

1.Load the model from adam file from folder adam model
2.Use greedy search to generate the caption for a image


## Authors

* **Dileep Kumar Maurya** - *Initial work* - [dileepkm6](https://github.com/dileepkm6)


