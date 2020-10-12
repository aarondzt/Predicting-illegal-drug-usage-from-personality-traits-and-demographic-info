# Predicting illegal drug usage from personality traits and demographic info
 
## Contents
* [Data source](https://archive.ics.uci.edu/ml/datasets/Drug+consumption+%28quantified%29)
* [Data files](Data)
* [Reference](References/The%20Five%20Factor%20Model%20of%20personality%20and%20evaluation%20of%20drug%20consumption%20risk.pdf)
* [Code/report](Drugs.ipynb)
* [Presentation](https://docs.google.com/presentation/d/1--JX88b1WO0hTc4KWwH6YXi9OkvIZe01IEJnCd_ium0/edit?usp=sharing)
* [YouTube](https://youtu.be/_M2cwrQhsxU)

## Abstract
Understanding the personality traits that are predictive of illegal drug usage is important for public health and guidence of policy-making. In [Fehrman et al.](https://arxiv.org/abs/1506.06297), the authors collect survey data on demographic factors, personality traits, and drug usage, and then run several machine learning models to analyze the traits that are predictive of the usage of individual and clusters of drugs. In this project, I focused on individuals who have used drugs that are widely classified as illegal (mushrooms, ecstasy, cocaine, LSD, ketamine, heroin, and crack) at least once. Very few people will take any one of these drugs in their lifetime, so the type of person who would cross that threshold would be interesting to understand.

I ran logistic regression and decision tree classifier models, which exhibited similar test accuracy (~70%) to the models described in the paper. The logistic regression model demonstrated that the personality traits of sensation seeking and openness to experience, in addition to the demographic of men were the most predictive of illegal drug use. The decision tree classifier demonstrated that a branch of lower sensation seeking, lower openness, and higher conscientiousness was the most predictive of never using an illegal drug.

## Project Info
<pre>
Contributors : <a href=https://github.com/aarondzt>Aaron Tan</a>
</pre>

<pre>
Languages    : Python
Tools/IDE    : Anaconda
Libraries    : numpy, pandas, matplotlib, seaborn, sklearn, statsmodels
</pre>

<pre>
Date published     : 10.12.2020
</pre>
