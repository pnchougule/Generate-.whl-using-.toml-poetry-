1. Firstly, create python package.

ProjectName</br>
|__ __init__.py</br>
|__ ModuleName.py</br>

4. Now, add pyproject.toml file & add respective metadata. Add setup.cfg, README.md.

4. ProjectName
6. |__ __init__.py
7. |__ ModuleName.py
8. pyproject.toml
9. setup.cfg
10. README.md

11. Install poetry: '(Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | python –'.
12. Add to environment path variable: 'C:\Users\poonamc\AppData\Roaming\pypoetry\venv\Scripts'.
13. Run 'poetry --version' cmd to check if poetry is installed successfully.
14. Now, run 'poetry build' it will generate dist folder and .whl & .tar.gz files inside dist.
