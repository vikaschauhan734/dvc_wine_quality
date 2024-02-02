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