# ⭐YelpReviewClassifier

## Description
This project classifies Yelp reviews into 1-star or 5-star categories based on the text content. It uses the Yelp Review Data Set from Kaggle and employs natural language processing techniques[^2^][2].

## Data
The dataset contains reviews of businesses by users, including the number of stars assigned, and the number of "cool," "useful," and "funny" votes each review received.

## Steps
1. **Data Loading**: Read the `yelp.csv` file into a DataFrame.
2. **Exploratory Data Analysis (EDA)**: Analyze the distribution of text lengths and star ratings.
3. **Feature Engineering**: Create a new column for text length.
4. **Model Training**: Use CountVectorizer and Multinomial Naive Bayes for classification.
5. **Evaluation**: Evaluate the model using confusion matrix and classification report.

## Results and Findings
- **Initial Model**: Achieved an accuracy of 93% using CountVectorizer and Multinomial Naive Bayes.
- **TF-IDF Model**: Including TF-IDF worsened the performance, reducing accuracy to 81%.
- **Final Model**: The best model used CountVectorizer without TF-IDF, achieving high precision and recall for 5-star reviews.

## Conclusion
The project demonstrates the effectiveness of simple text-based features and Naive Bayes for sentiment classification of Yelp reviews.
