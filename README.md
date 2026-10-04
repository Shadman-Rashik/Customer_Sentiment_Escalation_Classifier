# Customer_Sentiment_Escalation_Classifier

This project uses Python and Natural Language Processing (NLP) to analyze customer sentiment in airline-related tweets.
It automatically classifies passenger feedback into positive, negative, or neutral categories to highlight customer satisfaction levels.The resulting insights help airlines identify key pain points, improve service quality, and better understand public perception.

## What it does
- Predicts positive, neutral, or negative sentiment (TF-IDF + **Logistic Regression**).
- Compares the model with an "always guess the most common" baseline.
- Sends low-confidence messages to a human.
- Tests how much accuracy drops when typos are added.
- Ranks the most unhappy messages so they can be escalated first.
