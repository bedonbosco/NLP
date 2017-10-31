## Datasets

The [WSJ-PTB](https://catalog.ldc.upenn.edu/ldc2000t43) (the Wall Street Journal part of the Penn Treebank Dataset) corpus contains 1.17 million tokens and has been widely used for developing and evaluating POS tagging systems. (Gimenez and Marquez, 2004) employed one-against-all SVM based on manually-defined features within a sevenword window, in which some basic n-gram patterns were evaluated to form binary features such as: “previous word is the”, ”two preceding tags are DT NN”, etc.

## Results

| References              | Model                                        | Accuracy  |
|-------------------------|----------------------------------------------|-----------|
| Toutanova et al. (2003) | MAXENT with bidirectional dependency network | 97.24 |
| Gimenez et al. (2004)   | SVM with manual feature pattern              | 97.16     |
| Shen et al. (2007)      | Guided Learning                              | 97.33     |
| Collobert et al. (2011) | MLP with word embeddings + CRF               | 97.29     |
| Santos et al. (2014)    | MLP with character+word embeddings           | 97.32     |
| Huang et al. (2015)     | LSTM                                         | 97.29     |
| Huang et al. (2015)     | Bidirectional LSTM                           | 97.40     |
| Huang et al. (2015)     | LSTM-CRF                                     | 97.54     |
| Huang et al. (2015)     | Bidirectional LSTM-CRF                       | 97.55     |
| Kumar et al. (2015)     | DMN                                          | **97.56**     |

## References

* **Ask Me Anything: Dynamic Memory Networks for Natural Language Processing** (ICML'15), A Kumar et al. [[pdf](https://arxiv.org/pdf/1506.07285.pdf)]
* **Bidirectional LSTM-CRF Models for Sequence Tagging** (arXiv'15), Z Huang et al. [[pdf](https://arxiv.org/pdf/1508.01991.pdf)]
* **Natural Language Processing (Almost) from Scratch** (JMLR'11), R Collobert et al. [[pdf](http://www.jmlr.org/papers/volume12/collobert11a/collobert11a.pdf)]
* **Guided Learning for Bidirectional Sequence Classification** (ACL'07), L Shen et al. [[pdf](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.108.6948&rep=rep1&type=pdf)]
* **SVMTool: A general POS tagger generator based on Support Vector Machines** (LREC’04), JA Gimenez et al. [[pdf](http://www.lsi.upc.es/~nlp/SVMTool/lrec2004-gm.pdf)]]
* **Feature-Rich Part-of-Speech Tagging with a Cyclic Dependency Network** (HTL-NAACL'03), K Toutanova et al. [[pdf](http://www.aclweb.org/anthology/N03-1033)]

**See Also**

* [☶ Chunking (State of The Art)](https://github.com/magizbox/underthesea/wiki/English-NLP-SOTA#chunking)