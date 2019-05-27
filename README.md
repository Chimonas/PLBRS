# PLBRS
Here is the implementation of different Machine Learning techniques in order to classify text on fictional characters presented in cartoon TV series 'South Park' and 'Simpsons'.

# Datasets
The two datasets that were used were extracted from Kaggle.
• South Park: https://www.kaggle.com/tovarischsukhov/southparklinesAllseasons.csv  <br />
• Simpsons Family: https://www.kaggle.com/pierremegret/dialoguelines-of-the-simpsons

These are the amount of sentences per character in both shows combined (with >10000 sentences).

![alt text](https://github.com/Chimonas/PLBRS/blob/master/images/sentences_per_character.png)

In the code the data is cleaned and then by using the SMOTE algorithm the data is balanced by over-sampling the fewer data to match up Homer Simpson.

# Classificators

In the notebook Project notebook all the pre-processes are done and the classificators are trained. The classificators that were used are Logistic Regression, Naive Bayes classifier, Convolutional Neural Network (simple architecture), Long-Term Short-Term Memory (simple architecture). Bellow you can see the performances that they achieved.

![alt text](https://github.com/Chimonas/PLBRS/blob/master/images/table.png)


# Possible Improvements

As observed the CNN and LSTM have performed better than the other two (simpler) classificators. But it is important to note that the two neural networks have only a simple architecture with not much hyperparameter tuning.
