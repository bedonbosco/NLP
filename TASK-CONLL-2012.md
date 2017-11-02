[CoNLL 2012 Shared Task](https://catalog.ldc.upenn.edu/ldc2013t19): Language-Independent Named Entity Recognition

OntoNotes Release 5.0 was annotate a large corpus comprising various genres of text (news, conversational telephone speech, weblogs, usenet newsgroups, broadcast, talk shows) in three languages (English, Chinese, and Arabic) with structural information (syntax and predicate argument structure) and shallow semantics (word sense linked to an ontology and coreference).

# Dataset
**[Dataset](http://conll.cemantix.org/2012/data.html)**

The goal of OntoNotes coreference annotation and modeling is to fill in the coreference portion of the shallow semantic understanding of the text that OntoNotes is targeting. The intended semantic connection can then be filled in by supplying the implicit copula. In addition to Engllish, OntoNotes also comprises data for Arabic and Chinese languages. These languages have many instances of elided subjects which are necessary to be interpreted to form the complete understanding of a sentence, and therefore the whole document. For these languages, the OntoNotes coreference data connects the elided subjects with the other explicitly mentioned instances, and as were identified during the treebank annotation.

The English data consists of a little over one million words from newswire (≈450k), magazine articles (≈150k), broadcast news (≈200k), broadcast conversations (≈200k), web data (≈200k), telephone conversations (≈200k) and English translation of the New Testament (≈200k). 

The Chinese data also comprises a little over a million words from newswire (≈300k), broadcast news (≈300k), broadcast conversation (≈200k), web data (≈200k) and telephone conversations (≈100k). 

The Arabic language on the other hand comprises a smaller collection with about ≈300k words of newswire data. 

## Results

| References            | Method                                       | F1    |
|-----------------------|----------------------------------------------|-------|
| Finkel et al. (2009)  | Base on a discriminative constituency parser | 82.42 |
| Passos et al. (2014)  | Baseline + Gaz + LexEmb                      | 82.24 |
| Durrett et al. (2014) | JOINT                                        | 84.04 |
| Chiu et al. (2015)    | BLSTM-CNN + emb + lex                        | 86.28 |


## References 
 
* **Named Entity Recognition with Bidirectional LSTM-CNNs** (CL'15), JPC Chiu et al. [[pdf](https://arxiv.org/pdf/1511.08308.pdf)]
* **A Joint Model for Entity Analysis: Coreference, Typing, and Linking** (ACL'14), G Durrett et al. [[pdf](http://www.aclweb.org/anthology/Q14-1037)]
* **Lexicon infused phrase embeddings for named entity resolution** (ACL'14), A Passos et al. [[pdf](http://www.aclweb.org/anthology/W14-1609)]
* **OntoNotes 5.0** (CoNLL'12), R Weischedel et al. [[pdf](https://catalog.ldc.upenn.edu/docs/LDC2013T19/OntoNotes-Release-5.0.pdf)]
* **Joint Parsing and Named Entity Recognition** (ACL'09), JR Finkel et al. [[pdf](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.319.8203&rep=rep1&type=pdf)]


**See Also**

* [☶ Named Entity Recognition (State of The Art)](https://github.com/magizbox/underthesea/wiki/English-NLP-SOTA#named-entity-recognition)