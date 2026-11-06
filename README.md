# Movie_Review_Sentiment_Analysis_Transformers
A movie review sentiment analysis project using PyTorch and a custom transformer model to classify IMDB reviews as positive or negative.
The project uses the IMDB movie review dataset to train and evaluate the model.

# Dataset
The IMDB dataset contains 50,000 labelled movie reviews.
-Training: 22,500 reviews
-Validation: 2,500 reviews
-Testing: 25,000 reviews

# Technologies Used
Python
PyTorch
Hugging Face Transformers
BERT Tokenizer (bert-base-uncased)
Pandas
NumPy
Jupyter Notebook

--> A custom transformer model called DemoGPT was implemented using:
Token Embeddings
Positional Embeddings
Transformer Blocks
Layer Normalization
Mean Pooling

-->The model classifies reviews into two categories:
Positive
Negative

-->Training
Optimizer: AdamW
Loss Function: CrossEntropyLoss
Initial Training: 3 Epochs then 5 Epochs
Learning Rate: 0.0003

# Results
The model achieved a test accuracy of 75.31% after 3 epochs and 77.14% after 5 epochs, meeting the project's target of greater than 75%.
