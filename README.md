📦 SMS Chat NLP Analysis Project

This repository contains a complete Natural Language Processing (NLP) pipeline for analyzing SMS/chat messages. The project is designed to extract insights about user communication, sentiment, and common topics from a dataset of text messages.

🧩 Project Overview

The SMS Chat NLP project follows an end-to-end workflow:

Data Import & Inspection – Load and examine the SMS dataset.

Text Preprocessing – Clean text data: remove URLs, HTML, punctuation, digits, and tokenize messages.

Exploratory Data Analysis (EDA) – Analyze message lengths, top words/bigrams, and message distribution by country.

Sentiment Analysis – Use a Naive Bayes classifier trained on NLTK Twitter samples to classify messages as positive or negative.

Topic Modeling – Apply TF-IDF vectorization and NMF to extract dominant topics in the messages.

Country-Level Analysis – Compare sentiment scores across countries.

📁 Repository Structure

SMS_NLP_Complete_With_Summary.ipynb — Full Jupyter notebook with code, explanations, and visualizations.

processed_nus_sms_with_sentiment.csv — Processed dataset with sentiment labels.

Project_Report_Full.md — Markdown report summarizing findings and insights.

README.md — This GitHub-ready README.

🛠️ Features

Text Cleaning & Tokenization – Handles noise, URLs, HTML tags, punctuation, and numbers.

Exploratory Analysis – Top words, bigrams, message lengths, and country-level statistics.

Sentiment Classification – Positive or negative labeling using Naive Bayes.

Topic Modeling – Extracts 5 dominant topics from messages.

Country Comparison – Mean sentiment scores calculated and visualized per country.

🚀 How to Use

Clone this repository:

git clone https://github.com/yourusername/sms-nlp-analysis.git
cd sms-nlp-analysis


Place your SMS dataset (clean_nus_sms.csv) in the project root directory.

Create a Python environment and install dependencies:

pip install pandas numpy matplotlib seaborn nltk scikit-learn


Open SMS_NLP_Complete_With_Summary.ipynb in Jupyter Notebook or VSCode and run all cells.

After running, the processed dataset with sentiment labels will be saved as processed_nus_sms_with_sentiment.csv.

📊 Findings & Insights

Most messages originate from Singapore, India, and the United States.

Short messages dominate the dataset, with conversational language.

Naive Bayes classifier predicts a majority of messages as positive, but country-level sentiment varies.

Topic modeling identifies key themes: greetings, logistics, social interactions, reminders, and emotional expressions.

⚡ Future Enhancements

Replace Naive Bayes with transformer-based sentiment models (e.g., DistilBERT) for higher accuracy.

Integrate POS tagging and NER using SpaCy for deeper linguistic insights.

Build a web application (Flask/Django) to allow users to analyze their own chat data.

Generate advanced visualizations, like word clouds or network graphs of common terms.

📄 License

This project is open-source. Feel free to use, adapt, and expand for personal or educational purposes.

🤝 Contribution

Contributions are welcome! If you improve the code, enhance visualizations, or add features, please fork the repository and submit a pull request.
