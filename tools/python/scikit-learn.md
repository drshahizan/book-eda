---
description: Machine Learning in Python
---

# 👂 Scikit-learn

🔗 [GitHub](https://github.com/scikit-learn/scikit-learn) | [Website](https://scikit-learn.org/stable/)

**scikit-learn** is a Python module for machine learning built on top of SciPy and is distributed under the 3-Clause BSD license.

The project was started in 2007 by David Cournapeau as a Google Summer of Code project, and since then many volunteers have contributed. See the `About us <https://scikit-learn.org/dev/about.html#authors>`\_\_ page for a list of core contributors.

It is currently maintained by a team of volunteers.

## Scikit-learn and Exploratory Data Analysis (EDA)

Scikit-learn is a popular Python library for machine learning tasks and is widely used in the context of exploratory data analysis (EDA). While EDA primarily focuses on understanding the data and extracting meaningful insights, Scikit-learn complements this process by providing a comprehensive set of tools and algorithms for data preprocessing, modeling, and evaluation.

Scikit-learn offers a wide range of functionalities that are beneficial during EDA. Some key features of Scikit-learn in the context of EDA include:

1. **Data Preprocessing**: Scikit-learn provides various preprocessing techniques such as scaling, encoding categorical variables, handling missing values, and feature selection. These preprocessing steps are crucial in cleaning and transforming the data to make it suitable for analysis.
2. **Feature Extraction and Dimensionality Reduction**: Scikit-learn offers techniques for feature extraction, such as Principal Component Analysis (PCA) and feature selection methods like SelectKBest and Recursive Feature Elimination (RFE). These techniques help identify the most relevant features and reduce the dimensionality of the dataset.
3. **Supervised Learning Algorithms**: Scikit-learn provides a wide range of supervised learning algorithms, including linear regression, logistic regression, decision trees, random forests, support vector machines (SVM), and more. These algorithms enable data scientists to build predictive models and understand the relationships between variables.
4. **Unsupervised Learning Algorithms**: Scikit-learn includes unsupervised learning algorithms such as clustering algorithms (e.g., K-means, DBSCAN) and dimensionality reduction techniques (e.g., t-SNE). These algorithms assist in identifying patterns, grouping similar instances, and discovering underlying structures in the data.
5. **Model Evaluation and Validation**: Scikit-learn offers tools for model evaluation and validation, including techniques for cross-validation, performance metrics, and hyperparameter tuning. These tools help assess the performance of models, select the best model, and avoid overfitting or underfitting.

By utilizing Scikit-learn in the EDA process, data scientists can preprocess the data, apply feature extraction or dimensionality reduction techniques, build and evaluate models, and gain insights into the relationships and patterns within the dataset. Scikit-learn's extensive collection of algorithms and utilities makes it a powerful resource for conducting EDA and subsequent modeling tasks.

## Installation

Dependencies

scikit-learn requires:

* Python (>= |PythonMinVersion|)
* NumPy (>= |NumPyMinVersion|)
* SciPy (>= |SciPyMinVersion|)
* joblib (>= |JoblibMinVersion|)
* threadpoolctl (>= |ThreadpoolctlMinVersion|)

**Scikit-learn 0.20 was the last version to support Python 2.7 and Python 3.4.** scikit-learn 1.0 and later require Python 3.7 or newer. scikit-learn 1.1 and later require Python 3.8 or newer.

## User installation

If you already have a working installation of numpy and scipy, the easiest way to install scikit-learn is using `pip`

```
pip install -U scikit-learn
```

or `conda`

```
conda install -c conda-forge scikit-learn
```

The documentation includes more detailed `installation instructions <https://scikit-learn.org/stable/install.html>`\_.

## Important links

* Official source code repo: https://github.com/scikit-learn/scikit-learn
* Download releases: https://pypi.org/project/scikit-learn/
* Issue tracker: https://github.com/scikit-learn/scikit-learn/issues

## Source code

You can check the latest sources with the command

```
git clone https://github.com/scikit-learn/scikit-learn.git
```

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan\&labelColor=%23697689\&countColor=%23555555\&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
