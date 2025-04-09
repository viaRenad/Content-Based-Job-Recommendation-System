# Content-Based Job Recommendation System

A project that recommends jobs to users based on their skills and interests using natural language processing (NLP) techniques. It applies both TF-IDF vectorization and word embeddings to match user input with job descriptions, focusing on semantic similarity rather than simple keyword matching.

## Features

- **Skill-Based Matching**: Matches users to jobs based on skillsets.
- **TF-IDF Approach**: Calculates similarity between user input and job descriptions using TF-IDF and cosine similarity.
- **Word Embedding Approach**: Uses pre-trained word embeddings to capture deeper semantic relationships.
- **Data Preprocessing**: Cleans and prepares job description data for analysis.
- **Performance Evaluation**: Assesses recommendation quality using Precision@5.

## Project Structure

- `Recomendation_System_tf_idf.ipynb`: Notebook implementing the TF-IDF based recommendation system.
- `Recomendation_System_Word_Embeddings.ipynb`: Notebook implementing the word embedding-based recommendation system.

## How It Works

1. **Data Cleaning**: Removes stopwords, special characters, and applies text normalization.
2. **Feature Extraction**:
   - TF-IDF vectorization: Converts text into numerical features.
   - Word Embeddings: Represents text semantically using pre-trained vectors.
3. **Similarity Scoring**: Computes similarity between the user profile and job descriptions.
4. **Job Recommendations**: Returns the top matching jobs.
5. **Evaluation**: Measures performance using Precision@5 to validate the quality of recommendations.

## Requirements

- Python 3.x
- pandas
- scikit-learn
- nltk
- gensim
- numpy

You can install the dependencies using:

```bash
pip install pandas scikit-learn nltk gensim numpy
