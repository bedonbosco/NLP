Simverb-3500 Dataset [(Gerz 2016)](https://arxiv.org/pdf/1608.00869.pdf)

SimVerb-3500 is an evaluation resource that provides human ratings for the similarity of 3,500 verb pairs. SimVerb-3500 covers all normed verb types from the USF free-association database, providing at least three examples for every VerbNet class. This broad coverage facilitates detailed analyses of how syntactic and semantic phenomena together influence human understanding of verb meaning. Further, with significantly larger development and test sets than existing benchmarks, SimVerb-3500 enables more robust evaluation of representation learning architectures and promotes the development of methods tailored to verbs.

# Dataset

The 3,500 pairs consist of 827 distinct verbs. 29 top-level VN (VerbNet) classes are represented by 3 member verbs, while the three most represented classes cover 79, 85, and 93 member verbs. 40 verbs are not members of any VN class.

## Results

| References           | Method                               | Accuracy (%) |
|----------------------|--------------------------------------|--------------|
| Socher et al (2013)  | Naive Bayes with bag of words        | 0.818        |
| Socher et al (2013)  | Recurrent neural networks            | 0.824        |
| Faruqui et al (2015) | Sentence word embedding averages     | 0.812        |
| Faruqui et al (2015) | Retrofitted sentence word embeddings | 0.821        |
| Sedoc et al (2017)   | Signed clusters using word2vec       | 0.836        |

## References 

* **Semantic Word Clusters Using Signed Spectral Clustering** (ACL'17), J Sedoc et al. [[pdf](http://www.aclweb.org/anthology/P17-1087)]
* **A Large-Scale Evaluation Set of Verb Similarity** (EMNLP'16), D Gerz et al. [[pdf](https://arxiv.org/pdf/1608.00869.pdf)]
* **Retrofitting word vectors to semantic lexicons.** (NAACL'15), M Faruqui et al. [[pdf](https://www.cs.cmu.edu/~hovy/papers/15HLT-retrofitting-word-vectors.pdf)]
* **Recursive Deep Models for Semantic Compositionality Over a Sentiment Treebank** (EMNLP'13), R Socher et al. [[pdf](https://nlp.stanford.edu/~socherr/EMNLP2013_RNTN.pdf)]

**See Also**

* [☶ Representation (State of The Art)](https://github.com/magizbox/underthesea/wiki/English-NLP-SOTA#representation)]