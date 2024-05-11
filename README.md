# BERT-Simple-Sentiment-
Sentiment analysis with bert-base-multilingual-uncased-sentiment pretrained model.

Based on the model of github/nicknochnack

For sentiment analysis, an encoder only transformer model (BERT) is used. Basically, reviews from a webpage about products or places are scraped and fed to the model to generate reviews, indicating positivity and/or satisfaction about the product or place. The model from nlptown is finetuned for sentiment analysis on product reviews in six languages: English, Dutch, German, French, Spanish, and Italian. It predicts the sentiment of the review as a number of stars (between 1 and 5). The logit values taken from the model output indicate the sentiment in a straightforward manner.

