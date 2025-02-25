# Music Genre Classification Using Machine Learning

## Overview

This project aims to classify music into different genres using machine learning techniques, specifically Gaussian Mixture Model (GMM) clustering and a Decision Tree classifier. The project is implemented in Python and structured in a Jupyter Notebook format. The datasets used contain attributes such as instrumentalness, danceability, artist information, and frequency-based data like amplitude and Mel frequency.

## Datasets Used
1. FMA: A Dataset for Music Analysis
2. Spotify Dataset
3. 500 Greatest Songs of All Time
4. Prediction of Music Genre
5. A Dataset for Music Analysis


## Methodology
- Data Wrangling: The preprocessing steps included cleaning the datasets, removing duplicates, handling inconsistencies, and selecting relevant features. For details, check out Data_Wrangling.ipynb.
- Exploratory Data Analysis (EDA): Visualizing the data to understand distribution and feature importance.
- Dimensionality Reduction: PCA was applied to reduce data complexity.
- Clustering: Gaussian Mixture Model (GMM) clustering was used for genre grouping.
- Classification: A Decision Tree classifier was trained using extracted features.
- Evaluation: Model performance was assessed using silhouette score, accuracy, precision, recall, and F1-score.


## Results & Findings

The Decision Tree classifier achieved an average accuracy of ~60-70% based on team assessments but ~30% from direct results. Challenges encountered included dataset limitations and model complexity, impacting the GMM clustering model's performance. Despite obstacles, the project provided valuable insights into the effectiveness of unsupervised learning in music classification.


To explore the implementation, open **[Music Classification Using Unsupervised Learning.ipynb]** and **[Data_Wrangling.ipynb]**
