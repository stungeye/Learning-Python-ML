# Learning-Python-ML
Learning Python programming and various machine learning libraries.

## Installation

* Start with [PyEnv](https://github.com/pyenv/pyenv):
  * `git clone https://github.com/pyenv/pyenv.git ~/.pyenv`
  * `echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.bashrc`
  * `echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bashrc`
  * `echo -e 'if command -v pyenv 1>/dev/null 2>&1; then\n  eval "$(pyenv init -)"\nfi' >> ~/.bashrc`
  * `source ~/.bashrc`
  * Replace 3.6.5 with latest: `pyenv install 3.6.5`
* Next is [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io) and config env:
  * `pip3 install virtualenvwrapper`
  * `mkdir -p ~/.virtualenv`
  * `echo 'export WORKON_HOME=~/.virtualenv' >> ~/.bashrc`
  * `echo 'source /usr/local/bin/virtualenvwrapper.sh' >> ~/.bashrc`
  * `source ~/.bashrc`
  * `mkvirtualenv jupyter`
  
