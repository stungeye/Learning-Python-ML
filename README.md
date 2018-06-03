# Learning-Python-ML
Learning Python programming and various machine learning libraries.

## Installation of Python3, ML Libraries and Jupyter

This installation should work for Ubuntu or the Windows Ubuntu sub-system (WLS).

* Start with [PyEnv](https://github.com/pyenv/pyenv):
  * `git clone https://github.com/pyenv/pyenv.git ~/.pyenv`
  * `echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.bashrc`
  * `echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bashrc`
  * `echo -e 'if command -v pyenv 1>/dev/null 2>&1; then\n  eval "$(pyenv init -)"\nfi' >> ~/.bashrc`
  * `source ~/.bashrc`
  * Replace 3.6.5 with latest: `pyenv install 3.6.5`
  * `pyenv global 3.6.5`
  * Confirm version: `python -V`
  * Upgrade pip: `pip install --upgrade pip`
  * Confirm latest version: `pip -V`
* Next is [virtualenvwrapper](https://github.com/pyenv/pyenv-virtualenvwrapper) and config env:
  * `git clone https://github.com/pyenv/pyenv-virtualenvwrapper.git $(pyenv root)/plugins/pyenv-virtualenvwrapper`
  * `echo 'eval "pyenv virtualenvwrapper"' >> ~/.bashrc`
  * `source ~/.bashrc`
  * `mkvirtualenv jupyter`
  * Whenever you need this environment: `workon jupyter`
  * Or add this to your bashrc: `echo 'eval "workon jupyter"' >> ~/.bashrc`
* From within the `jupyter` environment the required libraries:
  * `pip install jupyter numpy scipy pandas matplotlib plotly seaborn scikit-learn`
* Then try our [Jupyter](https://jupyter.org/): 
  * ` jupyter notebook --no-browser`
  * Then open a browser tab to the provided URL.
  
