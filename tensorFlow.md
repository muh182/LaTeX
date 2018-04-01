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
* Install __pandas__:
   * `pip install pandas`
   * (In case of errors): `pip install --ignore-installed pandas`
   
## Installation of jython
* Install __jythin__: `brew install jython`
* Set up __jython__: [`sudo pip install execnet`](https://codespeak.net/execnet/example/hybridpython.html)
* In case of using __Homebrow__ and __tcsch__, you need to add jython to the path. For example,
`` set path = ($path /usr /usr/bin /usr/local/bin /sw/bin /usr/sbin /usr/X11R6/bin /usr/local/homebrew/Cellar/ant/1.10.1/libexec/bin /usr/local/homebrew/Cellar/git/2.15.1_1/bin /usr/local/homebrew/Cellar/scala/2.12.4/bin /usr/X11R6/bin /usr/local/texlive/2017/bin/x86_64-darwin /usr/local/homebrew/Cellar/jython/2.7.1/bin)``

## Update TensorFlow
* Install tensoflow 1.5 `http://www.python36.com/install-tensorflow-using-official-pip-pacakage/`


## Deep Learning + Bayesian Reasoning
* Download the code from here [`https://github.com/thu-ml/zhusuan`] 
* Run the script `sudo pip install`
