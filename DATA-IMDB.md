IMBB dataset (Maas 2011)

The Internet Movie Database (Maas 2011) is an online database containing information and statistics about movies, TV shows and video games as well as actors, directors and other film industry professionals. This information can include lists of cast and crew members, movie release dates and box office information, plot summaries, trailers, actor and director biographies and other trivia.

## Dataset

IMDB consists of 50,000 ”highly polar”, binary labeled reviews from IMDB. These reviews are split 50:50 into training and testing sets. The distribution of labels within each subset of data is balanced. The dataset also includes a further 50,000 unlabeled reviews which may be used for unsupervised training.


## Results

| References           | Model                               | Accuracy (%) |
|----------------------|-------------------------------------|--------------|
| Mousa et al (2017)   | cBLSTM LM + BLSTM binary classifier | 92.83        |
| Song et al (2017)    | Embedding + Joint                   | 92.07        |
| Denis et al (2017)   | RPA(ngram)                          | 88.52        |
| Zhang et al (2016)   | DSCNN                               | 90.2         |
| Gu et al (2015)      | RSM:α-NCE-5 (idf)                   | 87.81        |
| Dai et al (2015)     | SA-LSTM                             | 92.8         |
| Kim et al (2014)     | Disc. Conn.                         | 91.4         |
| Nguyen et al (2014)  | SVM(N-grams + RbF)                  | 89.87        |
| Labutov et al (2013) | Bag of Words SVM                    | 86.14        |
| Maas et al (2011)    | Joint training                      | 88.90        |

## References 

* **Contextual Bidirectional Long Short-Term Memory Recurrent Neural Network Language Models: A Generative Approach to Sentiment Analysis** (EACL'17), A Mousa et al. [[pdf](https://pdfs.semanticscholar.org/e272/990e38a44a52ca3f1c35875888b864da5d7e.pdf?_ga=2.222912923.1229478610.1512832600-1361082864.1510655493)]
* **A Hybrid Framework for Text Modeling with Convolutional RNN** (EACL'17), A Mousa et al. [[pdf](https://pdfs.semanticscholar.org/e272/990e38a44a52ca3f1c35875888b864da5d7e.pdf?_ga=2.222912923.1229478610.1512832600-1361082864.1510655493)]
* **Learning Word Representations with Regularization from Prior Knowledge** (CoNLL'17), Y Song et al. [[pdf](https://pdfs.semanticscholar.org/2923/18f8df52eb6ff11bae0648163c6ac1ba941c.pdf?_ga=2.231751839.1229478610.1512832600-1361082864.1510655493)]
* **Online Learning of Task-specific Word Representations with a Joint Biconvex Passive-Aggressive Algorithm** (EACL'17), P Denis et al. [[pdf](https://pdfs.semanticscholar.org/ffe3/952bbcf3ea03e3de8f21b892b956e4c9cdf0.pdf?_ga=2.122241291.1229478610.1512832600-1361082864.1510655493)]
* **Dependency Sensitive Convolutional Neural Networks for Modeling Sentences and Documents** (HLT-NAACL'16), R Zhang et al. [[pdf](https://pdfs.semanticscholar.org/ec64/f650fea9b49cbf7d8bddf458388c4b362475.pdf?_ga=2.188353960.1229478610.1512832600-1361082864.1510655493)]
* **Efficient Learning for Undirected Topic Models** (ACL'15), J Gu et al. [[pdf](https://pdfs.semanticscholar.org/c013/b30508d0b2d6b564af46b9a16c28ae806276.pdf?_ga=2.20669496.1229478610.1512832600-1361082864.1510655493)]
* **Semi-supervised Sequence Learning** (NIPS'15), M Dai et al. [[pdf](https://arxiv.org/pdf/1511.01432.pdf)]
* **Credibility Adjusted Term Frequency: A Supervised Term Weighting Scheme for Sentiment Analysis and Text Classification** (WASSA@ACL'14), Y Kim et al. [[pdf](https://pdfs.semanticscholar.org/a298/8455d5cdf5bfdc36ddedcced50a1d3010dd8.pdf?_ga=2.125566986.1229478610.1512832600-1361082864.1510655493)]
* **Sentiment Classification on Polarity Reviews: An Empirical Study Using Rating-based Features** (WASSA@ACL'14), DQ Nguyen et al. [[pdf](https://pdfs.semanticscholar.org/5ff4/9f741317a511bb8cab5727595dd834b2aef7.pdf?_ga=2.159991869.1229478610.1512832600-1361082864.1510655493)]
* **Re-embedding words** (ACL'13), I Labutov et al. [[pdf](https://pdfs.semanticscholar.org/bd8c/ace00cf3deed8f78b0aa4c80021474de004c.pdf?_ga=2.164302143.1229478610.1512832600-1361082864.1510655493)]
* **Learning Word Vectors for Sentiment Analysis** (ACL'11), L Maas et al. [[pdf](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.207.5479&rep=rep1&type=pdf)]

**See Also**

* [☶ Sentiment Analysis (State of The Art)](https://github.com/magizbox/underthesea/wiki/English-NLP-SOTA##sentiment-analysis)