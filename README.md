# Customer_Sentiment_Escalation_Classifier

A small Python project where I tried to spot unhappy customers in airline tweets.

## What it does
- Predicts positive, neutral, or negative sentiment (TF-IDF + **Logistic Regression**).
- Compares the model with an "always guess the most common" baseline.
- Sends low-confidence messages to a human.
- Tests how much accuracy drops when typos are added.
- Ranks the most unhappy messages so they can be escalated first.
