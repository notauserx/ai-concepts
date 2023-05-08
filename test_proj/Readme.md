# test project

## setup

```
 python -m venv venv
```

install the dependencies:

```
python -m pip install -U jupyter matplotlib numpy pandas scipy scikit-learn graphviz
```

update the deps in requirements file with

```
python -m pip freeze > requirements.txt
```

if you are having trouble activating the venv, set execution polity 

```
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted
```

## run

- active the virtual env

```
 .\venv\Scripts\activate
```

- install requirements

```
pip install -r requirements.txt
```

- run the jupyter env with

```
jupyter notebook
```