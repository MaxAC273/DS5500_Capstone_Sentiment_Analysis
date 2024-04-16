# DS5500_Capstone_Sentiment_Analysis

## Sentiment Analysis on Twitter Data: Exploring Abortion Discourse

Authors: Alan Cheung and Bezawit Ayalew

### Introduction

In this project, we delve into sentiment analysis on a Twitter dataset centered around discussions regarding abortion. Our goal is to utilize Python and various natural language processing (NLP) techniques to examine the sentiment expressed in tweets related to abortion. By analyzing and classifying the sentiment of these tweets, we aim to uncover insights into public opinion and attitudes surrounding this sensitive topic.

### Files Included

1. **Data Preprocessing_Classic ML Models_User Interface.ipynb**: This notebook contains code for data preprocessing and building classic machine learning models for sentiment analysis on the cleaned Twitter data. It may also include the development of a user interface (UI) for interacting with the trained models.

2. **BERTopic_sentiment_analysis.ipynb**: This notebook focuses on sentiment analysis using the BERTopic approach. BERTopic is a topic modeling technique based on BERT embeddings. The notebook likely covers preprocessing, topic modeling, and sentiment analysis using BERTopic.

3. **LDA_DistilBERT_Models.ipynb**: This notebook explores sentiment analysis using a combination of Latent Dirichlet Allocation (LDA) and DistilBERT models. LDA is a topic modeling technique, while DistilBERT is a distilled version of the BERT model. The notebook may include preprocessing, topic modeling with LDA, and sentiment analysis using DistilBERT.

4. **LDA_DistilBERT_functions.py**: This Python script likely contains reusable functions for preprocessing text data, performing LDA topic modeling, and conducting sentiment analysis using DistilBERT. It provides modularized code that can be imported and used in the notebooks or other scripts for analysis.

5. **twitier.csv**: This CSV file contains the Twitter data scraped after June 2022, focusing on discussions related to abortion. Please note that this dataset is used for sentiment analysis in this project.

### How to Use

1. **Clone the Repository**: Clone this repository to your local machine using:

    ```
    git clone https://github.com/your-username/project-name.git
    ```

2. **Navigate to the Directory**: Enter the project directory:

    ```
    cd project-name
    ```

3. **Run the Notebooks**: Execute the notebooks in your preferred environment. These notebooks contain the code for loading, cleaning, and analyzing the Twitter data.

### Dependencies

- Python 3.x
- Jupyter Notebook
- Libraries: pandas, numpy, nltk, etc. (Install dependencies using `pip install -r requirements.txt`)
