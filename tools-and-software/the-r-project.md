---
description: for Statistical Computing
---

# The R Project

R is an **open source** programming language that’s optimized for **statistical analysis** and **data visualization**. Developed in 1992, R has a rich ecosystem with complex data models and elegant tools for **data reporting**. At last count, more than **13,000 R packages** were available via the **Comprehensive R Archive Network (CRAN)** for **deep analytics**.

Popular among **data science scholars** and **researchers**, R provides a broad variety of libraries and tools for the following:

* **Cleansing** and **prepping data**
* **Creating visualizations**
* **Training** and **evaluating machine learning** and **deep learning algorithms**

R is commonly used within **RStudio**, an **integrated development environment (IDE)** for simplified statistical analysis, visualization, and reporting. R applications can be used directly and interactively on the web via **Shiny**. R beginners can also use these libraries as they are easy to use and can help them quickly understand the dataset with a few code lines.

Automated Exploratory Data Analysis packages that will be described consist of DataExplorer, GGally, SmartEDA, tableone and dataMaid.

## DataExplorer

{% tabs %}
{% tab title="🔗 Website" %}
{% embed url="https://cran.r-project.org/web/packages/DataExplorer" %}
{% endtab %}
{% tab title="🧰 Github" %}
{% embed url="https://github.com/boxuancui/DataExplorer" %}
{% endtab %}
{% endtabs %}

Automated data exploration process for analytic tasks and predictive modeling, so that users could focus on understanding data and extracting insights. The package scans and analyzes each variable, and visualizes them with typical graphical techniques. Common data processing methods are also available to treat and format data. This library automatically scans the dataset for variables, performs data profiling, and provides many useful functions to create various charts on both discrete and continuous features in the dataset.

Let us look at the code we need to install and use the DataExplorer library

```
# Installing the package
install.packages("DataExplorer")

# Importing the library
library(DataExplorer)
create_report(mtcars)
data()
```

The DataExplorer library generates a complete HTML report in the working directory for the EDA on the dataset using the create\_report function. This function also accepts additional arguments to customize the EDA report. The report HTML file, when opened with a browser, looks like the following:

<figure><img src="https://editor.analyticsvidhya.com/uploads/53359dataexplorer.gif" alt="" width="563"><figcaption></figcaption></figure>

From the above .gif image of the report, we can see that the table of contents indicates a comprehensive report covering most of the tasks performed during EDA generated with just one line of code. Here are some sample plots from the report at a glance-

