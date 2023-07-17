---
description: A plotting library for creating visualizations
---

# 📊 Matplotlib

🔗 [GitHub](https://github.com/matplotlib/matplotlib) | [Website](https://matplotlib.org/)

## Matplotlib: Visualization with Python

Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python. Matplotlib makes easy things easy and hard things possible.

* Create [publication quality plots](https://ieeexplore.ieee.org/document/4160265/citations?tabFilter=papers).
* Make [interactive figures](https://mybinder.org/v2/gh/matplotlib/mpl-brochure-binder/main?labpath=MatplotlibExample.ipynb) that can zoom, pan, update.
* Customize [visual style](https://matplotlib.org/stable/gallery/style\_sheets/style\_sheets\_reference.html) and [layout](https://matplotlib.org/stable/tutorials/provisional/mosaic.html).
* Export to [many file formats](https://matplotlib.org/stable/api/figure\_api.html#matplotlib.figure.Figure.savefig).
* Embed in [JupyterLab and Graphical User Interfaces](https://matplotlib.org/stable/gallery/#embedding-matplotlib-in-graphical-user-interfaces).
* Use a rich array of [third-party packages](https://matplotlib.org/mpl-third-party/) built on Matplotlib.

Matplotlib is an amazing visualization library in Python for 2D plots of arrays. Matplotlib is a multi-platform data visualization library built on NumPy arrays and designed to work with the broader SciPy stack. It was introduced by John Hunter in the year 2002. One of the greatest benefits of visualization is that it allows us visual access to huge amounts of data in easily digestible visuals. Matplotlib consists of several plots like line, bar, scatter, histogram etc.&#x20;

## **Installation**

&#x20;Windows, Linux and macOS distributions have matplotlib and most of its dependencies as wheel packages. Run the following command to install matplotlib package :

```
python -mpip install -U matplotlib
```

## **Basic plots in Matplotlib**&#x20;

Matplotlib comes with a wide variety of plots. Plots helps to understand trends, patterns, and to make correlations. They’re typically instruments for reasoning about quantitative information. Some of the sample plots are covered here. **Line plot :**&#x20;

{% tabs %}
{% tab title="Python3" %}
```
# importing matplotlib module
from matplotlib import pyplot as plt
 
# x-axis values
x = [5, 2, 9, 4, 7]
 
# Y-axis values
y = [10, 5, 8, 4, 2]
 
# Function to plot
plt.plot(x,y)
 
# function to show the plot
plt.show()
```
{% endtab %}

{% endtabs %}

Output : ![](https://media.geeksforgeeks.org/wp-content/uploads/line-plot-300x254.png)

```


[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan\&labelColor=%23697689\&countColor=%23555555\&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
