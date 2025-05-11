# Flipkart_Reviews_Sentiment_Analysis
## Problem
Flipkart, one of India’s largest e-commerce platforms, hosts millions of product reviews that influence customer buying decisions. Analyzing these reviews to determine sentiment (positive, neutral, negative) helps businesses gain insights into customer satisfaction and improve product offerings and services. This project aims to build a sentiment analysis model that classifies reviews into their respective sentiment categories using Natural Language Processing (NLP) and machine learning techniques.
## Dataset Information
- Product_name: the name of the product with little details about it.
- Review: review what the customer gives about that product.
- Rating: ranges from 1 to 5 stars given by the customer.
## Approach Used
- cleaned and pre-processed review text through tokenization, stop word removal, and lemmatization. Performed Exploratory Data Analysis (EDA) to explore word frequencies, sentiment distribution, and review lengths.
- Used TF-IDF vectorization to convert text into numerical features, capturing the importance of words across the corpus. Employed SentimentIntensityAnalyzer for polarity scoring and additional feature generation.
- Tested multiple classifiers including Logistic Regression, Naive Bayes, Decision Tree, Random Forest, and XGBoost.
- Evaluated model using classification metrics like :- Accuracy, Precision, Recall, F1-score, ROC AUC, and Classification report.
## Impact
- Reduces manual effort in classifying reviews for millions of products.
- Assists sellers and product managers in making data-driven improvements.
- Detects consistent negative sentiment in reviews to flag poor-quality or defective products. Helps Flipkart identify trends in feedback and take corrective action.
