# ⛏ Python tools

Automated Exploratory Data Analysis (EDA) tools are software or frameworks that facilitate the process of analyzing and understanding a dataset automatically, without requiring manual effort or extensive coding. These tools leverage various statistical and visualization techniques to provide insights into the data, detect patterns, and identify potential issues or anomalies.

## **AutoViz**

{% tabs %}
{% tab title="🔗 Website" %}
{% embed url="https://pypi.org/project/autoviz/0.0.6/" %}
{% endtab %}
{% tab title="🧰 Github" %}
{% embed url="https://github.com/AutoViML/AutoViz" %}
{% endtab %}
{% endtabs %}

🔗 [GitHub](https://github.com/AutoViML/AutoViz) | [Website](https://pypi.org/project/autoviz/0.0.6/)

Automatically visualizes the dataset using a single line of code. Generates a wide range of charts and graphs to explore the data, such as scatter plots, bar plots, and histograms.

AutoViz addresses these challenges by providing an easy-to-use, automated solution for generating meaningful visualizations with minimal effort. Its key motivations are:

1. **Save time and effort**: AutoViz simplifies the visualization process by requiring just a single line of code to generate multiple insightful plots, eliminating the need to write multiple lines of code for each chart.
2. **Handle large datasets**: AutoViz is designed to work with datasets of any size, intelligently sampling the data when necessary to ensure that the visualizations are generated quickly and efficiently, without compromising on the insights.
3. **Democratize Data Science**: AutoViz makes data visualization accessible to a broader audience, including non-experts and beginners in data analysis, by abstracting away the complexities of various plotting libraries.
4. **Automate EDA**: AutoViz now automatically analyzes and fixes Data Quality issues in your dataset. This will help users to quickly go from insights to action without having to manually analyze each variable. AutoViz uses the new `pandas-dq` library created by `autoviml` to perform data quality and cleaning.
5. **Customization and interactivity**: AutoViz offers various options for customization, enabling users to tailor the generated visualizations to their specific needs and preferences. Moreover, with interactive chart formats like Bokeh, users can explore the data more dynamically.

In summary, the motivation behind AutoViz is to make data visualization more efficient, accessible, and automated, enabling users to quickly gain valuable insights from their data and focus on making data-driven decisions.

## **D-Tale**

{% tabs %}
{% tab title="🔗 Website" %}
{% embed url="https://pypi.org/project/dtale" %}
{% endtab %}
{% tab title="🧰 Github" %}
{% embed url="https://github.com/man-group/dtale" %}
{% endtab %}
{% endtabs %}
🔗 [GitHub](https://github.com/man-group/dtale) | [Website](https://pypi.org/project/dtale/)

D-Tale is the combination of a Flask back-end and a React front-end to bring you an easy way to view & analyze Pandas data structures. It integrates seamlessly with ipython notebooks & python/ipython terminals. Currently this tool supports such Pandas objects as DataFrame, Series, MultiIndex, DatetimeIndex & RangeIndex.

D-Tale was the product of a SAS to Python conversion. What was originally a perl script wrapper on top of SAS's `insight` function is now a lightweight web client on top of Pandas data structures.

## **DataPrep**

{% tabs %}
{% tab title="🔗 Website" %}
{% embed url="https://docs.dataprep.ai" %}
{% endtab %}
{% tab title="🧰 Github" %}
{% embed url="https://github.com/sfu-db/dataprep" %}
{% endtab %}
{% endtabs %}
🔗 [GitHub](https://github.com/sfu-db/dataprep) | [Website](https://docs.dataprep.ai/)

DataPrep lets you prepare your data using a single library with a few lines of code. Currently, you can use DataPrep to:

* Collect data from common data sources through `dataprep.connector`
* Do your exploratory data analysis through `dataprep.eda`
* Clean and standardize data through `dataprep.clean`

`DataPrep.EDA` is the fastest and the easiest EDA (Exploratory Data Analysis) tool in Python. It allows you to understand a Pandas/Dask DataFrame with a few lines of code in seconds.

#### Create Profile Reports, Fast

You can create a beautiful profile report from a Pandas/Dask DataFrame with the `create_report` function. DataPrep.EDA has the following advantages compared to other tools:

* [**10X Faster**](https://arxiv.org/abs/2104.00841): DataPrep.EDA can be 10X faster than Pandas-based profiling tools due to its highly optimized Dask-based computing module.
* **Interactive Visualization**: DataPrep.EDA generates interactive visualizations in a report, which makes the report look more appealing to end users.
* **Big Data Support**: DataPrep.EDA naturally supports big data stored in a Dask cluster by accepting a Dask dataframe as input.

## **ExploriPy**

{% tabs %}
{% tab title="🔗 Website" %}
{% embed url="https://pypi.org/project/ExploriPy" %}
{% endtab %}
{% tab title="🧰 Github" %}
{% embed url="https://github.com/ExploriPy/ExploriPy" %}
{% endtab %}
{% endtabs %}
🔗 [GitHub](https://github.com/ExploriPy/ExploriPy) | [Website](https://pypi.org/project/ExploriPy/)

Exploratory Data Analysis (EDA) is one of the crucial steps in data science that facilitates generating insights and statistical measures which are essential for building predictive models. EDA is always a time-consuming activity and require a thorough analysis of datasets to summarize their main characteristics. It is always required to do an initial analysis on the data, and then deep dive on further domain specific analysis, based on the initial insights. Currently, there is no comprehensive library in Python, which could do the initial Data Analysis and statistical tests, and present in an output, which could be easily interpreted shared across the stakeholders. Though there are several individual packages available for statistical tests, interpretation of the output requires certain level of statistical knowledge.

**ExploriPy** reduces a data analyst’s efforts significantly in the initial EDA. It is designed in a way to perform automated EDA, and statistical tests including **Analysis of Variance**, **Chi Square Test of Independence**, **Weight of Evidence**, **Information Value** and **Tukey Honest Significance Difference**. It provides easy interpretation on these statistical test results, based on industry standard assumptions. It expects a **Pandas DataFrame**, along with a list of **categorical variables**, as input. Output will be a presentable **HTML document**, with the result of analysis and statistical tests, represented through several interactive charts, and tables (with option to download as CSV). The ExploriPy package is available in the **Python Package Index**.

## **Lux**

{% tabs %}
{% tab title="🔗 Website" %}
{% embed url="https://lux-api.readthedocs.io/en/latest/" %}
{% endtab %}
{% tab title="🧰 Github" %}
{% embed url="https://github.com/lux-org/lux/tree/master" %}
{% endtab %}
{% endtabs %}
🔗 [GitHub](https://github.com/lux-org/lux/tree/master) | [Website](https://lux-api.readthedocs.io/en/latest/)

Lux is a Python library that facilitate fast and easy data exploration by automating the visualization and data analysis process. By simply printing out a dataframe in a Jupyter notebook, Lux recommends a set of visualizations highlighting interesting trends and patterns in the dataset. Visualizations are displayed via [an interactive widget](https://github.com/lux-org/lux-widget) that enables users to quickly browse through large collections of visualizations and make sense of their data.

## **QuickDA**

{% tabs %}
{% tab title="🔗 Website" %}
{% embed url="https://pypi.org/project/quickda" %}
{% endtab %}
{% tab title="🧰 Github" %}
{% embed url="https://github.com/sid-the-coder/QuickDA/tree/master" %}
{% endtab %}
{% endtabs %}
🔗 [GitHub](https://github.com/sid-the-coder/QuickDA/tree/master) | [Website](https://pypi.org/project/quickda/)

Simple & Easy-to-use python modules to perform Quick Exploratory Data Analysis for any structured dataset!. Enter [QuickDA](https://pypi.org/project/quickda/), a simple, low-code & easy-to-use EDA library in Python to help you quickly explore, clean and visualise data with just few lines of customisable codes! One thing to remember is that QuickDA is supposed to be a starting point for quick exploratory analysis, and in no way a replacement to traditional EDA approaches.

## **dabl**

{% tabs %}
{% tab title="🔗 Website" %}
{% embed url="https://dabl.github.io/dev" %}
{% endtab %}
{% tab title="🧰 Github" %}
{% embed url="https://github.com/dabl/dabl" %}
{% endtab %}
{% endtabs %}
🔗 [GitHub](https://github.com/dabl/dabl) | [Website](https://dabl.github.io/dev/)

This project tries to help make supervised machine learning more accessible for beginners, and reduce boiler plate for common tasks. Current code focuses mostly on exploratory visualization and preprocessing. There are also drop-in replacements for GridSearchCV and RandomizedSearchCV using successive halfing. There are preliminary portfolios in the style of POSH auto-sklearn to find strong models quickly. In essence that boils down to a quick search over different gradient boosting models and other tree ensembles and potentially kernel methods. This library is in very active development, so it’s not recommended for production use.

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan\&labelColor=%23697689\&countColor=%23555555\&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
