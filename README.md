## Hate-Speech-Detection

# Pre-processing
In pre-processing following things are done:
1- Removing non-aphlabetic characters and stopwords
2- Lemmatization(the process of grouping together the inflected forms of a word so they can be analysed as a single item, identified by the word's lemma, or dictionary form)
3- Removing Duplicates
4- Resampling of data set
5- Vectorization.

# Processing
For processing, the data was split into training 80% and for testing, 20% of the data was separated. Logistic regression is used for modelling. Optimizer used liblinear as the solver.

# Results
After the model was trained it gave an accuracy of 85.37%. And using the optimizer it gave an accuracy of 87.80%.




