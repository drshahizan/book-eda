---
description: A library for data manipulation and analysis
---

# 🐼 Pandas

🔗 [GitHub](https://github.com/pandas-dev/pandas) | [Website](https://pandas.pydata.org/)

**pandas** is a Python package that provides fast, flexible, and expressive data structures designed to make working with "relational" or "labeled" data both easy and intuitive. It aims to be the fundamental high-level building block for doing practical, **real world** data analysis in Python. Additionally, it has the broader goal of becoming **the most powerful and flexible open source data analysis / manipulation tool available in any language**. It is already well on its way towards this goal.

## Pandas and **Exploratory Data Analysis (EDA)**

Pandas is a powerful Python library commonly used in **Exploratory Data Analysis (EDA)**. It provides data structures and functions to efficiently manipulate and analyze structured data, making it a fundamental tool for data analysis tasks.

Key features of pandas in the context of EDA:

1. **Data Structures**: Pandas introduces two primary data structures, namely **Series** and **DataFrame**. A Series is a one-dimensional array-like object that can hold any data type, while a DataFrame is a two-dimensional table with labeled columns and rows, similar to a spreadsheet or a SQL table. These data structures allow for efficient storage and manipulation of data during EDA.
2. **Data Loading**: Pandas provides functions to read data from various file formats, including **CSV**, **Excel**, **SQL databases**, and more. The **`read_csv()`**, **`read_excel()`**, and **`read_sql()`** functions are commonly used to import data into pandas DataFrames.
3. **Data Cleaning**: EDA often involves cleaning and preprocessing the data. Pandas offers a wide range of functions to handle missing data, duplicate values, data type conversions, and other data cleaning tasks. Functions like **`dropna()`**, **`fillna()`**, **`drop_duplicates()`**, and **`astype()`** are commonly used for data cleaning.
4. **Data Exploration**: Pandas provides numerous functions for exploring and summarizing data. You can perform operations like sorting, filtering, grouping, and aggregating data using functions like **`sort_values()`**, **`query()`**, **`groupby()`**, and **`agg()`**. These operations allow you to gain insights into the structure and characteristics of your data.
5. **Descriptive Statistics**: Pandas offers a wide range of statistical functions to compute descriptive statistics of your data. You can calculate measures such as mean, median, standard deviation, quantiles, correlation, and more using functions like **`mean()`**, **`median()`**, **`std()`**, **`quantile()`**, and **`corr()`**. These statistics help in understanding the distribution and relationships within the dataset.
6. **Data Visualization**: While pandas itself does not provide visualization capabilities, it seamlessly integrates with other libraries like **Matplotlib** and **Seaborn**. You can directly plot visualizations from pandas DataFrames using functions like **`plot()`**, **`plot.bar()`**, **`plot.hist()`**, and more. This integration allows you to generate insightful plots and charts as part of your EDA process.

Overall, pandas simplifies and accelerates the data manipulation and analysis tasks involved in EDA. Its intuitive data structures and extensive functions enable data scientists and analysts to efficiently explore and understand their datasets, making it an essential tool in the EDA workflow.

## Main Features

Here are just a few of the things that pandas does well:

* Easy handling of [**missing data**](https://pandas.pydata.org/pandas-docs/stable/user\_guide/missing\_data.html) (represented as `NaN`, `NA`, or `NaT`) in floating point as well as non-floating point data
* Size mutability: columns can be [**inserted and deleted**](https://pandas.pydata.org/pandas-docs/stable/user\_guide/dsintro.html#column-selection-addition-deletion) from DataFrame and higher dimensional objects
* Automatic and explicit [**data alignment**](https://pandas.pydata.org/pandas-docs/stable/user\_guide/dsintro.html?highlight=alignment#intro-to-data-structures): objects can be explicitly aligned to a set of labels, or the user can simply ignore the labels and let `Series`, `DataFrame`, etc. automatically align the data for you in computations
* Powerful, flexible [**group by**](https://pandas.pydata.org/pandas-docs/stable/user\_guide/groupby.html#group-by-split-apply-combine) functionality to perform split-apply-combine operations on data sets, for both aggregating and transforming data
* Make it [**easy to convert**](https://pandas.pydata.org/pandas-docs/stable/user\_guide/dsintro.html#dataframe) ragged, differently-indexed data in other Python and NumPy data structures into DataFrame objects
* Intelligent label-based [**slicing**](https://pandas.pydata.org/pandas-docs/stable/user\_guide/indexing.html#slicing-ranges), [**fancy indexing**](https://pandas.pydata.org/pandas-docs/stable/user\_guide/advanced.html#advanced), and [**subsetting**](https://pandas.pydata.org/pandas-docs/stable/user\_guide/indexing.html#boolean-indexing) of large data sets
* Intuitive [**merging**](https://pandas.pydata.org/pandas-docs/stable/user\_guide/merging.html#database-style-dataframe-or-named-series-joining-merging) and [**joining**](https://pandas.pydata.org/pandas-docs/stable/user\_guide/merging.html#joining-on-index) data sets
* Flexible [**reshaping**](https://pandas.pydata.org/pandas-docs/stable/user\_guide/reshaping.html) and [**pivoting**](https://pandas.pydata.org/pandas-docs/stable/user\_guide/reshaping.html) of data sets
* [**Hierarchical**](https://pandas.pydata.org/pandas-docs/stable/user\_guide/indexing.html#hierarchical-indexing-multiindex) labeling of axes (possible to have multiple labels per tick)
* Robust IO tools for loading data from [**flat files**](https://pandas.pydata.org/pandas-docs/stable/user\_guide/io.html#csv-text-files) (CSV and delimited), [**Excel files**](https://pandas.pydata.org/pandas-docs/stable/user\_guide/io.html#excel-files), [**databases**](https://pandas.pydata.org/pandas-docs/stable/user\_guide/io.html#sql-queries), and saving/loading data from the ultrafast [**HDF5 format**](https://pandas.pydata.org/pandas-docs/stable/user\_guide/io.html#hdf5-pytables)
* [**Time series**](https://pandas.pydata.org/pandas-docs/stable/user\_guide/timeseries.html#time-series-date-functionality)-specific functionality: date range generation and frequency conversion, moving window statistics, date shifting and lagging

## Where to get it

The source code is currently hosted on GitHub at: https://github.com/pandas-dev/pandas

Binary installers for the latest released version are available at the [Python Package Index (PyPI)](https://pypi.org/project/pandas) and on [Conda](https://docs.conda.io/en/latest/).

```sh
# conda
conda install -c conda-forge pandas
```

```sh
# or PyPI
pip install pandas
```

The list of changes to pandas between each release can be found [here](https://pandas.pydata.org/pandas-docs/stable/whatsnew/index.html). For full details, see the commit logs at https://github.com/pandas-dev/pandas.

## Dependencies

* [NumPy - Adds support for large, multi-dimensional arrays, matrices and high-level mathematical functions to operate on these arrays](https://www.numpy.org)
* [python-dateutil - Provides powerful extensions to the standard datetime module](https://dateutil.readthedocs.io/en/stable/index.html)
* [pytz - Brings the Olson tz database into Python which allows accurate and cross platform timezone calculations](https://github.com/stub42/pytz)

See the [full installation instructions](https://pandas.pydata.org/pandas-docs/stable/install.html#dependencies) for minimum supported versions of required, recommended and optional dependencies.

## Installation from sources

To install pandas from source you need [Cython](https://cython.org/) in addition to the normal dependencies above. Cython can be installed from PyPI:

```sh
pip install cython
```

In the `pandas` directory (same one where you found this file after cloning the git repo), execute:

```sh
python setup.py install
```

or for installing in [development mode](https://pip.pypa.io/en/latest/cli/pip\_install/#install-editable):

```sh
python -m pip install -e . --no-build-isolation --no-use-pep517
```

or alternatively

```sh
python setup.py develop
```

See the full instructions for [installing from source](https://pandas.pydata.org/pandas-docs/stable/getting\_started/install.html#installing-from-source).

## Documentation

The official documentation is hosted on [PyData.org](https://pandas.pydata.org/pandas-docs/stable/).

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan\&labelColor=%23697689\&countColor=%23555555\&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
