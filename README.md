# Suicide Prediction in Workplaces(NLP)

Create an algorithm to predict suicide in workplaces

Below are samples from training dataset

<img width="454" alt="Screen Shot 2022-11-06 at 10 57 02 PM" src="https://user-images.githubusercontent.com/98190799/200244553-db3bd56f-16e5-4114-b1d3-34cd096daf49.png">

The dataset is a collection of posts from "SuicideWatch" and 
"depression" subreddits of the Reddit platform. The posts are 
collected using Pushshift API. All posts that were made to 
"SuicideWatch" from Dec 16, 2008(creation) till Jan 2, 2021, were 
collected while "depression" posts were collected from Jan 1, 
2009, to Jan 2, 2021.

## Model Exploration
I have used pretrained bert tokenizer to encode text and tried multiple models including Logistic Regression(71.8% Accuracy), LightGBM(82.2% Accuracy), XGBoost(85,7% Accuracy), CatBoost(85.7% Accuracy), Pretrained BERT Classifier with fine-tuning(97.4%)

For the full report, please check out "Suicide Prdiction in Workplaces(NLP).pdf". 
For the code details, please check out "Suicide Prediciton(NLP).ipynb". 
