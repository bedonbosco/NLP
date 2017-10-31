## Datasets

The WSJ-PTB (the Wall Street Journal part of the Penn Treebank Dataset) corpus contains 1.17 million tokens and has been widely used for developing and evaluating POS tagging systems. (Gimenez and Marquez, 2004) employed one-against-all SVM based on manually-defined features within a sevenword window, in which some basic n-gram patterns were evaluated to form binary features such as: “previous word is the”, ”two preceding tags are DT NN”, etc.

## Results

| References              | Model                                        | Accuracy  |
|-------------------------|----------------------------------------------|-----------|
| Toutanova et al. (2003) | MAXENT with bidirectional dependency network | **97.24** |
| Gimenez et al. (2004)   | SVM with manual feature pattern              | 97.16     |
| Shen et al. (2007)      | Guided Learning                              | 97.16     |
| Collobert et al. (2011) | MLP with word embeddings + CRF               | 97.29     |
| Santos et al. (2014)    | MLP with character+word embeddings           | 97.32     |
| Huang et al. (2015)     | LSTM                                         | 97.29     |
| Huang et al. (2015)     | Bidirectional LSTM                           | 97.40     |
| Huang et al. (2015)     | LSTM-CRF                                     | 97.54     |
| Huang et al. (2015)     | Bidirectional LSTM-CRF                       | 97.55     |
| Kumar et al. (2015)     | DMN                                          | 97.56     |

*: per-token accuracy %

**See Also**

* [☶ Part-of-Speech Tagging (State of The Art)](https://github.com/magizbox/underthesea/wiki/English-NLP-SOTA#part-of-speech-tagging)


