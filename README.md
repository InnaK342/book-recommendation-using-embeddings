# Book Recommendation System using Cosine Similarity and Embeddings

This repository contains a Jupyter notebook that demonstrates how to build a book recommendation system using **cosine similarity** and **BERT embeddings**. The system recommends books based on a user's input by comparing the similarity of their descriptions with other books in the dataset.

## Overview

The recommendation system leverages the following techniques:

- **BERT (Bidirectional Encoder Representations from Transformers)**: Used for generating text embeddings for book titles, authors, categories, and descriptions.
- **Cosine Similarity**: Measures the similarity between the embeddings of the user's input and other books in the dataset to find the closest matches.

## Dataset

The dataset used in this project is the **Books Dataset**, which is available on Kaggle. You can access it [here](https://www.kaggle.com/datasets/elvinrustam/books-dataset).

## Files

- `Recommendation_systems_using_cosine_similarity_and_embeddings.ipynb`: The main notebook containing the code for loading the dataset, creating embeddings, and recommending books based on the input.
- `README.md`: This file, describing the project.

## Usage

1. Open the Jupyter notebook `Recommendation_systems_using_cosine_similarity_and_embeddings.ipynb`.
2. Run the cells to process the book data, generate embeddings using BERT, and get book recommendations based on a given description.
