# TWEET (Twitter Wisdom Extraction and Evaluation Tool)

TWEET is an NLP-based model that detects and analyzes fake news on Twitter. This project aims to develop a model to accurately detect and classify fake news on Twitter, providing insights into their spread and propagation mechanisms to help address the growing issue of misinformation on social media platforms.

## Objectives

The primary objectives of this project are:

- Develop an NLP model to accurately detect and classify fake news on Twitter.
- Analyze the characteristics of fake news tweets, including their linguistic features and the users who propagate them.
- Investigate the spread of fake news on Twitter, identifying factors that contribute to their propagation.
- Provide actionable insights and recommendations for combating the spread of fake news on Twitter and reinforcing public trust in reliable information sources.

## Dataset

The dataset for this project consists of tweets collected through the Twitter API. The dataset includes both genuine and fake news tweets, properly labeled to train and evaluate the model accurately.

## Methodology

The project follows the following steps to achieve the objectives:

- Data Collection: Collect a dataset of tweets, including both genuine and fake news, with proper labeling. Custom dataset created through the Twitter API.
- Feature Extraction: Extract relevant linguistic features from the tweets, such as the use of sensationalist language, lexical diversity, and sentiment polarity.
- Model Development: Train and evaluate various NLP models, such as BERT, to optimize their performance on the collected dataset. Utilize techniques such as cross-validation and hyper-parameter tuning to ensure the model's generalization and robustness.
- Analysis: Analyze the fake news tweets to identify common characteristics, sources, and patterns in their linguistic features. Investigate the propagation of fake news on Twitter, examining factors such as user engagement, retweet patterns, and the influence of bot accounts.
- Recommendations: Provide actionable insights and recommendations for combating the spread of fake news on Twitter and reinforcing public trust in legitimate information sources.

## Outcome

Upon successful completion of the project, the expected outcomes are:

- A high-performance NLP model for detecting fake news on Twitter.
- Insights into the characteristics of fake news tweets and the users who propagate them.
- An understanding of the spread of fake news on Twitter and the factors that contribute to their propagation.
- Recommendations for combating the spread of fake news on Twitter and reinforcing public trust in legitimate information sources.

## Repository Structure

The repository structure is as follows:

- `data`: contains the dataset used for training and evaluation.
- `notebooks`: contains Jupyter notebooks with data exploration, feature extraction, and model training and evaluation.
- `src`: contains Python scripts for data preprocessing, feature extraction, and model training and evaluation.

## Ethics

This project adheres to strict ethical guidelines, ensuring that the collected data is anonymized and that the privacy of individuals is respected. We have obtained the necessary permissions and comply with the terms and conditions of the Twitter API while collecting data. We avoid targeting specific individuals or groups and focus on the broader phenomenon of fake news.

## Conclusion

The TWEET project has the potential to make a significant contribution to the ongoing fight against misinformation. By developing a highly accurate NLP model tailored for Twitter and providing valuable insights into the spread of fake news on this platform, this project can inform strategies for mitigating the impact of misinformation and promoting trust in legitimate information sources.
