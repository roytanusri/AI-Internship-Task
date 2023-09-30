# AI-Internship-Task
* I have selected a few classifiers algorithms for my project. My project title is Sentiment Analysis Of Restaurant Reviews.

* The first step was to process the given dataset. In data processing, I used NLTK (Natural Language Toolkit) and cleared the unwanted words in my vector. I accepted only alphabets and converted it into lower case and split it in a list. Using the PorterStemmer method stem I shorten the lookup and Normalized the sentences. Then stored those words which are not a stopword or any English punctuation.

* Secondly, I used CountVectorizer for vectorization. Also used fit and transform to fit and transform the model.

* The next step was Training and Classification. Using train_test_split 20% of data was used for testing and remaining was used for training. The data were trained on Multinomial Naive Bayes, Bernoulli Naive Bayes and RandomForest algorithms.

* Later metrics like Confusion matrix, Accuracy, Precision, Recall were used to calculate the performance of the model.

* Lastly, the best model was tuned to get a better result.
