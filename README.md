create env

```bash
python3 -m venv /path/to/new/virtual/environment
```

activate env
```bash
source /path/to/new/virtual/environment/Scripts/activate
```

install requirements
```bash
pip install -r requirements.txt
```

run template.py file for creating basic structure
```bash
python template.py
```

initialize git
```bash
git init
```
initialize dvc
```bash
dvc init
```
 
 add data to dvc
```bash
dvc add -R data_given
```

add to git and commit
```bash
git add .
git commit -m "Your commit"
```

add remote repository
```bash
git remote add origin https://url
```

change branch name from master to main
```bash
git branch -M main
```

push changes to github
```bash
git push origin main
```

tox command -
```bash
tox
```

for rebuild
```bash
tox -r
```

pytest command -
```bash
pytest -v
```

setup command-
```bash
pip install -e .
```

build your own package commands-
```bash
pip install wheel
python setup.py sdist bdist_wheel
```

mlflow server command

mlflow server \
        --backend-store-uri sqlite:///mlflow-db.db \
        --default-artifact-root ./artifacts \
        --host 0.0.0.0 -p 1234