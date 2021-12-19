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
3. Install python dependencies
```shell-session
pip install -r requirements.txt
pip install -r torch_requirements.txt -f https://download.pytorch.org/whl/lts/1.8/torch_lts.htm
sudo apt-get install python3-tk  -y
```
4. Install system dependency EVALB
```shell-session
wget -O /tmp/EVALB.tgz https://nlp.cs.nyu.edu/evalb/EVALB.tgz
tar zxf /tmp/EVALB.tgz
cd /tmp/EVALB
sudo make
sudo cp -r /tmp/EVALB /usr/local/lib/EVALB
sudo ln -sf /usr/local/lib/EVALB/evalb /usr/local/bin/
```
5. Download spaCy English Model
```shell-session
python -m spacy download en_core_web_md
```

## Start jupyter
```shell-session
jupyter notebook
```

## Maintainer
- Elayne Lemos [@elaynelemos](https://github.com/elaynelemos)
