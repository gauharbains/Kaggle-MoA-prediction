# Kaggle-MoA-prediction  

This repository consists of my solution to the following kaggle competition: https://www.kaggle.com/c/lish-moa. Tu use the notebook, donwload the data from the kaggle site and copy it into the `Data` directory within the repository. 


## Requirements 

```
1. Tensorflow > 2.0
2. Keras 2.4.3
3. Seaborn 0.11.0
4. Scikit-learn 0.23.1
5. matplotlib
6. XGBoost 1.3.0.post0
```

## Summary of Workflow

```
1. Exploratory Data Analysis
2. Data Preprocessing
3. Grid search:1 to determine the optimum size of the Neural network architecture. 
4. Grid search:2 to determine the optimum value of the hyper parameters using cross validation.
5. Analyse the learning curves of the best selected model.
6. Create submission and get estimate of the performance. 
```
