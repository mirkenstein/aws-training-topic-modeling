# AWS ML Training - NLP - Topic Modeling

## Goals
Classify negative Amazon reviews in different categories to determine reasoning for unhappy customers.

## Dataset

[Amazon reviews classified as positive and negative](s3://nlp-workshop-reviews/amazon_review_polarity_csv.tgz)

## Strategy

1. Identify subset of negative reviews
2. Apply NLP (e.g. lemmatization, tokenization, stopwords removal)
3. Execute Neural Topic Model to extract topics from reviews

## References
- [AWS Documentation on Neural Topic Model (NTM) Algorithm](https://docs.aws.amazon.com/sagemaker/latest/dg/ntm.html)
- [Topic Modeling Amazon Product Reviews](https://kldavenport.com/topic-modeling-amazon-reviews/)
