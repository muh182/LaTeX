# Installation
* Install python 3.6.10 from this [link](https://www.python.org/downloads/release/python-370/) (Note: There might be issues with the newer python versions)
* Use _pip3_ to install jupyterlab (Note: _pip3_ is shipped with python)
* Type `pip3 install jupyterlab` (Note: The installation should start)

# Open Terminal
* Type `jupyter notebook` and a new therminal will be opened

# Install Tensorflow
* Install _pip_ `python get-pip.py --user` (Note: `get-pip.py` needs to be downloaded)
* Modify the _PATH_ `sudo vi /etc/paths` to add Python 2 version link for _pip_ (i.e., `/Users/XYZ/Library/Python/2.7/bin` _XYZ_ is the user home directory)
* Review the _PATH_ `echo $PATH`
* Install tensorflow `pip install --user tensorflow==1.6.0`
* Install _nose_ `pip install --user nose`
* Install _tornado_ `pip install --user tornado`
* Install _matplotlib_ `pip install --user matplotlib` (Note: You may need it using _pip3_ `pip3 install matplotlib`)
* Install _gym_ `pip3 install gym`
