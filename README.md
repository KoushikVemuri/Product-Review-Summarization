# Product-Review-Summarization

This repository contains the code and resources for a customer review summarization project. The goal of this project is to extract concise summaries from customer reviews to provide valuable insights to businesses. We are utilizing the Amazon Movie and TV dataset for this purpose.

## Dataset
The dataset used for this project can be found [here](https://cseweb.ucsd.edu/~jmcauley/datasets/amazon/links.html). It contains customer reviews from the Amazon Movie and TV category.

## Project Steps

### 1. Data Cleaning
In the data cleaning phase, we perform the following actions:
- Convert all text to lowercase.
- Remove unwanted characters.
- Eliminate stop words to prepare the data for pre-processing.

### 2. Data Pre-processing
In the data pre-processing stage, we conduct the following tasks:
- Tokenization and lemmatization to transform raw text data into a structured format.
- Apply techniques such as stemming or removing HTML tags if necessary.

### 3. Feature Extraction
In feature extraction, we perform the following:
- Compute TF-IDF scores and use word embeddings to convert text into numerical data.
- Explore methods like Word2Vec or GloVe embeddings to better capture word meanings.

### 4. Summarization Model
For the summarization model, we employ extractive or abstractive summarization techniques. We utilize the following techniques and libraries:
- **Extractive Summarization**: Gensim library in Python, with techniques such as TextRank and LexRank.
- **Abstractive Summarization**: Implementation of techniques like Latent Topic Modeling Summarization (LTMS) and Recurrent Neural Networks (RNN).

## License
This project is licensed under the [MIT License](link-to-license). Feel free to use the code and resources for your own projects.

---
Feel free to reach out with any questions or feedback. Happy summarizing!
