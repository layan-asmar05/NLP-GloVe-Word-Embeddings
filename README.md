# Exploring Pretrained Word Embeddings

## Overview
This project is part of the Natural Language Processing course. The main objective is to load pretrained GloVe embeddings and explore semantic similarities between words by computing their vector representations.

## Technologies Used
* **Python**
* **NumPy:** For array operations and reshaping.
* **scikit-learn:** Specifically used for calculating `cosine_similarity`.

## Methodology
1. **Loading Embeddings:** Loaded the 100-dimensional pretrained GloVe vectors (`glove.6B.100d.txt`) into a Python dictionary.
2. **Similarity Computation:** Selected 3 distinct words and utilized scikit-learn's `cosine_similarity` metric to iterate through the dictionary and find the top 5 closest (most similar) words for each target word.
3. **Analysis:** Reflected on the nearest neighbors to evaluate if the semantic relationships made sense and identified any surprising word associations based on the GloVe model.

## Dataset
The project utilizes the **GloVe (Global Vectors for Word Representation)** dataset. Specifically, the `glove.6B.100d.txt` file (100-dimensional vectors) downloaded from Stanford's NLP group. Due to its large size, the dataset is not included in this repository but can be downloaded directly from the official source.
