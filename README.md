# E-mail Spam Filter with Natural Language Processing

## Introduction
This repository contains code for building a spam filter for e-mails using Natural Language Processing (NLP) techniques. The dataset used for training and testing the spam filter is the SMS Spam Collection, which consists of SMS messages tagged as either "ham" (legitimate) or "spam". The goal of this project is to develop a Naïve Bayes classifier that can accurately classify incoming e-mails as either spam or legitimate.

## Dataset
The SMS Spam Collection dataset consists of 5,574 SMS messages in English, with each message labeled as either "ham" or "spam". The dataset is divided into two columns: 
- **v1**: Contains the label, which can be either "ham" or "spam".
- **v2**: Contains the raw text of the SMS message.

## Naïve Bayes Classifier
The Naïve Bayes classifier is a probabilistic machine learning model that is commonly used for text classification tasks. In this project, we utilize the Naïve Bayes algorithm to build a spam filter for e-mails. The classifier learns from the text data in the SMS Spam Collection dataset and predicts whether a given e-mail is spam or legitimate based on its content.

## Usage
To use the code in this repository, follow these steps:
1. Clone the repository to your local machine.
2. Ensure you have the necessary dependencies installed. You can install them using pip:
   ```
   pip install -r requirements.txt
   ```
3. Run the `spam_filter.py` script to train the Naïve Bayes classifier on the SMS Spam Collection dataset and evaluate its performance.
4. Once the classifier is trained, you can use it to classify new e-mails as either spam or legitimate.

## Contributors
- KishoreMuruganantham

## License
This project is licensed under the [MIT License](LICENSE).

---
