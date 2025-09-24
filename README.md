MACHINE LEARNING PROJECTS REPOSITORY
<br>
1.<b>IPL PREDICTION</b>
Predict Indian Premier League (IPL) match outcomes using historical match and ball-by-ball data.
<br>
<b>Description</b>

End-to-end ML pipeline to predict match winner (binary/class) using pre-match and in-play features. Includes data ingestion, feature engineering (team form, head-to-head, venue stats, toss impact, player availability), model training, evaluation, and simple deployment script.

<b>Key Features</b>

Pre-match predictions using team, venue, toss, and recent-form features

In-play/live predictions using progressive match-state features (over, wickets, runs)

Feature engineering for home/away, pitch/venue tendencies, powerplay performance

Model comparison: Logistic Regression, XGBoost/LightGBM, Random Forest, and a simple NN

Evaluation: accuracy, F1, ROC-AUC, confusion matrix, calibration

<b>Data</b>

Historical matches (match-level): date, teams, venue, toss, winner, result margin

Ball-by-ball (optional for live predictions): over, ball, batsman, bowler, runs, wickets

Player metadata: role, batting/bowling hand, fitness/availability (optional)

<b>Approach</b>

Clean & merge match + player datasets.

Engineer features: recent win% (last N matches), head-to-head stats, venue average scores, strike rates, economy rates, toss win impact.

Split by season/time (train on past seasons, validate on recent seasons).

Train models, tune hyperparameters (CV/time-series-aware split).

2.<b>Stock Market Price Prediction Model using NLP and Machine Learning</b>

1.This system combines Natural Language Processing (NLP) with machine learning models to forecast stock market movements by analyzing numerical price data (historical stock prices, indicators) along with textual financial data (news, tweets, earnings reports).

2.Built a hybrid model that combines LSTM-based time series forecasting with FinBERT-powered sentiment analysis of financial news and social media. Improved prediction accuracy of stock price trends by integrating both technical indicators and market sentiment.

3.Combines quantitative (price data) and qualitative (news sentiment) features
