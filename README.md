# COVID-19_Insights_on_Risk_Factors_Transmission_and_Affected_Organs

#### Please refer the presentation pdf and the ipynb uploaded

## Background

In response to the COVID-19 pandemic, the White House and a coalition of leading research groups have prepared a dataset of open sourced research papers. This data-set is a resource of over 45,000 scholarly articles, including over 33,000 with full text, about COVID-19, SARSCoV-2, and related coronaviruses. This freely available dataset is provided to the global research community to apply recent advances in natural language processing and other AI techniques to generate new insights in support of the ongoing fight against this infectious disease. There is a growing urgency for these approaches because of the rapid acceleration in new coronavirus literature, making it difficult for the medical research community to keep up and extract insight from this growing body work.

## Project Objectives

1. Implement functionality to parse natural language biomedical literature data according to given constraints and requirements.
2. Train and test machine learning algorithms (especially unsupervised machine learning algorithms such as clustering, dimensionality reduction, recommender systems, association rules, etc.) in order to gain insights or answer the overarching question you have chosen to pursue for this project.
3. Understand how to apply machine learning algorithms to the task of learning from a large corpus of biomedical research text.
4. Improve on skills and competencies required to collate and present domain specific, evidence-based insights. Particularly, in this case to gain insights and guide the fight
against the COVID-19 pandemic

## Aim:

1. To identify the **Risk Factors**, i.e., the factors which make the affect of coronavirus more likely in a person based on certain medical or social conditions
2. To determine the **Transmission Factors**, i.e., the factors which make the spread of coronavirus more likely
3. To look for the **Affected Organs** due to corona virus apart from the more commonly known 'lungs'

## Table of Contents: -

### 0.	LIBRARIES
    0.1	Downloading Libraries
    0.2	Importing Libraries
    0.3	Function Definition
### 1.	DATA PREPARATION
    1.1	Checking for missing values
    1.2	Data Cleaning
### 2.	SEARCHING LABELS
    2.1	Risk Factors
    2.2	Transmission Factors
    2.3	Affected Organs
### 3.	DATA EXPLORATION
    3.1	Frequency Related Visuals
    3.2	Reducing search labels
    3.3	Plotting with Reduced search labels
### 4.	EXPERIMENTING DIFFERENT DATAFRAMES MODEL OF RISK FACTORS LABELS FOR HEIRARCHICAL CLUSTERING
    4.1	Modified Bag of Ngrams using REGEX On Risk Factors (self developed)
    4.2	Using okapi BM25
    4.3	Using TFIDF – Vectorizer
### 5.	EXPERIMENTING DIFFERENT DATAFRAMES MODEL OF RISK FACTORS LABELS FOR KMEANS CLUSTERING
    5.1	Kmeans on Modified Bag of Ngrams using REGEX On Risk Factors (self developed)
    5.2	Kmeans on okapi BM25
    5.3	Kmeans on TFIDF – Vectorizer
### 6.	HIERARCHICAL CLUSTERING OF RISK FACTORS
### 7.	HIERARCHICAL CLUSTERING OF TRANSMISSION FACTORS
### 8.	HIERARCHICAL CLUSTERING OF AFFECTED ORGANS
### 9.	INSIGHTS AND RESULTS SUMMARY
    9.1	Summary of Coding Logic and Experimentation with Clustering
    9.2	Summary of Data Visualization and Inferred Results
        9.2.1	Risk Factors
        9.2.2	Transmission Factors
        9.2.3	Affected Organs


## References:

https://www.cdc.gov/coronavirus/2019-ncov/need-extra-precautions/people-at-higher-risk.html

https://www.canada.ca/en/public-health/services/diseases/2019-novel-coronavirus-infection/prevention-risks.html

https://www.vox.com/science-and-health/2020/4/8/21207269/covid-19-coronavirus-risk-factors

https://www.nbcnewyork.com/news/coronavirus/what-underlying-factors-put-people-at-higher-risk-for-severe-coronavirus-cases/2332144/

https://www.kff.org/global-health-policy/issue-brief/how-many-adults-are-at-risk-of-serious-illness-if-infected-with-coronavirus/

https://pypi.org/project/rank-bm25/
