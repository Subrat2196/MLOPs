hello_world
    - hello_world
        - __init__.py
        - main.py

# Virtual Environment 
```
python -m venv hello_demo  
.\hello_demo\Scripts\Activate
pip install setuptools twine
python setup.py sdist
twine upload --repository-url https://test.pypi.org/legacy/ \dist/hello_world_subrat_2196-0.0.1.tar.gz
```