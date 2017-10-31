[TREC question dataset](http://cogcomp.org/Data/QA/QC/)

Task involves classifying a question into 6 question types (whether the question is about person, location, numeric information, etc.) (Li and Roth, 2002)

## Datasets

5952 sentences. Data are collected from four sources: 4,500 English questions published by USC (Hovy et al., 2001),
about 500 manually constructed questions for a few rare classes, 894 TREC 8 and TREC 9 questions,
and also 500 questions from TREC 10 which serves as our test set.

6 coarse classes (ABBREVIATION, ENTITY, DESCRIPTION, HUMAN, LOCATION and NUMERIC VALUE) and 50 fine classes

## Results

| References                | Model          | Accuracy (%) |
|---------------------------|----------------|--------------|
| Li et al (2002)           | HIER           | 91.0         |
| Blunsom et al (2006)      | MAXENT         | 92.6         |
| Huang et al (2008)        | MAXENT         | 93.6         |
| Silva et al (2011)        | SVM            | 95.0         |
| Kalchbrenner et al (2014) | DCNN           | 93.0         |
| Kim (2014)                | CNN-non-static | 93.4         |

## References

* **Learning question classifiers** (ACL'02), X Li et al. [[pdf](http://aclweb.org/anthology/C02-1150)]
* **Question classification with log-linear models** (SIGIR'06), P Blunsom et al. [[pdf](https://dl.acm.org/citation.cfm?id=1148282)]
* **Question classification using head words and their hypernyms** (EMNLP'08), Z Huang et al. [[pdf](https://dl.acm.org/citation.cfm?id=1148282)]
* **From symbolic to subsymbolic information in question classification** (AIR'11), J Silva et al. [[pdf](http://www.inesc-id.pt/pt/indicadores/Ficheiros/6678.pdf)]
* **A Convolutional Neural Network for Modelling Sentences** (ACL'14), N Kalchbrenner et al. [[pdf](http://www.aclweb.org/anthology/P14-1062)]
* **Convolutional Neural Networks for Sentence Classification** (EMNLP'14), Y Kim. [[pdf](https://arxiv.org/pdf/1408.5882)]

**See Also**

* [☶ Text Classification (State of The Art)](https://github.com/magizbox/underthesea/wiki/English-NLP-SOTA#text-classification)
