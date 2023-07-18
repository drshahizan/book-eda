---
description: Machine Learning Visualization
---

# 🗳 Yellowbrick

🔗 [GitHub](https://github.com/DistrictDataLabs/yellowbrick/) | [Website](https://www.scikit-yb.org/en/latest/)

## What is Yellowbrick?

Yellowbrick is a suite of visual diagnostic tools called "Visualizers" that extend the scikit-learn API to allow human steering of the model selection process. In a nutshell, Yellowbrick combines scikit-learn with matplotlib in the best tradition of the scikit-learn documentation, but to produce visualizations for _your_ machine learning workflow!

For complete documentation on the Yellowbrick API, a gallery of available visualizers, the contributor's guide, tutorials and teaching resources, frequently asked questions, and more, please visit our documentation at [www.scikit-yb.org](https://www.scikit-yb.org/).

## Yellowbrick and Exploratory Data Analysis (EDA)

Yellowbrick is a Python library specifically designed for visual diagnostic tools that aid in the exploratory data analysis (EDA) process. It provides a wide range of visualizations and tools to help data scientists and analysts understand their data, identify patterns, explore relationships, and make informed decisions during the initial stages of data exploration.

Yellowbrick focuses on providing visualizations that enhance the understanding of machine learning models and assist in evaluating their performance. It complements other popular data analysis and machine learning libraries such as scikit-learn, allowing users to gain deeper insights into their models and make better-informed decisions.

With Yellowbrick, you can visualize various aspects of the data and models, including feature analysis, model selection, and performance evaluation. Some of the key features and visualizations offered by Yellowbrick include:

1. **Feature Visualization**: Yellowbrick offers visualizations such as histograms, scatter plots, and joint plots to explore the relationships between features and identify patterns, outliers, or potential issues in the data.
2. **Model Evaluation**: Yellowbrick provides visual tools like ROC curves, precision-recall curves, and confusion matrices to evaluate the performance of classification and regression models. These visualizations allow for a comprehensive analysis of model behavior and enable users to fine-tune their models accordingly.
3. **Clustering Evaluation**: For unsupervised learning tasks, Yellowbrick offers visualizations like dendrograms, silhouette plots, and elbow plots to evaluate clustering algorithms and identify the optimal number of clusters.
4. **Model Selection**: Yellowbrick includes tools like validation curves, learning curves, and residuals plots to assist with model selection and hyperparameter tuning. These visualizations help understand model performance and generalization capabilities.

By leveraging Yellowbrick's visual diagnostic tools, data scientists and analysts can gain valuable insights into their data, identify potential issues, validate assumptions, and select appropriate models for further analysis. Yellowbrick simplifies the process of exploring, analyzing, and interpreting data, enabling more effective decision-making and the development of reliable models.

## Installing Yellowbrick

Yellowbrick is compatible with Python 3.4 or later and also depends on scikit-learn and matplotlib. The simplest way to install Yellowbrick and its dependencies is from PyPI with pip, Python's preferred package installer.

```
$ pip install yellowbrick
```

Note that Yellowbrick is an active project and routinely publishes new releases with more visualizers and updates. In order to upgrade Yellowbrick to the latest version, use pip as follows.

```
$ pip install -U yellowbrick
```

You can also use the `-U` flag to update scikit-learn, matplotlib, or any other third party utilities that work well with Yellowbrick to their latest versions.

If you're using Anaconda (recommended for Windows users), you can take advantage of the conda utility to install Yellowbrick:

```
conda install -c districtdatalabs yellowbrick
```

## Using Yellowbrick

The Yellowbrick API is specifically designed to play nicely with scikit-learn. Here is an example of a typical workflow sequence with scikit-learn and Yellowbrick:

### Feature Visualization

In this example, we see how Rank2D performs pairwise comparisons of each feature in the data set with a specific metric or algorithm and then returns them ranked as a lower left triangle diagram.

```python
from yellowbrick.features import Rank2D

visualizer = Rank2D(
    features=features, algorithm='covariance'
)
visualizer.fit(X, y)                # Fit the data to the visualizer
visualizer.transform(X)             # Transform the data
visualizer.show()                   # Finalize and render the figure
```

### Model Visualization

In this example, we instantiate a scikit-learn classifier and then use Yellowbrick's ROCAUC class to visualize the tradeoff between the classifier's sensitivity and specificity.

```python
from sklearn.svm import LinearSVC
from yellowbrick.classifier import ROCAUC

model = LinearSVC()
visualizer = ROCAUC(model)
visualizer.fit(X,y)
visualizer.score(X,y)
visualizer.show()
```

For additional information on getting started with Yellowbrick, view the [Quick Start Guide](https://www.scikit-yb.org/en/latest/quickstart.html) in the [documentation](https://www.scikit-yb.org/en/latest/) and check out our [examples notebook](https://github.com/DistrictDataLabs/yellowbrick/blob/develop/examples/examples.ipynb).

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan\&labelColor=%23697689\&countColor=%23555555\&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
