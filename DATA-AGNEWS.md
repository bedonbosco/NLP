[AG’s dataset](https://www.di.unipi.it/~gulli/AG_corpus_of_news_articles.html)

The dataset is provided by the academic comunity for research purposes in data mining (clustering, classification, etc), information retrieval (ranking, search, etc), xml, data compression, data streaming, and any other non - commercial activity.

## Datasets
It contains 496,835 categorized news articles from more than 2000 news sources. Choose the 4 largest classes from this corpus to construct dataset, using only the title and description fields. The number of training samples for each class is 30,000 and testing 1900.

## Results

| References         | Model              | Accuracy (%) |
|--------------------|--------------------|--------------|
| Zhang et al (2015) | BoW                | 11.19        |
| Zhang et al (2015) | BoW TFIDF          | 10.36        |
| Zhang et al (2015) | ngrams             | 7.96         |
| Zhang et al (2015) | ngrams TFIDF       | 7.64         |
| Zhang et al (2015) | Bag-of-means       | 16.91        |
| Zhang et al (2015) | LSTM               | 13.94        |
| Zhang et al (2015) | Lg. w2v Conv.      | 9.92         |
| Zhang et al (2015) | Sm. w2v Conv.      | 11.35        |
| Zhang et al (2015) | Lg. w2v Conv. Th.  | 9.91         |
| Zhang et al (2015) | Sm. w2v Conv. Th.  | 10.88        |
| Zhang et al (2015) | Lg. Lk. Conv       | 8.55         |
| Zhang et al (2015) | Sm. Lk. Conv.      | 10.87        |
| Zhang et al (2015) | Lg. Lk. Conv. Th.  | 8.93         |
| Zhang et al (2015) | Sm. Lk. Conv. Th.  | 9.12         |
| Zhang et al (2015) | Lg. Full Conv.     | 9.85         |
| Zhang et al (2015) | Sm. Full Conv.     | 11.59        |
| Zhang et al (2015) | Lg. Full Conv. Th. | 9.51         |
| Zhang et al (2015) | Sm. Full Conv. Th. | 10.89        |
| Zhang et al (2015) | Lg. Conv.          | 12.82        |
| Zhang et al (2015) | Sm. Conv           | 15.65        |
| Zhang et al (2015) | Lg. Conv. Th.      | 13.39        |
| Zhang et al (2015) | Sm. Conv. Th.      | 14.80        |


## References 
* **Character-level Convolutional Networks for Text Classification** (CL'15), X Zhang et al. [[pdf](https://arxiv.org/pdf/1509.01626.pdf)]
* **Ranking a Stream of News** (ACM'05), GM Del Corso et al. [[pdf](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.59.5776&rep=rep1&type=pdf)]

**See Also**

* [☶ Text Classification (State of The Art)](https://github.com/magizbox/underthesea/wiki/English-NLP-SOTA#text-classification)