created env 
```bash
conda create -n mlops python=3.7 -y

activate env
```bash

created  a req file

install the req

pip install -r requirements.txt

git init 
```bash
dvc init
```bash
dvc add data_given/winequality.csv

git add .

git commit -m "first commit"


git push

tox command

tox


for rebuilding

tox -r

pytest command

pytest -v

setup commands

pip install -e .


build your own package command-

python setup.py sdist bdist wheel