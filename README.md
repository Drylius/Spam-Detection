# Spam Detection Project
This is a project with the objectives of detecting whether an email is spam or ham (legitimate/not spam).

## Dataset
This project uses a dataset originally created by Omkar Pathak and distributed under the MIT License. The original dataset can be found [here](https://github.com/OmkarPathak/Playing-with-datasets/tree/master).

The license is provided in the dataset folder.

## Code
For this model that I develop firstly, I use TF-IDF to reduce the noises from common words by reducing their importance.

Being a traditional text processing TF-IDF has some weaknesses. To address these weaknesses I also implemented some modern deep learning models like BERT and LSTM for semantic and sentiment analysis.

In this project I utilize machine learning models such as, logistic regression, random forest, and SVM. These models are then combined using voting classifier as an ensemble method.

The voting classifier I used here is hard voting, where each model make its own prediction and the category (spam, ham) that has the most vote will win or chosen.

## Result
The result that I achieved from this model is 98% accuracy.