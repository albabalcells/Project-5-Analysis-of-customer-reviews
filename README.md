<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Title of My Project
*Alba Balcells*

*Data Analytics Ironhack Barcelona, June 2020*

## Content
- [Project Description](#project-description)
- [Questions](#hypotheses-questions)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description

Businesses deal with large volumes of unstructured text on a daily basis. This data can come from many different sources (reviews, mails, social media interactions...) and contains valuable information for the company. However, going through all these texts is a tedious task to do manually. Topic analysis models enable to shift through large datasets and identify and get insights on the most frequent topics. 

By finding the most relevant topics discussed, a company can identify areas of improvement for the product, monitor brand image or automatically tagging customer support tickets according to topic, just to name a few.

For this project, I will focus on +30,000 reviews for HelloFresh, a food subscription company that sends pre-portioned ingredients to users’ doorstep on a weekly basis. I will aim to define the main topics discussed by customers using Latent Dirichlet Allocation (LDA), a popular algorith for topic modelling. Moreover, I will build a sentiment analysis model that classifies good and bad reviews based on only the text.

## Hypotheses / Questions
- What are the main topics discussed in the reviews?
- Do reviews discuss multiple topics?
- Is there a difference on the average rating amongst different topics?

## Dataset
The dataset I used for the analysis contains +30,000 HelloFresh reviews I previously scrapped from [Trustpilot](https://www.trustpilot.com/review/hellofresh.com). 

## Workflow
- Web scraping of Trustpilot reviews
- Exploratory analysis of reviews
- Data cleaning for Topic Modelling
- LDA 
- Sentiment Analysis (VADER, Gaussian Naive Bayes, Random Forest Classifier, Logistic Regression and Linear SVC)

## Organization
The repository contains 2 notebooks:
- *Trustpilot Scraper* contains a code used for webscrapping Trustpilot HelloFresh reviews.
- *HelloFresh review analysis* contains the core of the project: data cleaning, topic modelling and sentiment analysis.
The folder *data* contains csv files exported in the process of the analysis.

## Links

[Repository](https://github.com/albabalcells/Project-5-Analysis-of-customer-reviews)  
[Slides](https://drive.google.com/file/d/18bXyN1WuU3i5IgbIKv5Tp5KtC_-p8U9u/view?usp=sharing)  
