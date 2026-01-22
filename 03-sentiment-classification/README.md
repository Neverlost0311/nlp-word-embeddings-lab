# Lab 3: Sentiment Classification using Embeddings

## Objective
In this lab, we use text embeddings as input features to train a classical machine learning model for sentiment classification.

We use:
- IMDB movie reviews dataset
- Gemini embedding model
- XGBoost classifier

## Steps Performed

1. Load and preprocess the IMDB dataset
2. Convert text reviews into embeddings using Gemini API
3. Split data into training and testing sets
4. Train an XGBoost classifier on embedding vectors
5. Evaluate the model using accuracy and classification report
6. Test the model on custom user inputs

## Key Learning

- Embeddings can be used as powerful features for traditional ML models
- Even simple classifiers perform extremely well with good embeddings
- This approach is commonly used in production NLP systems

## Files

- `lab3_sentiment_classification.ipynb` → Full implementation notebook
