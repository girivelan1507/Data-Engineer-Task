# Data-Engineer-Task

**Overview**

This document provides a detailed explanation of the Data Engineering task performed using Python (Pandas) in Jupyter Notebook. Due to account-specific issues preventing AWS Glue and Lambda from functioning properly, data transformation was implemented using Pandas.

Initially: **What I did in AWS using dataset**

**Data Loading to AWS S3**

I load the dataset in the **S3 bucket** with proper IAM.

Then I created RDBMS on AWS like **Configured an RDS instance with MySQL**.

Now everything is setup. Next part is to transform the data using **AWS Glue or lambda**. In that case, I **faced an issues in my account** while using Glue and lambda. I can't able to perform any trasnformation.

So that only **I tried using Pandas** because as I learned pandas is also used for transformation but only for small amount of data.

**Challenges Faced in AWS**

AWS Glue and Lambda were not functional due to account issues.

Workaround: Performed data transformation locally using Pandas.

***Task Breakdown***

**1. Data Transformation using Pandas in Jupyter Notebook**

The raw data was loaded into a Pandas DataFrame.

**Applied data cleaning techniques:**

    Handling missing values.

    Standardizing column names.

    Removing duplicate records.

**Applied transformation logic:**

    Data type conversion.

    Feature engineering.

    Normalization and formatting.

**Visulaized the Transformed data in Pandas for easy understanding.**


