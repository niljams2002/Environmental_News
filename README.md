# Environmental News Text Search and Analysis System

## Overview
This system provides advanced text search and analysis for environmental news data, leveraging NLP techniques for diverse query handling and semantic matching.

## Features
- **Data Extraction**: Automated extraction from CSV files in a zip archive from the Kaggle link mentioned below.
- **Text Preprocessing**: Includes normalization, stopwords removal, punctuation removal, and lemmatization.
- **Search Functionality**: Supports single word, phrase, boolean, and wildcard queries.
- **Indexing Techniques**: Uses inverted index and B-Tree for efficient data retrieval.
- **K-Gram Generation**: Facilitates effective wildcard searches.
- **TF-IDF Analysis**: Employs TF-IDF for search result relevance measurement.
- **Semantic Matching**: Integrates Spacy for semantic similarity assessment.

## Technologies
- Python, NLTK, TextBlob, Pandas, Scikit-learn, Spacy
- Dataset Source: https://www.kaggle.com/datasets/amritvirsinghx/environmental-news-nlp-dataset?resource=download

## Installation & Usage
1. Install the required Python libraries.
2. Download and extract the dataset from Kaggle.
3. Run the Python script to start the application.

## Evaluation
- The system was tested on various search queries. A specific wildcard query achieved a precision of 0.921 and recall of 0.833, demonstrating high effectiveness.

