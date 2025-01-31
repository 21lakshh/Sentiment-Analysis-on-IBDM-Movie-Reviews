# Sentiment Analysis of IMDB Movie Reviews

This project is a Sentiment Analysis system for IMDB movie reviews that classifies sentiments as either **positive** or **negative**. The model converts textual data into numerical form using the **Bag of Words (BoW)** vector representation, and it employs a **Long Short-Term Memory (LSTM)** neural network for classification. This project also utilizes **Natural Language Processing (NLP)** techniques for text preprocessing and sentiment analysis.

## Introduction
Sentiment Analysis is a natural language processing (NLP) task that involves determining the sentiment expressed in a piece of text. In this project, we analyze IMDB movie reviews to classify their sentiments as **positive** or **negative** using NLP techniques and an LSTM-based model.

## Dataset
We use the **IMDB movie reviews dataset**, which contains 50,000 movie reviews equally divided into positive and negative sentiments:
- **Training Set:** 25,000 reviews
- **Validation Set:** 5,000 reviews
- **Test Set:** 20,000 reviews

The dataset is preprocessed by converting textual data into numerical form using the Bag of Words (BoW) model and applying NLP techniques such as tokenization and text normalization.

## Model Architecture
The model leverages a **Long Short-Term Memory (LSTM)** neural network for sentiment classification. LSTM is a type of recurrent neural network (RNN) that is well-suited for sequential data, such as text.

### Key Components:
1. **Bag of Words Representation:** Converts text into a numerical format.
2. **Embedding Layer:** Converts numerical input into dense vectors of fixed size.
3. **LSTM Layer:** Captures sequential dependencies in the data.
4. **Dense Layer:** Fully connected layer for final classification.
5. **NLP Preprocessing:** Techniques such as tokenization, stemming, and stopword removal are applied to clean the text.

## Results
The model achieves the following performance metrics:

- **Training Accuracy:** 91.81%
- **Validation Accuracy:** 87.80%
- **Test Accuracy:** 88.05%

These results indicate that the model generalizes well to unseen data while maintaining high accuracy.

## Contributing
Contributions are welcome! If you have suggestions or improvements, please create a pull request or open an issue.
---

