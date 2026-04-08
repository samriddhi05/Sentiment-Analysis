# Sentiment-Analysis
Sentiment Analysis project using Python and TextBlob to classify text into Positive, Negative, and Neutral sentiments based on polarity. Data is processed using Pandas and visualized with Matplotlib. Also includes a Word Cloud to highlight key patterns and frequent words in negative reviews for better insights.

Sentiment Analysis with Word Cloud

This project performs Sentiment Analysis on textual data using Natural Language Processing (NLP) techniques in Python. The main objective is to classify text into Positive, Negative, and Neutral sentiments and extract meaningful insights from customer reviews.

Features
Classifies text using TextBlob polarity
Handles real-world textual data using Pandas
Generates sentiment distribution (Positive/Negative/Neutral)
Visualizes results using Matplotlib (Pie Chart)
Extracts negative reviews and creates a Word Cloud to identify common issues
Dataset

The dataset consists of customer/product/service review sentences. Each sentence is analyzed and assigned a sentiment label based on polarity scores.

How It Works
Load dataset using Pandas
Apply sentiment function using TextBlob
Classify each sentence into sentiment categories
Count and visualize sentiment distribution
Filter negative reviews
Generate Word Cloud from negative text
Output
Sentiment classification for each sentence
Pie chart showing sentiment distribution (Positive, Negative, Neutral)
Word Cloud highlighting most frequent negative words (like product, service, frustration)
Tech Stack
Python
Pandas, NumPy
TextBlob (NLP)
Matplotlib, Seaborn
WordCloud
Use Cases
Customer feedback analysis
Product review insights
Business decision support
Social media sentiment tracking


