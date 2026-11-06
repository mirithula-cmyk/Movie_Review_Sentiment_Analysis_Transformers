# Movie_Review_Sentiment_Analysis_Transformers
A movie review sentiment analysis project using PyTorch and a custom transformer model to classify IMDB reviews as positive or negative.
The project uses the IMDB movie review dataset to train and evaluate the model.
# Movie Review Sentiment Analysis

## About the Project

SentimentScope is a movie review sentiment analysis project that uses a custom transformer model built with PyTorch.

The goal is to classify IMDB movie reviews as either **positive** or **negative**.

## Dataset

The project uses the IMDB movie review dataset containing 50,000 labelled reviews.

| Dataset | Number of Reviews |
|---|---:|
| Training | 22,500 |
| Validation | 2,500 |
| Testing | 25,000 |
| **Total** | **50,000** |

## Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- BERT Tokenizer (`bert-base-uncased`)
- Pandas
- NumPy
- Jupyter Notebook

## Model Architecture

A custom transformer model named **DemoGPT** was implemented with the following components:

- Token Embeddings
- Positional Embeddings
- Transformer Blocks
- Layer Normalization
- Mean Pooling
- Classification Layer

The model predicts one of two sentiment classes: positive or negative.

## Training Details

| Parameter | Value |
|---|---|
| Optimizer | AdamW |
| Loss Function | CrossEntropyLoss |
| Epochs | 3 |
| Learning Rate | 0.0003 |
| Maximum Sequence Length | 128 |

## Results

The model achieved a test accuracy of:
**75.31%** after 3 epochs and **77.14%** after 5 epochs
This meets the project's target of achieving more than 75% accuracy.

## Key Learnings

- Preparing and exploring a text dataset.
- Using a BERT tokenizer to process movie reviews.
- Creating a custom Dataset class using PyTorch.
- Understanding the basics of transformer architecture.
- Training and evaluating a sentiment classification model.
- Debugging errors and experimenting with model parameters.

