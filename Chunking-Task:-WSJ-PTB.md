## Datasets

The [WSJ-PTB](https://catalog.ldc.upenn.edu/ldc2000t43) (the Wall Street Journal part of the Penn Treebank Dataset) corpus contains 1.17 million tokens and has been widely used for developing and evaluating POS tagging systems. (Gimenez and Marquez, 2004) employed one-against-all SVM based on manually-defined features within a sevenword window, in which some basic n-gram patterns were evaluated to form binary features such as: “previous word is the”, ”two preceding tags are DT NN”, etc.

## Results

| References         | Model                      | F1    |
|--------------------|----------------------------|-------|
| Kudo et al. (2001) | Emsemble of classifiers    | 93.91 |
| Sha et al. (2003)  | Second-order random fields | 88.76 |
| Shen et al. (2005) | Voting classifier scheme   | 95.23 |

## References

* **Voting between Multiple Data Representations for Text Chunking** (AAI'05), H Shen et al. [[pdf](https://pdfs.semanticscholar.org/1de0/b1f8196029d0cb1a4ab25f3ed37474b2a148.pdf)]
* **Shallow parsing with conditional random fields** (NAACL'03), F Sha et al. [[pdf](https://dl.acm.org/citation.cfm?id=1073473)]
* **Chunking with Support Vector Machines** (NAACL'01), T Kudo et al. [[pdf](http://chasen.org/~taku/publications/naacl2001.pdf)]

**See Also**

* [☶ Chunking (State of The Art)](https://github.com/magizbox/underthesea/wiki/English-NLP-SOTA#chunking)