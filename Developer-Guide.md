## Underthesea Project

### Setup development environment

Setup pre-commit hooks for running `flake8`, `black` and `pylint` before commit

* Step 1: Edit your `underthesea/.git/hooks/pre-commit` file 

```
echo 'Run Flake8'
flake8 --max-complexity 10 --ignore E501,W504,W605 .
echo 'Run Black'
black underthesea/utils/vietnamese_ipa.py
black underthesea/utils/vietnamese_ipa_rules.py
black --check underthesea/utils/vietnamese_ipa.py
black --check underthesea/utils/vietnamese_ipa_rules.py
echo 'Run pylint'
pylint ./underthesea/utils/vietnamese_ipa.py --fail-under 9
```

We're in the processing of applying `black` and `pylint`. A lot of works must be done for fully migrations.

* Step 2: Change permission 

```
$ chmod u+x .git/hooks/pre-commit
```

## Resources Project (Deprecating)

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

### Coding Convention

- **Linting Tool**: We use `flake8` to ensure our code adheres to PEP 8 standards and to catch any potential errors.
- **Documentation Style**: For docstrings, we follow the `Google Style` conventions to maintain clarity and consistency in our code documentation.

### Working with Datasets

Step 1: First, install [git-lfs](https://git-lfs.com/) (before submodule init)

Step 2: Initialize submodules

```
git submodule update --init --recursive
```

Step 3: Go to `datasets` folder to access and mangage datasets

## Tools 

For development and maintaince underthesea, we are using the following tools:

* Git (Github, Github Actions)
* Pycharm 2022.2.1 (Community Edition)
* Mac (Mac OS Monterey 12.4), Ubuntu (18.04, 20.04)
* Anaconda (conda 4.9.2)
* Python (3.8)
* Docker ([Playground](https://labs.play-with-docker.com/))
* Rust ([poetry](https://github.com/poem-web/poem) 1.1.14, [maturin](https://github.com/PyO3/maturin) 0.9.4)

Technologies for [Apps](https://github.com/undertheseanlp/underthesea/tree/main/apps)

* Django 3.2.16
* Bootstrap 3.3, Angular 1.6.5

Thanks for all awesome creators and maintainers.

## More articles

* [Model and Dataset Naming Convention](https://github.com/undertheseanlp/underthesea/wiki/Quy-t%E1%BA%AFc-%C4%91%E1%BA%B7t-t%C3%AAn-file-model-v%C3%A0-dataset)
* [CI/CD](https://github.com/undertheseanlp/underthesea/wiki/CI-CD)