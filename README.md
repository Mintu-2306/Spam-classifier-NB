# Spam-classifier-NB
This project implements a spam e-mail classifier using the Naive Bayes algorithm. It classifies messages as 'spam' or 'ham' (non-spam) based on their content. The model is trained using a dataset of labeled messages and is deployed as a web app using Streamlit, allowing users to input a message and receive a classification.

# Spam Message Classifier

## Overview
This project is a **Spam E-mail Classifier** that uses a **Naive Bayes classifier** to predict whether a given message is spam or ham (not spam). The model was trained using a dataset of e-mails, and it is deployed as a web app using **Streamlit** for easy interaction.

## Features
- Classifies e-mails as either **Spam** or **Ham**.
- Built with **Scikit-learn**'s Naive Bayes model.
- Interactive web interface built using **Streamlit**.
- **Real-time predictions**: Enter a message and get instant classification.

## How It Works
1. The user enters an e-mail into the input box.
2. The mail is passed through a **pre-trained Naive Bayes classifier**.
3. The app predicts whether the mail is **Spam** or **Ham**.
4. The prediction is displayed in a friendly, easy-to-read format.

## Requirements

To run the app locally, you will need to have the following Python libraries installed:

- **Streamlit**: for building the web app.
- **Scikit-learn**: for the machine learning model.
- **Pandas**: for data manipulation.
- **Pickle**: for loading the pre-trained model and vectorizer.

You can install the required libraries by running the following command:
```bash
pip install -r requirements.txt
```
## How to Use
1.Clone this repository to your local machine.

2.Install the necessary dependencies by running:
```bash
pip install -r requirements.txt
```
3.Run the app using Streamlit:
```bash
streamlit run app.py
```
4.Open the app in your web browser and enter a message to see if it's spam or ham.

## Live Demo
You can try the Spam Message Classifier app [here](https://spam-classifier-nb-d3kss2cktqikx7jvprzeoc.streamlit.app/)


## Project Structure
1.```app.py```: The main Streamlit app file with the UI and logic.

2.```naive_bayes_model.pkl```: The pre-trained Naive Bayes model used for prediction.

3.```count_vectorizer.pkl```: The fitted CountVectorizer used to vectorize the text messages.
