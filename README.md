# COMP309 Template
This is a template setup for comp309, it installs all the required libraries and sets up the environment.


## Tools
### VSCode
This uses Visual Studio Code as the IDE, it also recommends some extensions allowing us to work with jupyter notebooks inside of the ide.

### Poetry
Python Poetry is used as the package manager as it is more powerful and more versatile then anaconda or native pip. More details can be found at https://python-poetry.org.

## Setup
Setup of the project is easy requiring you to have [poetry](https://python-poetry.org) installed and then running the following commands:

```bash
poetry install
poetry shell
```

When you have the jupyter notebook open in the top right you can select the interpreter which should be the virtual env created by poetry.