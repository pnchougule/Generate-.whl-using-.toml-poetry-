1. Firstly, create python package.

ProjectName
|__ __init__.py
|__ ModuleName.py

2. Now, add pyproject.toml file & add respective metadata. Add setup.cfg, README.md.

ProjectName
|__ __init__.py
|__ ModuleName.py
pyproject.toml
setup.cfg
README.md

3. Install poetry: '(Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | python –'.
4. Add to environment path variable: 'C:\Users\poonamc\AppData\Roaming\pypoetry\venv\Scripts'.
5. Run 'poetry --version' cmd to check if poetry is installed successfully.
6. Now, run 'poetry build' it will generate dist folder and .whl & .tar.gz files inside dist.
