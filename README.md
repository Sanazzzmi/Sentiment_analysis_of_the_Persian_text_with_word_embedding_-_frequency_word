# Sentiment_analysis_of_the_Persian_text_with_word_embedding_-_frequency_word
[This article](http://acta.uni-obuda.hu/Hayashi_Fujita_94.pdf) uses Twitter datasets and movie datasets for English language. But we have used Persian comments.
<br>
Also, in this article, only the xgboost classifier is used ، But we used different classifiers and clustering and CNN for better comparison.
<br>
In this article, wordembedding glove is used in English language And we have used word embedding fasttext in Persian.
<br>
In the final output, we have a 300-dimensional vector for each sentence. Which we gave these vectors as input to classifiers and clusters
<br>
Dataset used => [digikala dataset](https://www.digikala.com/opendata/#section-4) 
|method               | accuracy      | 
| --------------------|:-------------:| 
| SVM                 | 87%           |
| CNN                 | 86%           |
| LogisticRegression  | 85%           |
