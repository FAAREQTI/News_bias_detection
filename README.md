# Classification

1. Roberta.ipynb - This notebook showcases the use of the RoBERTa model for a text
classification task. It includes steps for preprocessing text data, model training,
evaluation, and error analysis.
2. Random_Forest.ipynb - This notebook demonstrates the application of the Random
Forest algorithm. It focuses on feature extraction, model tuning, and performance
metrics.
3. LSTM.ipynb - This notebook presents the implementa􀆟on of an LSTM network for
sequence data processing. It covers data preparation, model architecture, training,
and validation.

# Clustering

This repository contains code for performing topic modeling and clustering on a text dataset
using various techniques such as Latent Dirichlet Allocation (LDA) with KMeans, Hierarchical
and expectation Maximization Clustering. It demonstrates how to preprocess text data,
tokenize it, create document-term matrices, and evaluate the coherence of different topic
models.

Dependencies

- Python 3.x
- Gensim
- Scikit-learn
- NLTK
File -
ChampionModel_LDAKMeansClusteringFinalProject.ipynb

# Flask Chatbot API README

Overview

This Flask application serves as a backend for a chatbot API. It receives webhook requests
from a chatbot platform, processes the requests, and returns appropriate responses based
on the defined logic.

Dependencies

- Python 3.x
- Flask
- Pandas
- NumPy
This will start the Flask app and make it accessible at http://localhost:8080 by default.

## Endpoints
- /webhook:
- Method: POST
- This endpoint is used to receive webhook requests from the chatbot platform.
- It processes the incoming requests, performs actions based on the intent recognized from
the request, and returns appropriate responses.

