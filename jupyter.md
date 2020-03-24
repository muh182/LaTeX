# Installation Process
## Installation Python
* Install python 3.7.14 from this [link](https://www.python.org/downloads/release/python-374/) (Note: There might be issues with the newer python versions)
* Use _pip3_ to install jupyterlab and all other packages (Note: _pip3_ is shipped with python)

## Install Jupyterlab
* Install _jupyterlab_ `pip3 install jupyterlab` (Note: The installation should start)
* Test the installation with typing `jupyter notebook` (A new therminal will be opened)

## Install Tensorflow
* Install tensorflow `pip3 install "tensorflow>=1.15,<2.0"` (Older version 1.15.2 and not version 2)
* Test tensorflow with 
```
>> % python3
Python 3.7.4 (v3.7.4:e09359112e, Jul  8 2019, 14:54:52) 
>>> % import tensorflow as tf
>>> % print(tf.__version__)
1.15.2
>>> 
```
* Install _matplotlib_ `pip3 install matplotlib`
* Install _scipy_ `pip3 install scipy`
* Install _pandas_ `pip3 install pandas`
* Install _sklearn_ `pip3 install sklearn`

# Usage
## Enable Zoom In in a Plot
### Option 1
* Install `mpld3` with `pip install mpld3`
* Add this command 
```
%matplotlib inline
import mpld3
mpld3.enable_notebook()
```
### Option 2
* Add this code
```
import matplotlib
matplotlib.use('nbagg')
import matplotlib.pyplot as plt
```
* [Reference](https://stackoverflow.com/questions/10655217/ipython-notebook-pylab-inline-zooming-of-a-plot)
