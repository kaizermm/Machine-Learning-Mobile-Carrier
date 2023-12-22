# Machine Learning Mobile-Carrier

## Introduction
In this endeavour, we embark on a mission to assist Mobile carrier Megaline in optimizing their customer plans. Faced with the challenge of numerous customers still using legacy plans, our goal is to develop an advanced model that leverages behavior data. This model will not only analyze customer behavior but also recommend the ideal plan from Megaline's newer offerings: Smart or Ultra.

## Objectives
In this project for mobile carrier Megaline, the goal is to develop a model that analyzes subscribers' behavior and recommends one of their newer plans, either Smart or Ultra. Utilizing behavior data from subscribers who have already transitioned to these plans, the project focuses on building a model with an accuracy threshold of 0.75. The project workflow begins with data exploration, followed by data splitting into training, validation, and test sets. The main phase involves investigating different machine learning models and hyperparameter adjustments to achieve optimal performance. Key findings are documented for each model tested. After selecting the most suitable model, it undergoes a rigorous assessment using the test dataset to ensure its predictive accuracy. Additionally, a crucial additional task is performed to address complexities in the dataset and verify the model's sanity and robustness. This multifaceted project aims to provide Megaline with a highly accurate recommendation model to enhance their subscriber experience and plan adoption.

## Data Description

* сalls — number of calls,
* minutes — total call duration in minutes,
* messages — number of text messages,
* mb_used — Internet traffic used in MB,
* is_ultra — plan for the current month (Ultra - 1, Smart - 0).
