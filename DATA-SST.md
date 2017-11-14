[Stanford Sentiment Treebank](https://nlp.stanford.edu/~socherr/EMNLP2013_RNTN.pdf)

The Stanford Sentiment Treebank is the first corpus with fully labeled parse trees that allows for a complete analysis of the compositional effects of sentiment in language.

# Dataset

**[Dataset](https://nlp.stanford.edu/sentiment/)**

The corpus is based on the dataset introduced by Pang and Lee (2005) and consists of 11,855 single sentences extracted from movie reviews. It was parsed with the Stanford parser (Klein and Manning, 2003) and includes a total of 215,154 unique phrases from those parse trees, each annotated by 3 human judges. This new dataset allows us to analyze the intricacies of sentiment and to capture complex linguistic phenomena.

| Data | Classes | Average sentence length | Dataset size | Vocab size | Test size |
|------|---------|-------------------------|--------------|------------|-----------|
| SST1 | 5       | 18                      | 11855        | 17836      | 2210      |
| SST2 | 2       | 19                      | 9613         | 16185      | 1821      |

## Results

### SST1 DataSet

| References                 | Method             | Accuracy (%) |
|----------------------------|--------------------|--------------|
| Socher et al. (2011)       | RAE                | 43.2         |
| Socher et al. (2012)       | MV-RNN             | 44.4         |
| Socher et al. (2013)       | RNTN               | 45.7         |
| Kalchbrenner et al. (2014) | DCNN               | 48.5         |
| Irsoy et al. (2014)        | Deep Recursive NNs | 49.8         |
| Le et al. (2014)           | Paragraph-Vec      | 48.7         |
| Kim (2014)                 | CNN-multichannel   | 48.0         |
| Zhu et al. (2015)          | LSTM on tree       | 48.0         |
| Ma et al. (2015)           | DCNNs              | 49.5         |
---
### SST2 Dataset

| References                 | Method           | Accuracy (%) |
|----------------------------|------------------|--------------|
| Socher et al. (2011)       | RAE              | 82.4         |
| Socher et al. (2012)       | MV-RNN           | 82.9         |
| Socher et al. (2013)       | RNTN             | 85.4         |
| Kalchbrenner et al. (2014) | DCNN             | 86.8         |
| Le et al. (2014)           | Paragraph-Vec    | 87.8         |
| Kim. (2014)                | CNN-multichannel | 88.1         |

## References 

* **Dependency-based Convolutional Neural Networks for Sentence Embedding** (ACL'15), M Ma et al. [[pdf](http://www.aclweb.org/anthology/P15-2029)]
* **Long Short-Term Memory Over Tree Structures** (ICML'15), X Zhu et al. [[pdf](https://arxiv.org/pdf/1503.04881.pdf)]
* **A Convolutional Neural Network for Modelling Sentences** (ACL'14), N Kalchbrenner et al. [[pdf](http://www.aclweb.org/anthology/P14-1062)]
* **Distributed Representations of Sentences and Documents** (ICML'14), Q Le et al. [[pdf](https://cs.stanford.edu/~quocle/paragraph_vector.pdf)]
* **Deep Recursive Neural Networks for Compositionality in Language** (NIPS'14), O Irsoy et al. [[pdf
* **Convolutional Neural Networks for Sentence Classification** (EMNLP'14), Y Kim. [[pdf](https://arxiv.org/pdf/1408.5882.pdf)]
* **Recursive Deep Models for Semantic Compositionality Over a Sentiment Treebank** (EMNLP'13), R Socher et al. [[pdf](https://nlp.stanford.edu/~socherr/EMNLP2013_RNTN.pdf)]
* **Semantic Compositionality through Recursive Matrix-Vector Spaces** (EMNLP'12), R Socher et al. [[pdf](https://nlp.stanford.edu/pubs/SocherHuvalManningNg_EMNLP2012.pdf)]
* **Semi-Supervised Recursive Autoencoders for Predicting Sentiment Distributions** (EMNLP'11), R Socher et al. [[pdf](https://dl.acm.org/citation.cfm?id=2145450)]

**See Also**

* [☶ Sentiment Analysis (State of The Art)](https://github.com/magizbox/underthesea/wiki/English-NLP-SOTA#sentiment-analysis)