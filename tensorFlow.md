## Installation of Tensorflow and Dependencies on MAC

* Install `pip`: 'sudo easy_install pip'
* Install `virtualenv`: `sudo pip install virtualenv`
* Intall `tensorflow` through:
   * `virtualenv`: `virtualenv --system-site-packages ~/tensorflow`
   * `pip install tensorflow==1.2.0 --ignore-installed`
* Navigate to the __bin__ folder: `cd ~/tensorflow/bin`
* Activate tensorFlow: 
   * For TSCH: `source activate.csh`
   * For Bash: `source ./activate`
* Add this path:
   * For bashrc or terminal: `export PYENV_ROOT=/usr/local/opt/pyenv`
      * Add this line for future use: `vi ~/.bash_profile`
   * For tcshrc: `setenv PYTHONHTTPSVERIFY 0`
* Make sure to see this configuration if the username is __test__: `[tensorflow] /Users/test/tensorflow/bin 90`
* Install __xlrd__: `pip install xlrd`
* Install __matplotlib__: `pip install matplotlib`
   * Add `--ignore-installed six` if you receive a related error message: `pip install --ignore-installed six`
   * Add to __matplotlib__:
   * Navigate to __matplotlib__ folder in the main user folder: `cd ~/.matplotlib`
   * Open __vi__ and add this file: `backend: TkAgg`
   * Open vi __matplotlibrc__ and add this file: `backend: TkAgg`
