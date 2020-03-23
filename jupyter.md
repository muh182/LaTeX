# Installation
* Install python 3.7.14 from this [link](https://www.python.org/downloads/release/python-374/) (Note: There might be issues with the newer python versions)
* Use _pip3_ to install jupyterlab (Note: _pip3_ is shipped with python)
* Type `pip3 install jupyterlab` (Note: The installation should start)

# Open Terminal
* Type `jupyter notebook` and a new therminal will be opened

# Install Tensorflow
Install tenosrflow with pip3 install tensorflow (Check version 1.15.0)
then do install pip3 install Jupyter notebook


# Install Tensorflow
* Install _pip_ `python get-pip.py --user` (Note: `get-pip.py` needs to be downloaded)
* Modify the _PATH_ `sudo vi /etc/paths` to add Python 2 version link for _pip_ (i.e., `/Users/XYZ/Library/Python/2.7/bin` _XYZ_ is the user home directory)
* Review the _PATH_ `echo $PATH`
* Install tensorflow `pip install --user tensorflow==1.6.0`
* Install _nose_ `pip install --user nose`
* Install _tornado_ `pip install --user tornado`
* Install _matplotlib_ `pip install --user matplotlib` (Note: You may need it using _pip3_ `pip3 install matplotlib`)
* Install _gym_ `pip3 install gym`

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

