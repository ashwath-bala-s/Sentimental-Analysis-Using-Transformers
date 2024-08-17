# Sentimental Analysis Using Transformers

**Introduction:**

Sentiment analysis is a powerful tool for understanding public opinion, consumer behavior, and social media trends. By analyzing text data, businesses and researchers can gain valuable insights into how people feel about products, services, or events. Transformers, a state-of-the-art architecture in natural language processing (NLP), offer advanced capabilities for sentiment analysis due to their ability to capture context and nuanced meanings in text. This project aims to apply transformer models to perform sentiment analysis, enhancing the accuracy and depth of sentiment understanding.

**Problemt Statement:**

The objective of this project is to develop a sentiment analysis model using transformer architectures to classify text data into sentiment categories. By leveraging pre-trained transformer models and fine-tuning them on specific datasets, the project will enable accurate sentiment classification, providing insights into textual data from various sources like IMDB Reviews.

**Dataset:**

The Dataset used for this project is "IMDB Reviews" from Hugging Face Library.

**Project Description:**

• Utilized the IMDB Review dataset from the Hugging Face library.

• Tokenized the data to convert text into a model-understandable format.

• Configured the DataLoader to efficiently handle batching and shuffling of the tokenized data for training and validation.

• Utilized the pre-trained ALBERT model and fine-tuned it on the IMDB dataset.

• Achieved an model loss of 0.36.

• Utilized the SHAP Library for model interpretation.

• Integrated Weights and Biases (WandB) API for tracking and visualizing training metrics.

• Saved the trained model and tokenizer for future use.

• Developed a pipeline for sentiment analysis using the trained model and tokenizer.

**Skills:** Sentiment Analysis · Transformers · ALBERT · Hugging Face · Tokenization · SHAP · Weights and Bias API · Model Pipeline · Data Loader