![R Libraries](https://lh3.googleusercontent.com/jDT8wl6irqpGnrXsxbn6\_mvcU37prCQjm5HuOVD77KwItBRSuFftehdOMp6rc7Zz5XGvc6Zyg5IHoCdDQV6x04ZKTM-ZTp5zo0LGSVo6YA4qWnSqLDOdueG6puOZAe7nccLkFXzJFDnQ6QUUnTb0BhvQo1G4NZHaw8hMHBi5Uo5FxM-YyHyMH9VqJw)

You can also refer to the [package documentation](https://cran.r-project.org/package=DataExplorer) on the CRAN-R website for additional details

## GGally

{% tabs %}
{% tab title="🔗 Website" %}
{% embed url="https://cran.r-project.org/web/packages/GGally/index.html" %}
{% endtab %}
{% tab title="🧰 Github" %}
{% embed url="https://github.com/ggobi/ggally/tree/master" %}
{% endtab %}
{% endtabs %}

[`ggplot2`](https://ggplot2.tidyverse.org/) is a plotting system for R based on the grammar of graphics. [`GGally`](https://ggobi.github.io/ggally/) extends ggplot2 by adding several functions to reduce the complexity of combining geoms with transformed data. Some of these functions include a pairwise plot matrix, a scatterplot plot matrix, a parallel coordinates plot, a survival plot, and several functions to plot networks. When using the ggplot() function to create charts, the 'geom()' object must be used to determine the plot type. In the case of the gGally package, however, it includes pre-built features such as:

* `ggally_density()` – To plot Density Plot.
* `ggally_points()` – To plot the ScatterPlot, etc.

which reduces the complexity of plotting graphs with the geoms like in `ggplot2`. So, let’s dive into some graphs which can be plotted using GGally in R Programming Language.

### Installation

To install this package from GitHub or [CRAN](https://cran.r-project.org/package=GGally), do the following from the R console:

```r
# Github
library(devtools)
install_github("ggobi/ggally")
```

```r
# CRAN
install.packages("GGally")
```

## SmartEDA

{% tabs %}
{% tab title="🔗 Website" %}
{% embed url="https://cran.r-project.org/web/packages/SmartEDA" %}
{% endtab %}
{% tab title="🧰 Github" %}
{% embed url="https://github.com/daya6489/SmartEDA" %}
{% endtab %}
{% endtabs %}

SmartEDA is a comprehensive programme for automating most EDA activities including descriptive statistics, data visualisation, custom tables, and HTML reports.

Using the ExpReport method in the SmartEDA package, we can also generate a full HTML report. As indicated below, we will install and import the package, as well as run the ExpReport function to perform the EDA.

```
# Install package
install.packages("SmartEDA")
# Import library
library(SmartEDA)
ExpReport(df,op_file='smartEDA.html')
```

This ExpReport function accepts several arguments to customize the report for Template, op\_file,op\_dir, label, theme, etc.

Here, we will use the ‘op\_file’ function to name the report.html file. This report file is available with the specified name in the working directory and can be opened with a browser. The snippet of the .html report shown below provides information on how well the SmartEDA package has summarized the ‘mtcars’ dataset.

<figure><img src="https://editor.analyticsvidhya.com/uploads/50666smartEDA.gif" alt="R Libraries" width="563"><figcaption></figcaption></figure>

Here are a few sample plots from the report:

![R Libraries](https://lh5.googleusercontent.com/2TB\_S2Xbhgxn0dcB2rJaIoqGUpAEkxp\_G7MMNOTdQHZvprCikcj8-MR9HKdWrvV9tOnFPCiC1QCxqDCTgD93J2JxlG3AtWzioGH2S\_T4AwJhm-iF8ttGA1jGr8IWiont584puD6lVBoLP3zmyaJCXqeVtqbft80gSCuDYo7zffZwctg-UxtDK8Ln\_g)

From the .html report, we can see that it contains several plots generated with just one line of code and these plots are useful in understanding the dataset better. The documentation for SmartEDA can be found [here](https://cran.r-project.org/web/packages/SmartEDA/index.html).

## tableone

{% tabs %}
{% tab title="🔗 Website" %}
{% embed url="https://cran.r-project.org/web/packages/tableone/" %}
{% endtab %}
{% tab title="🧰 Github" %}
{% embed url="https://github.com/kaz-yos/tableone" %}
{% endtab %}
{% endtabs %}

An R package to create “Table 1”, description of baseline characteristics

Table 1 is a common format to show summary statistics of data that is used in medical research papers. You can use a various data wrangling mehods such as Group By, Summarize, etc. to calculate such statistics. But, in R, there is a package called ‘tableone’, which is designed to generate the Table 1 information. This means, you can quickly use the package to generate Table 1 information in Exploratory.

There are two ways to use this package.

1. Use Note, which is built on RMarkdown and allows you to construct R scripts directly using the ‘tableone‘ package and output the results. This is a simple and quick solution if you are ok with the output in Note.
2. Another is to create a custom R function with the ‘tableone’ package and call it as a data wrangling step. This would take a bit of steps, but since you will get the result in a data frame format you will be able to use the data in a more flexible way.

tableone was inspired by descriptive statistics functions in Deducer , a Java-based GUI package by Ian Fellows. This package does not require GUI or Java, and intended for command-line users.

## dataMaid

{% tabs %}
{% tab title="🔗 Website" %}
{% embed url="https://cran.r-project.org/web/packages/dataMaid/index.html" %}
{% endtab %}
{% tab title="🧰 Github" %}
{% embed url="https://github.com/ekstroem/dataMaid" %}
{% endtab %}
{% endtabs %}

The dataMaid package creates a report in different formats, such as PDF, DOCX, or HTML. The generated report checks and neatly simply summarizes the dataset. It is a good tool for checking errors in the dataset.

To utilize the dataMaid package, one can execute the given command to install, import, and run it.

```
# Install package
install.packages("dataMaid")
# Import library
library(dataMaid)
# Create report
makeDataReport(df, output = "html", replace = TRUE)
```

<figure><img src="https://editor.analyticsvidhya.com/uploads/85664datamaid.gif" alt="" width="563"><figcaption></figcaption></figure>

From the above .gif for the .html report generated by the dataMaid package, we can see that all the discrepancies in the dataset are summarized variable by variable in the generated report. Thus, it is easier to understand the data quality and decide on the next steps required for data cleaning.

The [dataMaid package documentation](https://cran.r-project.org/web/packages/dataMaid/index.html) can be explored for additional details.

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan\&labelColor=%23697689\&countColor=%23555555\&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
