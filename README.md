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
poetry init
poetry shell

````