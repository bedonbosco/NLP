## Underthesea Project

### Setup development environment

Setup pre-commit hooks for running flake8 before commit

* Step 1: Edit your `underthesea/.git/hooks/pre-commit` file 

```
echo 'Run Flake8'
flake8 --max-complexity 10 --ignore E501,W504,W605 .
```
* Step 2: Change permission 

```
$ chmod u+x .git/hooks/pre-commit
```

## Resources Project

Always build before commit

* Step 1: Edit your `resources/.git/hooks/pre-commit` file 

```
echo 'Build resources'
python build.py
```
* Step 2: Change permission 

```
$ chmod u+x .git/hooks/pre-commit
```

## Tools 

For development and maintaince underthesea, We are using the following tools

* Pycharm Community Edition
* Anaconda 
* Git (Github, Github Actions)