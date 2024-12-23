# Text-Classifier

This text classification project focuses on categorizing news articles into one of five predefined categories: sport, business, politics, entertainment, and tech. The task involves training various machine learning models using a provided labeled dataset of 1,063 news articles. Each article contains an ID, raw text, and a corresponding category label. The project utilizes different approaches for feature extraction, such as Count Vectorization and TF-IDF, to convert textual data into numerical representations. 

The training process employs a neural network with a two-hidden-layer architecture and evaluates models using 5-fold cross-validation to ensure robust performance assessment. Metrics such as average accuracy and standard deviation for both training and testing phases are calculated to compare feature extraction methods and optimization strategies. After selecting the best-performing model, predictions are generated for a separate test dataset containing 735 unlabeled articles.

Performed careful preprocessing of the textual data, model training, hyperparameter tuning, and validation to achieve optimal classification performance. The project's emphasis on rigorous evaluation and comparison across models fosters a comprehensive understanding of document classification in the context of natural language processing.
