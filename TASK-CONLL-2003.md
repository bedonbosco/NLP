[CoNLL-2003 Shared Task](https://cogcomp.org/page/resource_view/81): Language-Independent Named Entity Recognition

The CoNLL-2003 (Sang et al. 2003) shared task deals with language-independent named entity recognition as well (English and German).

# Dataset

The CoNLL-2003 shared task data files contain four columns separated by a single space. Each word has been put on a separate line and there is an empty line after each sentence. The first item on each line is a word, the second a part-of-speech (POS) tag, the third a syntactic chunk tag and the fourth the named entity tag. The chunk tags and the named entity tags have the format I-TYPE which means that the word is inside a phrase of type TYPE. Only if two phrases of the same type immediately follow each other, the first word of the second phrase will have tag B-TYPE to show that it starts a new phrase. A word with tag O is not part of a phrase.

The English data is a collection of news wire articles from the Reuters Corpus. The annotation has been done by people of the University of Antwerp. Because of copyright reasons we only make available the annotations. In order to build the complete data sets you will need access to the Reuters Corpus. It can be obtained for research purposes without any charge from NIST.

The German data is a collection of articles from the Frankfurter Rundschau. The named entities have been annotated by people of the University of Antwerp. Only the annotations are available here. In order to build these data sets you need access to the ECI Multilingual Text Corpus. It can be ordered from the Linguistic Data Consortium.

## Results

| References                | Task | F1    |
|---------------------------|------|-------|
| Kudo et al. (2001) | NER  | 88.31 |
| Florian et al. (2003)     | NER  | 88.76 |
| Ando et al. (2005)     | NER  | 89.31 |


## References 
* **A Framework for Learning Predictive Structures from Multiple Tasks and Unlabeled Data** (JMLR'05), RK Ando et al. [[pdf](http://www.jmlr.org/papers/volume6/ando05a/ando05a.pdf)]
* **Named Entity Recognition through Classifier Combination** (HLT-NAACL'03), R Florian et al. [[pdf](http://clair.si.umich.edu/clair/HLT-NAACL03/conll/pdf/florian.pdf)]

**See Also**

* [☶ Named Entity Recognition (State of The Art)](https://github.com/magizbox/underthesea/wiki/English-NLP-SOTA#named-entity-recognition)