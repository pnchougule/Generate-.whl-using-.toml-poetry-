Firstly, create python package

ProjectName
|__ __init__.py
|__ ModuleName.py
pyproject.toml
setup.cfg
README.md

Now, add pyproject.toml file & add respective metadata. Add setup.cfg, README.md
Install poetry
Add to environment path variable: 'C:\Users\poonamc\AppData\Roaming\pypoetry\venv\Scripts'
Run 'poetry --version' cmd to check if poetry is installed successfully
Now, run 'poetry build' to generate .whl & .tar.gz file inside dist folder 
