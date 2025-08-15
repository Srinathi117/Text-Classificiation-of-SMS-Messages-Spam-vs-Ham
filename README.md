# Text-Classificiation-of-SMS-Messages-Spam-vs-Ham
## Overview

Text preprocessing plays a vital role in organizing and analyzing short text data such as SMS messages. This project presents a complete end-to-end pipeline for clustering and topic modeling of SMS data. The raw text undergoes essential preprocessing steps including lowercasing, tokenization, stopword removal and lemmatization to prepare it for further analysis. Following preprocessing, dimensionality reduction techniques are applied to simplify high-dimensional data for visualization and interpretation. To group semantically similar messages, multiple clustering algorithms are utilized, including KMeans, Agglomerative Clustering, DBSCAN, Spectral Clustering and Gaussian Mixture Models. The effectiveness of these clustering methods is evaluated by examining representative texts from each cluster to extract underlying themes. In addition, Latent Dirichlet Allocation (LDA) is employed for topic modeling, offering deeper insights into the principal topics within the SMS corpus. This comprehensive pipeline facilitates systematic exploration of short text clustering and topic modeling techniques, contributing to the identification of meaningful patterns and structural relationships in the data.

## Dataset

The project uses the SMS Spam Collection Dataset, a popular corpus for text classification tasks.
 - Source: UCI Machine Learning Repository
 - Format: CSV file with 2 columns and 5,572 rows
 - Purpose: Classify SMS messages as spam or ham (not spam)

## Requirements

- Python
- pandas, numpy
- nltk, spaCy (for text preprocessing
- scikit-learn (for clustering, vectorization, LDA)
- gensim (for topic modeling)
- matplotlib / seaborn (for visualization)
- Libraries: OpenCV, numpy, pandas, scikit-learn, matplotlib, pillow

## Usage

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Srinathi117/Text-Classificiation-of-SMS-Messages-Spam-vs-Ham.git
