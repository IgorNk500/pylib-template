# Name of the lib
### Desc.
###### *(Go to [changelog](changelog.md))*

## Table of contents
1. [Installing](#installing)
2. ...
3. [Build](#build)
5. [Workflows](#workflows)

## Installing
```bash
python -m pip install pypi-id
```

...

## Build
### To build the wheel, run:
```bash
python -m pip install setuptools wheel
python setup.py bdist_wheel
```
Don't forget to change the config in the `pylib.json` file before doing this.\
**All wheels are stored in the `dist` folder**

***
### Also, you can use `pyproject.toml`:
```bash
python -m pip install build
python -m build
```

## Workflows
**This project contains one workflow that:**
+ collects the wheel library,
+ adds it to the release files,
+ and uploads the release to PyPi.

## If you encounter any errors, please open [issue](https://github.com/IgorNk500/pylib-template/issues/new "New issue") on GitHub.
