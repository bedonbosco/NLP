[MPQA dataset](http://mpqa.cs.pitt.edu/corpora/mpqa_corpus/)

Opinion polarity detection subtask of the MPQA (Multi-Perspective Question Answering) dataset (Wiebe et al. 2005)
## Datasets
MPQA Corpus version 1.2 have 19962 subjective expressions in the 535 documents (11112 sentences) of the MPQA Corpus were annotated with their contextual polarity.

Distribution of contextual polarity tags

| Neutral | Positive | Negative | Both | Total  |
|---------|----------|----------|------|--------|
| 9057    | 3311     | 7294     | 299  | 19961  |
| 45.4%   | 16.6%    | 36.5%    | 1.5% | 100%   |

## Results

| References                  | Model       | Accuracy (%) |
|-----------------------------|-------------|--------------|
| Nakagawa et al (2010)       | Tree-CRF    | 86.1         |
| Pennington et al (2011)     | RAE         | 86.4         |
| Wang et al (2012)           | NBSVM       | 86.3         |
| Wang et al (2012)           | MNB         | 86.3         |
| Hermann et al (2013)        | CCAE        | 87.2         |
| Wang et al (2013)           | G-Dropout   | 86.1         |
| Wang et al (2013)           | F-Dropout   | 86.3         |
| Kim (2014)                  | CNN-static  | 89.6         |
| Dong et al (2014)           | Sent-Parser | 86.3         |

## References
* **A Statistical Parsing Framework for Sentiment Classification** (CL'14), L Dong et al. [[pdf](https://arxiv.org/pdf/1401.6330.pdf)]
* **Convolutional Neural Networks for Sentence Classification** (EMNLP'14), Y Kim. [[pdf](https://arxiv.org/pdf/1408.5882)]
* **Fast Dropout Training** (ICML'13),  S Wang et al. [[pdf](https://nlp.stanford.edu/pubs/sidaw13fast.pdf)]
* **The Role of Syntax in Vector Space Models of Compositional Semantics** (ACL'13),  KM Hermann et al. [[pdf](https://aclweb.org/anthology/P/P13/P13-1088.pdf)]
* **Baselines and Bigrams: Simple, Good Sentiment and Topic Classification** (ACL'12), S Wang et al. [[pdf](https://www.aclweb.org/anthology/P12-2018)]
* **Semi-Supervised Recursive Autoencoders for Predicting Sentiment Distributions** (EMNLP'11), RSJ Pennington et al. [[pdf](http://www.aclweb.org/anthology/D11-1014)]
* **Dependency Tree-based Sentiment Classification using CRFs with Hidden Variables** (ACL'10), T Nakagawa et al. [[pdf](http://www.aclweb.org/anthology/N10-1120)]
* **Recognizing Contextual Polarity in Phrase-Level Sentiment Analysis** (HLT-EMNLP'05), T Wilson et al. [[pdf](http://people.cs.pitt.edu/~wiebe/pubs/papers/emnlp05polarity.pdf)]