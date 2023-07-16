# ⛏ Python tools

## **AutoViz**

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

🔗 [GitHub](https://github.com/man-group/dtale) | [Website](https://pypi.org/project/dtale/)

D-Tale is the combination of a Flask back-end and a React front-end to bring you an easy way to view & analyze Pandas data structures. It integrates seamlessly with ipython notebooks & python/ipython terminals. Currently this tool supports such Pandas objects as DataFrame, Series, MultiIndex, DatetimeIndex & RangeIndex.

## **DataPrep**

🔗 [GitHub](https://github.com/sfu-db/dataprep) | [Website](https://docs.dataprep.ai/)

DataPrep lets you prepare your data using a single library with a few lines of code. Currently, you can use DataPrep to:
- Collect data from common data sources through `dataprep.connector`
- Do your exploratory data analysis through `dataprep.eda`
- Clean and standardize data through `dataprep.clean`

`DataPrep.EDA` is the fastest and the easiest EDA (Exploratory Data Analysis) tool in Python. It allows you to understand a Pandas/Dask DataFrame with a few lines of code in seconds.

#### Create Profile Reports, Fast

You can create a beautiful profile report from a Pandas/Dask DataFrame with the `create_report` function. DataPrep.EDA has the following advantages compared to other tools:

- **[10X Faster](https://arxiv.org/abs/2104.00841)**: DataPrep.EDA can be 10X faster than Pandas-based profiling tools due to its highly optimized Dask-based computing module.
- **Interactive Visualization**: DataPrep.EDA generates interactive visualizations in a report, which makes the report look more appealing to end users.
- **Big Data Support**: DataPrep.EDA naturally supports big data stored in a Dask cluster by accepting a Dask dataframe as input.


## **ExploriPy**

🔗 [GitHub](https://github.com/ExploriPy/ExploriPy) | [Website](https://pypi.org/project/ExploriPy/)

Exploratory Data Analysis (EDA) is one of the crucial steps in data science that facilitates generating insights and statistical measures which are essential for building predictive models. EDA is always a time-consuming activity and require a thorough analysis of datasets to summarize their main characteristics. It is always required to do an initial analysis on the data, and then deep dive on further domain specific analysis, based on the initial insights. Currently, there is no comprehensive library in Python, which could do the initial Data Analysis and statistical tests, and present in an output, which could be easily interpreted shared across the stakeholders. Though there are several individual packages available for statistical tests, interpretation of the output requires certain level of statistical knowledge.

**ExploriPy** reduces a data analyst’s efforts significantly in the initial EDA. It is designed in a way to perform automated EDA, and statistical tests including **Analysis of Variance**, **Chi Square Test of Independence**, **Weight of Evidence**, **Information Value** and **Tukey Honest Significance Difference**. It provides easy interpretation on these statistical test results, based on industry standard assumptions. It expects a **Pandas DataFrame**, along with a list of **categorical variables**, as input. Output will be a presentable **HTML document**, with the result of analysis and statistical tests, represented through several interactive charts, and tables (with option to download as CSV). The ExploriPy package is available in the **Python Package Index**.


## **Lux**

🔗 [GitHub](https://github.com/) | [Website](https:/)

Provides an interactive and visual approach to EDA. Offers recommendations for visualizations based on the data and allows users to explore the dataset through an intuitive interface.

## **Pandas Profiling**

🔗 [GitHub](https://github.com/) | [Website](https:/)

Generates a detailed report with statistics, visualizations, and insights about the dataset. Provides information about missing values, data types, correlations, and distribution of variables.

## **QuickDA**

🔗 [GitHub](https://github.com/) | [Website](https:/)

Offers automated data cleaning, preprocessing, visualization, and statistical analysis. Supports interactive exploration and provides insights into the dataset quickly.

## **dabl**

🔗 [GitHub](https://github.com/) | [Website](https:/)

Simplifies the process of data analysis by automating common tasks such as data cleaning, feature selection, and model evaluation. Offers visualizations and model explanations.

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan\&labelColor=%23697689\&countColor=%23555555\&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
