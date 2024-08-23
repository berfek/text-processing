# **Named Entity Recognition and Sensitive Information Masking**

## Introduction
In this notebook, we will explore how to use Natural Language Processing (NLP) techniques to handle sensitive information in text data. Our focus will be on two main tasks:

1. Named Entity Recognition (NER) for Person Names using SpaCy: We will use SpaCy, a powerful NLP library, to identify and mask names of people mentioned in the text. NER helps us automatically detect specific entities like person names, organizations, locations, and more for text data analysis and privacy protection.
2. Hiding Emails, Phone Numbers, and URLs using the clean-text Library: Apart from identifying person names, we often need to anonymize other sensitive information, such as email addresses and URLs. For this task, we will use the clean-text library, which provides simple and effective functions to clean and standardize text data by removing or masking unwanted patterns like emails, URLs, and phone numbers. It also allows us to perform further data cleaning, which is why I will include those lines in the code block.

## Why is this important?
With the growing concerns around data privacy and security, it is essential to handle sensitive information carefully. Whether working with customer data, social media content, or any other text data, it's crucial to anonymize identifiable information to comply with privacy regulations like GDPR and to maintain trust with users.

## What will you learn?
How to perform Named Entity Recognition (NER) using SpaCy to identify and mask person names in text data. How to use the clean-text library to effectively hide emails, URLs, and other sensitive patterns in the text. How to combine these techniques to create a robust pipeline for anonymizing sensitive information in text datasets.

## Steps to Follow
1. Install the required libraries: We will start by installing SpaCy and clean-text to our Python environment.
2. Load SpaCy’s pre-trained model: We will use SpaCy's English model to perform NER on our text data. Here, it is crucial to translate non-English dataset before using it.
3. Write functions for masking names and other sensitive information:
4. We'll create custom functions that use SpaCy for person names and clean-text for emails and URLs.
5. Apply these functions to sample text data: We'll test our functions on sample text to see how they perform in masking sensitive information.
