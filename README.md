
# DEEP LEARNING FOR DATA ANALYTICS
__Copenhagen Summer University, 21-25 August 2017__

Frederiksberg Campus  
Bülowsvej 17  
1870 Frederiksberg  
Denmark

http://www.big-data.dk/csu/

# Getting Started
One of the texts used during this course is:

__Deep Time Series Forecasting with Python__  
An Intuitive Introduction to Deep Learning for Applied Time Series Modeling  
by N.D. Lewis  
ISBN-13: 978-1540809087

This section covers the general assumptions made about which programming languages and support modules are to be used when attempting to perform the exercises in each chapter. If you want to run these scripts on your own computer, then you will need to install the following:

__Python 2.7__  
As mentioned in the beginning of the book, all the code presented is intended to work with Python 2, specifically Python 2.7.11. Therefore, we also suggest that you use this or some later version of Python 2.7.

If you are new to Python, try installing a Python distributions called `anaconda` to get started. Use the following link to find a [download option for your operating system](https://www.continuum.io/downloads). We highly recommend using `anaconda` as it will make it easier to install the support modules need to follow the exercises from the text book.

Furthermore, the exercises in the book use a number of support models. Some support models such as `matplotlib`, `numpy`, `pandas`, `scipy`, and `scikit-learn` are already included in `anaconda`, however others are not. Below is a collection of links where you can find download and installation instructions for the required support modules not included in `anaconda`.


__Keras__ is a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano. To install `Keras` you can either [read and follow the instructions from the documentation](https://keras.io/#installation) or instead you can try the following `pip` command:

`    sudo pip install keras`


__Theano__ is a Python library that allows you to define, optimize, and evaluate mathematical expressions involving multi-dimensional arrays efficiently. To install `Theano` please read the documentation for installation on your operating system [here](http://deeplearning.net/software/theano/install.html). However, most of you should be able to use the following `conda` command to install `Theano`.

`    conda install theano pypgu`


__nnet-ts__ is a neural network architecture for time series forecasting. This packages relies heavily on `numpy`, `scipy`, `pandas`, `theano` and `keras`. Check on their repositories how to install them first. Then, simply fetch the package using `pip`:

`    sudo pip install nnet-ts`

Otherwise, you can get the module from GitHub [here](https://github.com/hawk31/nnet-ts).


__pyneurgen__ provides libraries for use in Python programs to build hybrids of neural networks and genetic algorithms and/or genetic programming. If you are using `anaconda` then you should be able to use the following command to install `pyneurgen`:

`    sudo pip install pyneurgen`

Otherwise, you can get the module [here](https://pypi.python.org/pypi/pyneurgen/0.3.0).


### NOTICE 
Since random numbers are involved in many of the examples below, the exact results from the book may or may not be reproduced in this worksheet, since that would require the same versions of Python and each of the Python libraries. However, as we will see, the exact results are not necessary to show that the code produces the expected results!
