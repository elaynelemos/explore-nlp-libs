# Explore NLP Libs

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)

Usage example for a couple of Natural Language Processing libraries.


## Config
- Python version: 3.8

## To start developing
1. Initialize a new virtualenv
```shell-session
virtualenv -p 3.8 .virtualenv
```
2. Enter the environment
```shell-session
source .virtualenv/bin/activate
```
3. Install the dependencies
```shell-session
pip install -r requirements.txt
```

4. Install `berkeley-parser-analyser` as submodule
```shell-session
git submodule update
```

4. Configure `berkeley-parser-analyser` package
```shell-session
cd berkeley-parser-analyser
python setup.py install
```

## Start jupyter
```shell-session
jupyter notebook
```

## Maintainer
- Elayne Lemos [@elaynelemos](https://github.com/elaynelemos)
