# Sentimental-Analysis 
Dataset : ../input/amazon-fine-food-reviews/Reviews.csv
This is a Sentimental Analysis Python project on Amazon food reviews. we used NLTK(Natural language ToolKit). Two models used are : VADER and Roberta models.  
Amazon food reviews is a dataset which contains the reviews in the text format. We used these reviews to implement our sentimental analysis.
We first used VADER(Valence Aware Dictionary and sEntiment Reasoner) - Bag of words approach. VADER is simply a bag of words approach, which quantisizes the sentence. It basically scores each word and combines the the scores to get a total score.
Coming to Roberta model- It is pre-trained model. This a trained model on large corpus of data. This transformer model accounts for the words but also the context related to other words.
