# EDA: A Comprehensive Examination

In the field of data analysis, the following aspects are investigated to derive meaningful insights:

## **Dataset's Shape and Overview:**&#x20;

The initial step involves examining the **shape** of the dataset, encompassing the number of **rows** and **columns**. This provides a comprehensive **overview** of the dataset's structure and composition.

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*Ww5zm7vOtW_YahtL_nJlXw.png" alt="" height="146" width="700"><figcaption></figcaption></figure>

## **Missing Values**

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

## **Numerical Variables**

In-depth exploration of **numerical variables** is conducted. This entails analyzing statistical characteristics such as **mean**, **median**, and **standard deviation** to gain insights into central tendency, dispersion, and variability of these variables.

## **Distribution of Numerical Variables**

Understanding the distribution of **numerical variables** is essential for accurate data interpretation. Visualizations and statistical techniques are employed to examine the **shape**, **skewness**, and **kurtosis** of these variables.

## **Outliers**

The identification and examination of **outliers**, which are observations that significantly deviate from the majority, are essential. This analysis aids in assessing the impact of outliers on the dataset. Based on the dataset's nature, appropriate actions such as exclusion, transformation, or handling of outliers can be determined.

## **Categorical Variables**

The analysis encompasses an exploration of **categorical variables** within the dataset. This involves examining the different **categories** and their respective **frequencies** to gain insights into the composition and distribution of these variables.

## **Cardinality of Categorical Variables**

Evaluating the **cardinality**, i.e., the number of unique values, within categorical variables is crucial. Assessing the level of diversity within each variable helps guide decision-making regarding variable transformation or feature engineering, if required.

## **Relationship Between Independent and Dependent Features**

The relationship between **independent features** and the **dependent feature** of interest is scrutinized. This involves **plotting** and analyzing the distributions of independent features in relation to the dependent feature. This analysis aids in uncovering potential **patterns**, **correlations**, or **dependencies** present in the data.

By thoroughly examining these aspects, valuable insights can be gleaned, leading to informed decision-making throughout the data analysis process.
