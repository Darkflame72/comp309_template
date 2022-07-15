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

You can then at by pressing `ctrl shift p`/`cmd shit p` and then typing `Python: Select Interpreter` use the virtual environment created by poetry which is listed when running `poetry shell` this means that all your dependencies are in the same place and won't conflict with anything else.