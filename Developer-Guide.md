### Setup development environment

Run `flake8` before commit, edit your `underthesea/.git/hooks/pre-commit` file 

```
echo 'Run Flake8'
flake8 --max-complexity 10 --ignore E501,W504,W605 .
```