# Sentiment-Analysis
This repository contains a Natural Language Processing (NLP) project focused on performing sentiment analysis on a dataset of product reviews. The project follows a complete workflow, from initial data exploration and cleaning to sentiment classification and data visualization.

Key Features
Exploratory Data Analysis (EDA): The notebook includes steps to load the dataset, check for missing values, and identify duplicate entries, ensuring data quality before analysis.

Text Preprocessing: A custom text cleaning function handles essential preprocessing tasks like converting text to lowercase, removing special characters, and eliminating common English stopwords to prepare the data for modeling.

Sentiment Classification: The project classifies customer review ratings into three main sentiment categories: Positive (ratings 4-5), Neutral (rating 3), and Negative (ratings 1-2).

Analysis & Visualization: The notebook analyzes the distribution of sentiments and identifies the most frequent words for each sentiment category. Visualizations such as a pie chart and word clouds are used to present these findings clearly.

Technology Stack
The project is built with Python and utilizes the following key libraries:

pandas: For data manipulation and analysis.

matplotlib and seaborn: For creating static, animated, and interactive visualizations.

nltk: For natural language processing tasks, including tokenization and stopword removal.

wordcloud: To generate visual representations of word frequency.
