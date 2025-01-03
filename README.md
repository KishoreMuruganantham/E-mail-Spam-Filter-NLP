
# E-mail Spam Filter with Natural Language Processing 📧🚫

## Introduction 🔍

Welcome to the **E-mail Spam Filter** project! This repository contains code for building a powerful spam filter using **Natural Language Processing (NLP)** techniques. We’ll use the **SMS Spam Collection** dataset, consisting of SMS messages labeled as either "ham" (legitimate) or "spam." The aim is to create an accurate **Naïve Bayes classifier** that can classify incoming e-mails as spam or legitimate based on their content. 🎯

## Dataset 📊

The dataset used for training and testing the spam filter consists of **5,574 SMS messages** in English, each labeled as either "ham" (legitimate) or "spam". The dataset is structured with two columns:
- **v1**: Contains the label: "ham" or "spam" 📨.
- **v2**: Contains the raw text of the SMS message 📑.

## Naïve Bayes Classifier 🤖

The **Naïve Bayes classifier** is a simple but powerful **probabilistic model** commonly used for text classification tasks. In this project, we train the classifier using the SMS Spam Collection dataset, enabling it to predict whether an incoming e-mail is spam or legitimate based on its content. 📬

## Usage 🛠️

To use this project and filter spam effectively, follow these easy steps:

1. **Clone the repository** to your local machine:
   ```bash
   git clone https://github.com/YourUsername/email-spam-filter.git
   ```

2. **Install dependencies**:
   Ensure you have the necessary packages installed. Use the following command to install them:
   ```bash
   pip install -r requirements.txt
   ```

3. **Train the classifier**:
   Run the `spam_filter.py` script to train the Naïve Bayes classifier on the SMS Spam Collection dataset and evaluate its performance:
   ```bash
   python spam_filter.py
   ```

4. **Classify new e-mails**:
   Once the classifier is trained, you can use it to classify new e-mails as spam or legitimate! 📧

## Contributors ✨

- **KishoreMuruganantham**: The mastermind behind this spam filter solution! 💡

## License 📜

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and contribute! 🎉
