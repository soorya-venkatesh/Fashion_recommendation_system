# Fashion_recommendation_system

## Data collection:
The data was collected from amazons product advertising API.(https://webservices.amazon.com/paapi5/documentation/)

## Problem Statement:
Given a fashion product(such as a shirt), recommend similar products to it

## Outline of the approach:
The first 2 approaches uses product title to get features and recommend products based on cosine similarity.
The techniques used to featurize product titles were
1. BOW
2. tf-idf

The 3rd approach used a VGG 16 network to extract features from product images and recommend products based on these features
