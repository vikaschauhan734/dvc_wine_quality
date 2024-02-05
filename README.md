### DVC Wine Quality Project

Steps:

```cmd
pip install -r requirements.txt
```

```cmd
git init
```

```cmd
dvc init
```

```cmd
dvc add data_given\winequality.csv
```

```cmd
git add . && git commit -m "first commit"
```

```cmd
git remote add origin https://github.com/vikaschauhan734/dvc_wine_quality.git
```

```cmd
git branch -M main
```

```cmd
git push -u origin main
```

For staging data:
```cmd
dvc repro
```

```cmd
mkdir report
```

For metrics check:
```cmd
dvc metrics show
```

For comparing new metrics with old metrics:
```cmd
dvc metrics diff
```

```cmd
mkdir tests
```

```cmd
touch tests/conftest.py tests/test_config.py tests/__init__.py
```

pytest command:
```cmd
pytest -v
```

```cmd
tox
```

For rebuilding the environment:
```cmd
tox -r
```


Setup commands:
For installing src package:
```cmd
pip install -e .
```

Build your own package commands:
```cmd
pip install wheel
python setup.py sdist bdist_wheel
```

