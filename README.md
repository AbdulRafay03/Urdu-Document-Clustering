# Urdu News Clustering Using Headlines

## Table of Contents
1. [Introduction](#introduction)
2. [Objectives](#objectives)
3. [Data Collection](#data-collection)
4. [Preprocessing](#preprocessing)
5. [Feature Extraction](#feature-extraction)
6. [Clustering](#clustering)
7. [Evaluation](#evaluation)
8. [Results](#results)
9. [Conclusion](#conclusion)
10. [Future Work](#future-work)
11. [Installation](#installation)
12. [Usage](#usage)
13. [Contributing](#contributing)
14. [License](#license)

## Introduction
This project aims to cluster Urdu news headlines using natural language processing (NLP) techniques. The primary objective is to group similar news headlines together, enabling better organization and analysis of news data.
**Data**: Urdu news articles from BBC and Voice of America.
## Objective
1. **Preprocessing**: Clean and preprocess the text data, including tokenization and removal of stopwords.
2. **Feature Extraction**: Extract meaningful features using techniques such as TF-IDF (Term Frequency-Inverse Document Frequency).
3. **Clustering**: Apply clustering algorithms to group similar news headlines together.
4. **Evaluation**: Evaluate the clustering results to ensure meaningful groupings.
5. **Similar News**: Find similar news of the input

## Preprocessing
Preprocessing steps include:
- **Normalization**: Converting text to a consistent format, including lowercasing and removing punctuation.
- **Stopwords Removal**: Removing common Urdu stopwords that do not contribute to the meaning of the sentences.
- **Stemming**: Reducing words to their root form to unify different variations of the same word.
- **Vectorization**: Converting text data into numerical format using techniques like TF-IDF.
- **Named Entity Recognition (NER)**: Identifying and classifying entities in the text such as names of people, organizations, and locations.
  
## Feature Extraction
We use the TF-IDF vectorization technique to convert text data into numerical features for clustering.

## Clustering
We apply the K-Means clustering algorithm to group similar headlines. Other clustering algorithms like DBSCAN and Hierarchical Clustering can also be explored in future work.

## Evaluation
We evaluate the clustering results using the Silhouette Score, which measures the quality of clustering.

## Results
The clustering results indicate that the news headlines were successfully grouped into meaningful clusters. Each cluster represents a specific topic, allowing for better organization and analysis of the news data.

## Conclusion
This project demonstrates the effectiveness of using NLP and clustering techniques to group similar Urdu news headlines. The approach can be extended to other languages and types of text data for improved information retrieval and organization.

## Future Work
- **Improve Preprocessing**: Enhance text preprocessing steps to include more advanced techniques.
- **Explore Other Clustering Algorithms**: Experiment with other clustering algorithms like DBSCAN and Hierarchical Clustering.
- **Incorporate Deep Learning**: Use deep learning models like BERT for better feature extraction and clustering performance.
