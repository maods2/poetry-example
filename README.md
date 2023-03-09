# Project Setup
1.  [Poetry Installation](https://python-poetry.org/docs/#installing-with-the-official-installer)
```
# For linux
curl -sSL https://install.python-poetry.org | POETRY_HOME=/etc/poetry python3 -

# For powershell
(Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | py -
```
2. To get started you need Poetry's bin directory (/home/user/.local/bin) in your `PATH`
environment variable.

````
nano ~/.bashrc
# Adding paths to your PATH
export PATH="/home/maodsunix/.local/bin:$PATH"

source ~/.bashrc
````
3. Check Poetry Version

````
poetry --version
````

4. Inicializing virtual env with poetry
````
poetry init or poetry new project_name
poetry shell


poetry add --group dev pytest
poetry add --group dev pytest-cov 
poetry add --group dev blue # PEP8 Formater
poetry add --group dev isort # import sorting
poetry add --group dev taskipy # automation scripting

poetry add --group doc mkdocs-material # Doc generator
poetry add --group doc mkdocstrings # Doc generator
poetry add --group doc mkdocstrings-python # Doc generator



````

