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

```cmd
mkdir -p prediction_service/model
```

```cmd
mkdir webapp
```

```cmd
touch app.py
```

```cmd
touch prediction_service/__init__.py
touch prediction_service/prediction.py
```

```cmd
mkdir -p webapp/static/css
mkdir webapp/templates
mkdir -p webapp/static/script
```

```cmd
touch webapp/static/css/main.css
touch webapp/static/script/index.json
touch webapp/templates/index.html
touch webapp/templates/404.html
touch webapp/templates/base.html
```

