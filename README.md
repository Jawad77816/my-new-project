# Sentiment Analysis on Product Reviews

Final project for the Building AI course

## Summary

This project focuses on analyzing customer sentiment in product reviews using natural language processing (NLP) techniques. It aims to classify reviews as positive, neutral, or negative, helping businesses better understand customer feedback and improve their products.

## Background

Customer feedback is essential for businesses to enhance their products and services. However, manually analyzing large volumes of reviews can be time-consuming and prone to errors. Automating sentiment analysis can solve this problem by providing quick insights into customer opinions.

* Manual review analysis is time-consuming
* Hard to categorize mixed sentiments
* Difficulty in prioritizing feedback based on sentiment

## How is it used?

The solution is designed for businesses that collect customer reviews online. By integrating this model into their systems, businesses can automatically categorize reviews and focus on areas needing improvement. The users are typically data analysts or customer experience teams who need accurate and fast insights.

![Sentiment Analysis Workflow](https://upload.wikimedia.org/wikipedia/commons/thumb/6/69/WordCloud.png/640px-WordCloud.png)

## Data sources and AI methods

The project uses a dataset of product reviews collected from an e-commerce platform. The model leverages NLP techniques such as tokenization, stop-word removal, and TF-IDF for text preprocessing. It then applies a machine learning algorithm, such as a Support Vector Machine (SVM), to classify the sentiment.

[Amazon Product Reviews Dataset](https://www.kaggle.com/datasets)

| Technique    | Description                         |
| ------------ | ----------------------------------- |
| Tokenization | Splitting text into individual words|
| TF-IDF       | Term frequency-inverse document frequency for feature extraction|

## Challenges

This project does not address the complexity of mixed sentiments within a single review. Additionally, there are ethical concerns regarding the accuracy of sentiment classification and potential biases in the dataset that might affect the outcome.

## What next?

To improve this project, the model can be trained on a larger, more diverse dataset and fine-tuned to handle mixed sentiments. Future iterations could also explore deep learning techniques like LSTM or transformers for enhanced accuracy.

## Acknowledgments

* Inspired by the [Sentiment Analysis on Amazon Reviews](https://www.kaggle.com/datasets) project
* Thanks to the creators of the open-source datasets and NLP libraries used in this project
* [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)

---

Feel free to modify the content as needed for your specific project!
