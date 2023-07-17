---
description: Essential Analysis Considerations in Data Analysis
---

# A Comprehensive Examination

Data analysis plays a vital role in extracting valuable insights from datasets. To ensure a thorough and accurate analysis, it is essential to consider various aspects. This article provides a comprehensive examination of the essential analysis considerations in data analysis. By understanding and addressing these key factors, analysts can derive meaningful and reliable insights from their data.

In the field of data analysis, the following aspects are investigated to derive meaningful insights:

## **1. Dataset's Shape and Overview**

The initial step involves examining the **shape** of the dataset, encompassing the number of **rows** and **columns**. This provides a comprehensive **overview** of the dataset's structure and composition.

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*Ww5zm7vOtW_YahtL_nJlXw.png" alt="" width="563"><figcaption></figcaption></figure>

## **2. Missing Values**

Identifying and addressing missing values is critical to ensuring data quality. The analysis entails determining the presence and extent of **missing values** within the dataset. This step aids in making informed decisions regarding the appropriate treatment of missing data.

Here we will check the percentage of NaN values present in each feature:\
1\) make the list of features which has missing values\
2\) print the feature name and the percentage of missing values

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*7hwVf0ih9vT_HBN_hH6cbw.png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*RyitaXsi1a0aNMgVNiaKuw.png" alt="" width="563"><figcaption></figcaption></figure>

We can use heatmap and visualize missing values.

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*bapx7HhSHv2Ie-NJAxXtfQ.png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*WJl_dcj5EE3x9HZ-O8AwiQ.png" alt="" width="563"><figcaption></figcaption></figure>

We need to find the relationship between missing values and the target feature. Let’s plot some diagram for this relationship.

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*AUBSqrjcgNMmmjN7vkALsw.png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*ZPOexSZ5OXjByujUumtCbw.png" alt="" width="563"><figcaption></figcaption></figure>

Here, the relation between the missing values and the dependent variable is clearly visible. So we need to replace these NaN values with something meaningful which we will do in Feature Engineering. From the above dataset some of the features might not be required, which we will drop.

## **3. Numerical Variables**

In-depth exploration of **numerical variables** is conducted. This entails analyzing statistical characteristics such as **mean**, **median**, and **standard deviation** to gain insights into central tendency, dispersion, and variability of these variables.

Get the list of Numerical variables and visualize columns.

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*pSsv3ico1sE8R0mHKebx1w.png" alt="" width="563"><figcaption></figcaption></figure>

**Temporal Variables(Eg: Datetime Variables):** From a Dataset, we may have year variables. We can extract information from the datetime variables like number of years or number of days.

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*whUvRt2fJ7h2qdKobIb53Q.png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*PGYjaEuwUfKhzaxF8EcloA.png" alt="" width="563"><figcaption></figcaption></figure>

## **4. Distribution of Numerical Variables**

Understanding the distribution of **numerical variables** is essential for accurate data interpretation. Visualizations and statistical techniques are employed to examine the **shape**, **skewness**, and **kurtosis** of these variables.

Numerical variables are usually of 2 types: Discrete Variable and Continuous variable.

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*5fLFudMfa4qLdcLbhOPl7g.png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*gLHXSxj8hRnxL6WvonfZ4Q.png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*11Dph-QAK3xowDGI75xuBQ.png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*6XElpqL1LAO5wD5O8Xm3Rg.png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*CT_bX7g0TqgLC37iVG8Vkg.png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*2YnYo-iiIYVEH13igHr0oQ.png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*gK1yszew6uBY98RJS3ig5g.png" alt="" width="563"><figcaption></figcaption></figure>

## **5. Outliers**

The identification and examination of **outliers**, which are observations that significantly deviate from the majority, are essential. This analysis aids in assessing the impact of outliers on the dataset. Based on the dataset's nature, appropriate actions such as exclusion, transformation, or handling of outliers can be determined.

Let’s find outliers in continuous variables using Boxplot.

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*JGCVN7BK0Kc8LSKdNOZl9A.png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*V6LE4tnF8qCtG1moXdVl6Q.png" alt="" width="563"><figcaption></figcaption></figure>

## **6. Categorical Variables**

The analysis encompasses an exploration of **categorical variables** within the dataset. This involves examining the different **categories** and their respective **frequencies** to gain insights into the composition and distribution of these variables.

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*KvsEQSXqjjXDplM8fxpmVw.png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*jhE6lg9PXmIa8Hqfi5DhzQ.png" alt="" width="563"><figcaption></figcaption></figure>

Let’s find out the relationship between categorical variable and dependent feature.

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*m_T-uns-thB4y_9RYQfdTQ.png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*vRqYUKUQ2qQvCkIHKSExyw.png" alt="" width="563"><figcaption></figcaption></figure>

## **7. Cardinality of Categorical Variables**

Evaluating the **cardinality**, i.e., the number of unique values, within categorical variables is crucial. Assessing the level of diversity within each variable helps guide decision-making regarding variable transformation or feature engineering, if required.

## **8. Relationship Between Independent & Dependent Features**

The relationship between **independent features** and the **dependent feature** of interest is scrutinized. This involves **plotting** and analyzing the distributions of independent features in relation to the dependent feature. This analysis aids in uncovering potential **patterns**, **correlations**, or **dependencies** present in the data.

By thoroughly examining these aspects, valuable insights can be gleaned, leading to informed decision-making throughout the data analysis process.

## Conclusion

A comprehensive examination of essential analysis considerations enhances the quality and reliability of data analysis. By focusing on the dataset's shape, missing values, numerical and categorical variables, distributions, outliers, and the relationship between features, analysts can derive meaningful insights and make informed decisions. Considering these factors ensures robust analysis and enables data-driven decision-making.
