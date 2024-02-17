# Recipe Recommendation Engine Project

## Introduction
The recommendation engine is a crucial tool for increasing user engagement on your website. By providing users with relevant recipes, you can enhance their experience and encourage them to spend more time on your site. This project focuses on building a recommendation engine for a recipe website, aiming to improve user engagement and potentially increase business opportunities such as collaborations and promotions.

![image](recommender.jpg)

## Project Objectives
In this assignment, your objective is to recommend recipes to a user. You have to build a recommender system that will generate recommendations for given user_ids.

Recommender systems in real life are expected to come up with results instantaneously. Prediction latency is more important than accuracy. The data and features these recommender systems use to make recommendations are very voluminous. As a result, we will have to sub-sample the dataset.

## Data
You will be working with three CSV files containing recipe and interaction data:

- **Raw Ratings Data (Small):** [Link to CSV file](https://raw-recipes-clean-upgrad.s3.amazonaws.com/raw_ratings_small.csv)
- **Raw Recipes Data (Small):** [Link to CSV file](https://raw-recipes-clean-upgrad.s3.amazonaws.com/raw_recipies_small.csv)
- **Raw Recipes Data (Full):** [Link to CSV file](https://raw-recipes-clean-upgrad.s3.amazonaws.com/RAW_recipes_cleaned.csv)

## Tools and Platform
- **Platform:** Google Colab
- **Algorithms:** ALS and K Nearest Neighbors (KNN)

## Task Overview
1. **Read the Data:** Read the Raw Recipes and Raw Ratings CSV files from the S3 bucket and ensure correct data types for each field.
2. **Feature Recalculation:** Recalculate features if needed as the new data files do not have the features created earlier.
3. **Build ML Model:** Use Spark platform to build your ML model. The algorithms you will use are ALS and KNN.
4. **Optional:** Using KNN and making a hybrid recommender system will be optional.

## Submission
You are expected to use the Google Colab environment to solve this assignment. You can download and submit the notebook in .ipynb format.
