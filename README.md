# california housing model selection

compare several statistical learning methods on california housing dataset and evaluate their performance using cross validation and rmse.

---

## dataset

* california housing dataset
* 20640 samples
* 8 features
* target: median house value

dataset source:

https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html

---

## methods

* ridge regression
* lasso regression
* principal component regression (pcr)
* partial least squares (pls)

---

## workflow

1. load and explore data
2. data visualization
3. train-test split
4. ridge regression
5. lasso regression
6. pcr
7. pls
8. model comparison

---

## evaluation

* rmse
* cross validation

---

## visualizations

* target distribution
* correlation matrix
* income vs house value
* ridge cv curve
* lasso coefficients
* pcr components
* pls components
* model comparison

---

## libraries

* numpy
* pandas
* matplotlib
* seaborn
* scikit-learn

---

## results

the models show different behaviors in terms of regularization and dimensionality reduction.

ridge provides stable predictions.

lasso performs feature selection by shrinking coefficients.

pcr reduces dimensions using principal components.

pls uses latent variables to improve prediction.

the final model performance is compared using rmse.

---

## project structure

```text
california-housing-model-selection/

│
├── california_housing_model_selection.ipynb
├── requirements.txt
├── README.md
└── images/
```

---

## author

amirmahdimanaseir
