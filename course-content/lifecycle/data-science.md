# Data Science

## What is Data Science?

As the name implies, data science is the area of study that investigates enormous volumes of information using modern tools and techniques to find unseen patterns, derive meaningful information, and make business decisions based on that information. Predictive models are built using complex machine learning algorithms in data science. The data used for analysis can come from many different sources and be presented in various formats.

## What is a Data Science Life Cycle?

The Data Science Lifecycle is an extensive step-by-step guide that illustrates how machine learning and other analytical techniques can be used to generate insights and predictions from data to accomplish a business objective.

Several processes are taken during the entire process, including data preparation, cleaning, modeling, and model evaluation. The process is lengthy and could take several months to finish.

## Data Science Life Cycle

The life cycle of data science contains the following steps:

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/1*DjIccrMeRWmrC_mCUOGDhw.png" alt="" height="394" width="700"><figcaption><p>Data Science life cycle (Sivaraj, 2020)</p></figcaption></figure>

### Understanding the Business problem

The "why" question served as the catalyst for many world advances.

Every good business or IT-focused life cycle begins with "why," and the same is true for good data science life cycles. The business objective must be clearly understood because it will be the analysis's end result.

A crucial aspect of the early stages of data analytics is to look at business trends, develop case studies of related data analytics in other businesses, and conduct market research on the business's industry. These duties are regularly undertaken by stakeholders at this early stage of data analytics. All members of the team evaluate the internal infrastructure, internal resources, the total amount of time required to complete the project, and the technological requirements for the project. Once all of these analyses and evaluations have been completed, the stakeholders begin developing the primary hypothesis on how to resolve all business difficulties based on the current market condition after all of the preliminary analyses and evaluations have been completed.

In short, to define the business problem for the data science project following are the essential points to remember.

* List the issue that needs to be resolved.&#x20;
* Define the project's potential value.
* Determine the project's risks, taking ethical issues into account.&#x20;
* Create and distribute a flexible, high-level project plan.

### Preparing the data

The second phase of the data science life cycle is data preparation. This is to prepare the data to understand the business problem and extract information to solve the problem.

![](https://lh3.googleusercontent.com/gBWILLY8CDCbdhS\_-2ynnukjiH4-fi6IkYtyu-hYjCR9F5gspI-HhXYj\_aGrwH1AQWSCQL0hnkFC4v3Ck1sNDhWbE61cQdTSBJ\_iU0jeUFvkXIxVi-zrAoJ5rCmIBTK4XBwa4EkBOfiQl6Ofwl5HL9aAMr9SXsIH3S3CmjajPQhm4E9h\_GUScwxJrg)

* Selecting data related to the problem.
* Combining the data sets, you may integrate the data.&#x20;
* Clean the data to find the missing values.
* Handle the missing values by removing or imputing them.&#x20;
* Errors are dealt with by being removed.
* Use the box plots for detecting outliers and handling them.

### Exploratory Data Analysis (EDA)

Before really developing the model, this step entails understanding the solution and the variables that may affect it. To understand data and data features better, we create heat maps, bar graphs, and charting.

We need to keep a few factors in mind when analyzing the data, including checking that the data is accurate and free of duplicates, missing values, and even null values. Additionally, when working on model construction, we need to be sure that we recognize the crucial factors in the data set and eliminate any extraneous noise that can really reduce the accuracy of our conclusions.

70% of the data science project life cycle time is spent on this step. We can extract lots of information with the proper EDA.

### Modeling the data

This is the most important step of the life cycle of data science. This tells a lot about a data science project. This phase is about selecting the right model type, depending on whether the issue is classification, regression, or clustering. Following the selection of the model family, we must carefully select and implement algorithms to be used inside that family.

There are numerous hyperparameters. Therefore, we should determine the model's ideal hyperparameter values. We don't want to overfit. So hyperparameter tuning is important in model building. This hyperparameter tuning makes the model predict correctly.

### Evaluating the model

We built a model in the previous phase. But isn't our model effective? Therefore, we must determine our model's existing status to improve it.

To evaluate the model to understand the model works better. There are two techniques used widely to assess the performance of the model. They are Hold-Out and Cross-Validation used in data science to evaluate models.

**Holdout evaluation** is the process of testing a model with data that is distinct from the data it was trained on. This offers a frank assessment of learning effectiveness.

**Cross-validation** is the process of splitting the data into sets and using them to analyze the performance of the data. In the cross-validation procedure, the initial observation data set is divided into two sets: a training set for the model's training and an independent set for the analyses' evaluation. Both approaches use a test set (unseen by the model) to assess model performance in order to prevent over-fitting.&#x20;

If the evaluation does not yield a satisfying outcome, we must repeat the modeling procedure in its entirety until the necessary level of metrics is attained.

Metrics that are used to evaluate the models are:

* Classification models:&#x20;
* Accuracy&#x20;
* ROC-AUC
* Precision-Recall o Log-Loss
* Regression models:
* MSAE
* MSPE
* R Square
* Adjusted R Square&#x20;
* Unsupervised Models:
* Mutual Information
* Rand Index

With the help of this step, we choose the right model for our business problem. Based on this step, we create the model best suits our needs.

### Deploying the model

We have reached the end of our life cycle. In this step, the delivery method that will be used to distribute the model to users or another system is created.

For various projects, this step can mean many different things. Getting your model results in a Tableau dashboard might be all that is necessary. or as complicated as growing it to millions of users on the cloud.

Any shortcuts used during the minimally viable model phase are updated to systems fit for production. This phase is typically carried out by team members who are more "engineering-focused," such as data engineers, cloud engineers, machine learning engineers, application developers, and quality assurance engineers.

The many phases of the data science life cycle should be carefully considered. The entire effort is wasted if any step is carried out incorrectly because it will have an impact on the following phase.

For instance, improper data collection will result in information loss and a model that is not perfect. The model won't function effectively if the data is not adequately cleaned. The model will fall short in the real world if it is not adequately examined. Each phase, from business comprehension to model deployment, should receive the appropriate consideration, time, and effort.
