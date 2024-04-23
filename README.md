Firstly, create python package.

ProjectName
|__ __init__.py
|__ ModuleName.py

Now, add pyproject.toml file & add respective metadata. Add setup.cfg, README.md.

ProjectName
|__ __init__.py
|__ ModuleName.py
pyproject.toml
setup.cfg
README.md

Install poetry.
Add to environment path variable: 'C:\Users\poonamc\AppData\Roaming\pypoetry\venv\Scripts'.
Run 'poetry --version' cmd to check if poetry is installed successfully.
Now, run 'poetry build' it will generate dist folder and .whl & .tar.gz files inside dist.
