# Week 1
## Assignment 1
---
### Part I
#### 1. In the notes of Week 1, we compared & contrasted MLOps with DevOps. In this question, you need to understand what is meant by the term AIOps, & then contrast it with MLOps.
_AIOps,_ sometimes referred to as _Artificial Intelligence for IT Operations_ or _Algorithmic IT Operations_ is a term invented by Gartner in 2016 as an industry category for Machine Learning analytics technology that enhances IT operations analytics.

The official definition of AIOps as per Gartner is -
> AIOps platforms utilize big data, modern machine learning and other advanced analytics technologies to directly and indirectly enhance IT operations (monitoring, automation and service desk) functions with proactive, personal and dynamic insight. AIOps platforms enable the concurrent use of multiple data sources, data collection methods, analytical (real-time and deep) technologies, and presentation technologies.

In simple words, AIOps is a series of multi-layered platforms that automate IT to make it more efficient. (Gartner coined the term in 2017)

Ultimately, the goal of AIOps is to enhance IT operations. System's performance and operation information are merely tools, and not the intended goal for any project. However, when we have too much information, our priorities become distorted and identifying the root cause and implmenting effective solutions becomes difficult. This problem is solved by AIOps by collecting, processing, and observing IT operations data intelligently in order to identify the root cause and propose solutions fast. 

_MLOps_ according to Wikipedia - 
> _MLOps_ or _ML Ops_ is a set of practices that aims to deploy and maintain machine learning models in production reliably and efficiently

MLOps is a multidisciplinary approach to managing machine learning algorithms as ongoing products, each with its own continuous lifecycle. It's a discipline that aims to build, scale, and deploy algorithms to production consistently. 

Differences -
1. AIOps automates machines while MLOps standardizes processes.
2. While MLOps' goal is bridging the gap between data scientists and operation teams, therefore between ML model building and their execution, AIOps focuses on automating incidents management and intelligent root cause analysis.
3. MLOps is all about monitoring and management of ML models. AIOps is all about applying cognitive computing techniques to improve IT operations

#### 2. Interpretable Machine Learning is another concept that has attracted lot of attention recently & is promoted by most of the MLOps frameworks. Explain what it means for a linear regression model to be interpretable. 

Interpret means to explain or to present in understandable terms. In the context of ML systems, interpretability is the ability to explain or to present in understandable terms to a human. 

Interpretable ML means extracting human-understandable insights from any Machine Learning model. We often generate a lot of data and trains models, but have no idea what a particular data trend actually means. We have the data, but are unable to interpret it. Thus, Machine Learning models have been branded as ‘Black Boxes’ by many. This means that though we can get accurate predictions from them, we cannot clearly explain or identify the logic behind these predictions.

In the case of Linear Regression Models we have the following -
1. **Interpretation of a Numerical Feature** - An increase of feature $x_k$ by one unit increases the prediction for $y$ by $\beta_k$ units when all other feature values remain fixed.
2. **Interpretation of a Categorical Feature** - Changing feature $x_k$ from the reference category to the other category increases the prediction for $y$ by $\beta_k$ when all other features remain fixed.
3. **R-squared metric** - R-squared tells you how much of the total variance of your target outcome is explained by the model. The higher R-squared, the better your linear model explains the data. R-squared ranges between 0 for models where the model does not explain the data at all and 1 for models that explain all of the variance in your data.
4. **SSE** - The SSE tells you how much variance remains after fitting the linear model, which is measured by the squared differences between the predicted and actual target values.
5. **SST** - SST is the total variance of the target outcome.
6. **t-statistic for Feature Impporptance** - The importance of a feature in a linear regression model can be measured by the absolute value of its t-statistic. The t-statistic is the estimated weight scaled with its standard error. The importance of a feature increases with increasing weight. The more variance the estimated weight has (= the less certain we are about the correct value), the less important the feature is. 
7. **Visual Interpretations** - We see trend more easily when we see a visulisation. At the same time, they can also be misleading. So, careful choice of Visulisation should be made, understanding the underlying assumptions. 

#### 3. What is AutoML? How is it related to MLOps? Just as we saw a list of various MLOps tools, create a list of 3-5 tools used for AutoML (& try to explore their functionality by reading their docs).

AutoML stands for Automated machine learning (AutoML) and it is the process of automating the tasks of applying machine learning to real-world problems.

According to automl.org, 
>Automated Machine Learning provides methods and processes to make Machine Learning available for non-Machine Learning experts, to improve efficiency of Machine Learning and to accelerate research on Machine Learning.

>Machine learning (ML) has achieved considerable successes in recent years and an ever-growing number of disciplines rely on it. However, this success crucially relies on human machine learning experts to perform the following tasks:

> 1. Preprocess and clean the data.
> 2. Select and construct appropriate features.
> 3. Select an appropriate model family.
> 4. Optimize model hyperparameters.
> 5. Design the topology of neural networks (if deep learning is used).
> 6. Postprocess machine learning models.
> 7. Critically analyze the results obtained.

> As the complexity of these tasks is often beyond non-ML-experts, the rapid growth of machine learning applications has created a demand for off-the-shelf machine learning methods that can be used easily and without expert knowledge. We call the resulting research area that targets progressive automation of machine learning AutoML.

### Part II
![AWS Console Screenshot](AWS_SS.png?raw=true "AWS Console Screenshot")
