# Kamal Saltani | Data Science Portfolio

I use Python to study how models learn, how to evaluate them, and how to explain their predictions. This collection grew out of my studies at Lewis University and MIT. The notebooks range from applied classification problems to statistical tests implemented from scratch.

## Selected notebooks

| Question | What to look for | Notebook |
| --- | --- | --- |
| How do you evaluate a fraud classifier when only about 0.17% of transactions are fraudulent? | Compare logistic regression, XGBoost, and random forest baselines. Examine the confusion matrices to see which fraud cases the models miss, then explore oversampling and undersampling. | [Credit card fraud and class imbalance](Projects/Pre-Processing%20Pipeline/samplng-techniques-for-imbalanced-classification.ipynb) |
| Why did a random forest misclassify a file? | The notebook ranks features by permutation importance, then uses SHAP to examine individual false positives and false negatives in the ClaMP malware dataset. | [Explaining classification errors](Projects/Machine%20Learning%20Explainability/model-explainability-for-classification.ipynb) |
| How closely does a hand-calculated hypothesis test agree with SciPy? | Follow a one-sample t-test from simulated observations to its test statistic and p-value. Later examples compare groups using the Kruskal–Wallis and Friedman tests. | [Hypothesis tests from scratch](Statistical%20Inference/major-hypothesis-tests-from-scratch.ipynb) |
| How does combining many trees change a prediction? | Follow the bootstrap sampling and voting logic on Titanic passenger data, then compare the custom ensemble with scikit-learn’s implementation. | [Bagging and random forests](Machine%20Learning%20%28ML%29/SupervisedMachineLearning/Ensembles/bagging-and-random-forest-ensemble-from-scratch.ipynb) |

## Explore by method

- **Supervised learning** — [Logistic regression](Machine%20Learning%20%28ML%29/SupervisedMachineLearning/Generalised%20Linear%20Models%28GLM%29/logistic-regression-from-scratch-v2.ipynb) and [gradient boosting for regression](Machine%20Learning%20%28ML%29/SupervisedMachineLearning/Ensembles/gradient-boosting-from-scratch-regression.ipynb).
- **Unsupervised learning** — [K-means](Machine%20Learning%20%28ML%29/UnsupervisedMachineLearing/Clustering%20Techniques/k-means-clustering-from-scratch.ipynb), [DBSCAN](Machine%20Learning%20%28ML%29/UnsupervisedMachineLearing/Clustering%20Techniques/dbscan-from-scratch.ipynb), and [principal component analysis](Machine%20Learning%20%28ML%29/UnsupervisedMachineLearing/Dimentionality%20Reduction/pca-from-scratch.ipynb).
- **Neural networks** — Start with the [multilayer network](Artificial%20Neural%20Network%28ANN%29/artificial-neural-network-from-scratch-l-layer.ipynb), then explore [regularization and dropout](Artificial%20Neural%20Network%28ANN%29/ann-from-scratch-sgd-reg-drop-out.ipynb).

Open a notebook on GitHub to read its code and saved outputs. To rerun the fraud example locally, download the [credit card fraud dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud), update the CSV path in the loading cell, and use a Jupyter environment with the packages imported at the top of the notebook. The hypothesis-testing example generates its own observations.

## Related applied projects

- [Federal Program Performance & Spending Analytics](https://github.com/saltanikamal/federal-program-performance-analytics) uses Python and SQL to trace changes in federal contract obligations and presents the analysis in Streamlit.
- [Financial Market Analytics Platform](https://github.com/saltanikamal/financial-market-analytics-platform) applies tree ensembles to market time series, evaluates them on later observations, and serves predictions through FastAPI.
