# Portfolio

---

## Projects

- [Analysis of Indirect Question Answering Models Using Transfer Learning Techniques](#indirectqa)
- [One Medical Passport: Predictive Obstructive Sleep Apnea](#1mp-osa)
- [Neural Machine Translation: Vietnamese-English](#nmt-viet-eng)
- [Keepin' It Real: How to Identify Fake and Genuine Reviews](#keepin-it-real-how-to-identify-fake-and-genuine-reviews)
- [Python Price Tracking and Monitoring Tool](#python-price-tracking-and-monitoring-tool)
- [Goodreads Book Recommender System](#goodreads-book-recommender-system)
- [Food Happens in Vegas: How Can Restaurants Improve Their Yelp Profiles for Success?](#food-happens-in-vegas-how-can-restaurants-improve-their-yelp-profiles-for-success)
- [Amazon.com and Its Effect on the Retail Market and Employment](#amazoncom-and-its-effect-on-the-retail-market-and-employment)

---

## Academic projects 

### [Analysis of Indirect Question Answering Models Using Transfer Learning Techniques](/pdf/NLU_project_final.pdf)
[![GitHub Link](https://img.shields.io/badge/GitHub-Project_Code-blue?logo=GitHub)](https://github.com/anu-ujin-g/indirectqa_nlu)

**Abstract**

The IndirectQA task aims to understand responses to naturally occurring boolean questions which do not contain direct cue words. Building models that perform well on this task can be instrumental in improving performance of conversational chatbots, as well as interactions with robots or other AI agents. In this paper, we explore the recently developed Circa dataset of indirect question-answer pairs, attempting to replicate and then improve upon its classification results. We first implement the same BERT-based models fine-tuned on other datasets reported in the original paper, and then run similar experiments on other model architectures using T5, RoBERTa, and UnifiedQA. The RoBERTa model fine-tuned on MNLI and Circa achieved the highest accuracy on the test set, in both the strict (87.5%) and relaxed settings (89.6%), as well as the highest F-1 scores on both the strict (86.4%) and relaxed (89.3%) settings.

_Results from experiments using different baseline models_

<img src="images/IndirectQA_results.png?raw=true"/>

---
### [Generating Feature Impact from Individual Conditional Expectation Plots](/pdf/Generating Feature Impact from Individual Conditional Expectation Plots.pdf)
[![GitHub Link](https://img.shields.io/badge/GitHub-Project_Code-blue?logo=GitHub)](https://github.com/anu-ujin-g/mltools-fi_cate)

**Abstract**

As machine learning systems become ubiquitous, methods for understanding and interpreting these models are increasingly important. In particular, practioners are often interested in both what features the model relies on and how the model relies on them – the feature’s impact on model predictions. Previous work on feature impact including partial derivative plots and individual conditional expectation (ICE) plots has focused on a visual interpretation of feature impact. To address shortcomings in ICE, we propose several modifications for visual clarity and computational efficiency. To quantify feature impact, we also introduce ICE feature impact, a model-agnostic, performance-agnostic feature impact metric extracted from ICE plots. Additionally, we introduce an in-distribution variant of ICE feature impact to reduce the influence of out-of-distribution points. To assess utility, we conduct an experiment comparing ICE feature impact with random forest feature importance scores in a real-world dataset.

_Proposed change to the ICE algorithm_

<img src="images/ICE_algo.png?raw=true"/>

---
### [One Medical Passport: Predictive Obstructive Sleep Apnea](/pdf/Capstone_Team27_Final_Report.pdf)

**Abstract**

The use of machine learning algorithms in the medical field has gained traction on account of its ability to provide more concrete and accurate results. This research was conducted in cooperation with the healthcare SaaS company One Medical Passport to examine potential predictors of obstructive sleep apnea (OSA) and to create a pre-screening tool. We used various machine learning and deep learning algorithms including logistic regression, random forest, multi-layer perceptron, and K-modes clustering to assess the predictive power of 4 out of the 8 criteria included in STOP-BANG which is the most widely-used OSA screening questionnaire, and also explored other possible predictors that could be used to augment the existing questionnaire.

_Top 15 features and their importance weights, according to our models_

<img src="images/1MP_features.png?raw=true"/>

---
### [Neural Machine Translation: Vietnamese-English](/pdf/nmt_vi-en.pdf)
[![GitHub Link](https://img.shields.io/badge/GitHub-Project_Code-blue?logo=GitHub)](https://github.com/anu-ujin-g/nmt-vi-en)

**Abstract**

The performance of NMT models are highly sensitive to the amount of available training data. For this reason, low resource language pairs such as English- Vietnamese often suffer from poor performance. In the scope of this project, the IWSLT’15 English-Vietnamese dataset was used to experiment with different encoder-decoder architectures using LSTM and GRU RNNs, and hyperparameter tuning to maximize NMT model performance.

_Sample translations showing from left to right: complications with \<UNK\> tokens, grammatical errors, and a good translation_

<img src="images/NMT_sample.png?raw=true"/>

---
### [Keepin' It Real: How to Identify Fake and Genuine Reviews](https://github.com/anu-ujin-g/KeepinItReal/blob/master/KeepinItReal.pdf)
[![GitHub Link](https://img.shields.io/badge/GitHub-Project_Code-blue?logo=GitHub)](https://github.com/anu-ujin-g/KeepinItReal)

**Abstract**

Reviews have quickly become an important decision making tool for consumers considering both online and offline spending. Thus, for a new industry around buying and selling Fake Reviews has risen to meet the demand of unscrupulous businesses. The goal of this project is to generate a model that successfully classifies Fake and Genuine reviews.

_Visualization of the models' performance and precision scores_

<img src="images/Final_models_KIR.jpeg?raw=true"/>

---
### [Python Price Tracking and Monitoring Tool](https://github.com/anu-ujin-g/py_price_project/blob/master/Price_Tracker_report.pdf)
[![GitHub Link](https://img.shields.io/badge/GitHub-Project_Code-blue?logo=GitHub)](https://github.com/anu-ujin-g/py_price_project/)

**Abstract**

It has become increasingly difficult to shop as a rational consumer and buy products from retailers offering the lowest prices. There are differences in prices in the market; retailers offer the same product for different prices and external factors create price fluctuations over time. In our project we tracked prices across three major e-commerce companies: Amazon, Target and Walmart. We enable users to track baskets of items over time by providing specific URLs of items from Amazon or search for products using a keyword. Users can explore price data and check how prices change over time or which retailer sells a given item for the cheapest price at a given time by exploring graph of the prices.

_Sample run of the price comparison tool for a Window Shopper_

<img src="images/Price_window.jpeg?raw=true"/>

_Sample run of the price scraper for an Informed Buyer_

<img src="images/Price_scraper.jpeg?raw=true"/>

_Example of the price tracker for an Informed Buyer_

<img src="images/Price_tracker.jpeg?raw=true"/>

---
### [Goodreads Book Recommender System](https://github.com/anu-ujin-g/big_readers/blob/master/Big_Readers_writeup.pdf)
[![GitHub Link](https://img.shields.io/badge/GitHub-Project_Code-blue?logo=GitHub)](https://github.com/anu-ujin-g/big_readers/)

**Abstract**

Recommender systems are a driving force for a variety of businesses such as retailers and entertainment services, and their popularity is only rising. On the business side, it allows the companies to offer a wide range of products, without limiting them to a confined physical space. As for the users, it makes it easier for them to make a decision when consuming a product by giving them a personal recommendation based on the choices made by users with similar interests. This project explores a basic recommendation system implementation, with a comparison to single machine implementations extension. The data set that is used for this project was provided by Goodreads - an online platform for readers to share their opinions on books they’ve read. As we have explicit feedback from the users in the form of a rating, we have used a Collaborative Filtering approach, which creates a recommendation based on the behavior history of the user as well as of users that have similar interests. Additionally, as the data matrix for this type of problem is usually very sparse, we have used an Alternating Least Squares method to process the data set and make predictions.

_Sample output from the Recommender System_

<img src="images/Rec_sys.jpeg?raw=true"/>

---
### [Food Happens in Vegas: How Can Restaurants Improve Their Yelp Profiles for Success?](https://github.com/anu-ujin-g/Vegas_Foodies/blob/master/DSGA1001_TermProject2019_FinalWriteUp_VegasFoodies.pdf)
[![GitHub Link](https://img.shields.io/badge/GitHub-Project_Code-blue?logo=GitHub)](https://github.com/anu-ujin-g/Vegas_Foodies)

**Abstract**

The purpose of this data mining project is to examine how restaurants can improve their Yelp profile to become more “successful” on Yelp in Las Vegas, Nevada. Differently from the traditional approaches to this dataset, our methodology defines “success” as a binary variable through an exploratory analysis of the restaurants’ review counts and ratings on Yelp. Feature variables include categories and attributes that Yelp users can use to select which restaurant to visit. For this project, we ran Decision Tree, Random Forest, and Logistic Regression to explore key features associated with “success” and obtain recommendations for restaurants to improve their Yelp profile. Final results indicate that determinants of success vary by cuisine type.

_Comparison of the performance of different models_

<img src="images/Final_models_VF.png?raw=true"/>

---
### [Amazon.com and Its Effect on the Retail Market and Employment](/pdf/Gerelt-Od_Thesis.pdf)

**Abstract**

Amazon.com is one of the fastest growing companies in the US and its expansion threatens the continuance of brick and mortar stores. As we see an increase in the number of department store shutdowns, e-commerce is seen to be at the center for blame. However, that may not be true as Amazon is becoming a large contributor in the job market by providing more positions with better wages. Additionally, other sectors including warehousing and courier services are complement industries and they might see a positive growth in employment as a result of the expansion of the e-commerce giant.

_Growth in employment rate of Amazon as a percentage of total retail employment_

<img src="images/Amazon_emp.png?raw=true"/>

---
