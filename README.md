Firstly, create a new virtual environment & activate newly created virtual environment(.venv/Scripts/activate).</br>
Then add project folder & add python package (create your package).</br>

ProjectName</br>
|__ __init__.py</br>
|__ ModuleName.py</br>

Now, add pyproject.toml file & add respective metadata. Add setup.cfg, README.md.</br>

ProjectName</br>
|__ __init__.py</br>
|__ ModuleName.py</br>
pyproject.toml</br>
setup.cfg</br>
README.md</br>

Install poetry: '(Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | python –'.</br>
Add to environment path variable: 'C:\Users\poonamc\AppData\Roaming\pypoetry\venv\Scripts'.</br>
Run 'poetry --version' cmd to check if poetry is installed successfully.</br>
Now, run 'poetry build' it will generate dist folder and .whl & .tar.gz files inside dist.</br>
