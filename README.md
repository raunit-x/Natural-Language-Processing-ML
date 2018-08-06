# Natural-Language-Processing-ML
Some projects which use NLP in classification. NLTK and Sklearn used in python
1) Movie Reviews classification:
   In this project, 2000 movie reviews are processed using NLP from NLTK.
   -> Firstly, the reviews are converted to suitable formats and the stopwords(including punctuations) are removed
   from the array of the words.
   -> Now from this large pool of words, top 3000 words are used as features. 
   -> NaiveBayesClassification is used to classify the review into 'pos' and 'neg'.
   Accuracy - 0.792 or 79.2%. The accuracy can be increased by increasing the size of the training dataset and by
   also cleaning and improving the dataset further.
   
