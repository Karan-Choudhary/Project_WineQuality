## WineQauality
Wine Quality is a popular dataset for learning Machine Learning algos.</br>
Using wine quality dataset, I implemented it as a MLOps project.

Created a pipeline to reproduce and tracking the model and results.

Used majorly to learn:
1. [DVC (Data Version Control)](https://dvc.org/)
2. [mlflow](https://mlflow.org/)

## Deployed on:
* Heroku

## Follows:
* Continuous Integration and Continuous Deployment
* Retraining Approachs


## Requirements:
requirements.txt

for installation
```
pip install -r requirements.txt
```

## For reproducing same results as mine use command:
```
dvc repro
```

## Testing done with:
* [tox](https://tox.wiki/en/latest/)

## Parameters present in:
* [params.yaml](https://github.com/Karan-Choudhary/Project_WineQuality/blob/main/params.yaml)

## DVC and mlflow configuration present in:
* [dvc.yaml](https://github.com/Karan-Choudhary/Project_WineQuality/blob/main/dvc.yaml)

## Recommendation:
Please create new [virtual environment](https://docs.python.org/3/library/venv.html) before use.

## Warning:
Do not try to edit dvc.lock file and .tox directory
