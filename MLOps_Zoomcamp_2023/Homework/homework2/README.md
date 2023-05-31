# Homework 2 for MLOps Zoomcamp from DataTalks

link to homework questions [here](https://github.com/DataTalksClub/mlops-zoomcamp/blob/main/cohorts/2023/02-experiment-tracking/homework.md)

Q2 command:
```
python preprocess_data.py --raw_data_path ./data --dest_path ./output
```

Q3 command:
```
python train.py
```

Q4 command:
```
mlflow server --backend-store-uri sqlite:///backend.db --default-artifact-root ./artifacts_local
python hpo.py
```

Q5 command:
```
python register_model.py
```

All the python files with the modified code are in this homework2 folder
