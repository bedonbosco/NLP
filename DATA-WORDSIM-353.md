WordSim353 Dataset [(Gabrilovich 2002)](http://www.cs.technion.ac.il/~gabr/resources/data/wordsim353/)

The WordSimilarity-353 Test Collection (Gabrilovich 2002) contains two sets of English word pairs along with human-assigned similarity judgements. The collection can be used to train and/or test computer algorithms implementing semantic similarity measures.

## Dataset

The first set (set1) contains 153 word pairs along with their similarity scores assigned by 13 subjects. The second set (set2) contains 200 word pairs, with their similarity assessed by 16 subjects. Subjects' names have been replaced by ordinal numbers (1..13, or 1..16) to protect their privacy; identical numbers in the two sets do not necessarily correspond to the same individual.
All the subjects in both experiments possessed near-native command of English. Their instructions were to estimate the relatedness of the words in pairs on a scale from 0 (totally unrelated words) to 10 (very much related or identical words).

Each set provides the raw scores assigned by each subject, as well as the mean score for each word pair. For convenience, a combined set (combined) is provided that contains a list of all 353 words, along with their mean similarity scores. The combined set is merely a concatenation of the two smaller sets.


## Results

| References                     | Method                                        | Spearman's rho |
|--------------------------------|-----------------------------------------------|----------------|
| Strube et al (2006)            | SVM                                           | 0.59           |
| Gabrilovich et al (2007)       | ESA-Wikipedia                                 | 0.75           |
| Witten et al (2008)            | WLM                                           | 0.69           |
| Agirre et al (2009)            | WN30g, bag of words                           | 0.78           |
| Agirreet al (2009)             | WN30g, bag of words, context windows, syntax  | 0.78           |
| Hassan et al (2009)            | Cross-lingual relatedness                     | 0.71           |
| Bruni et al (2012)             | Window2                                       | 0.70           |
| Bruni et al (2012)             | Window20                                      | 0.70           |
| Mikolov et al (2013)           | Word2Vec                                      | 0.78           |
| JeffreyPennington et al (2014) | GloVe                                         | 0.76           |
| Lu et al (2015)                | DCCA (Deep canonical correlation analysis)    | 0.70           |
| Schwartz et al (2015)          | Skip-gram word2vec                            | 0.79           |
| Iacobacci et al (2015)         | SENSEMBED                                     | 0.78           |
| Liu et al (2015)               | SWE (Semantic word embeddings ) + Synon-Anton | 0.72           |
| Hu et al (2016)                | RLCC                                          | 0.75           |
| Komninos et al (2016)          | Window-5 based skipgram                       | 0.71           |
| Ruan et al (2016)              | SWE (Semantic word embedding)                 | 0.68           |
| Sun et al (2016)               | SEING                                         | 0.67           |
| Sun et al (2016)               | BEING                                         | 0.73           |
| Ji et al (2016)                | WordRank                                      | 0.79           |
| Speer et al (2017)             | ConceptNet                                    | 0.82           |
| Athiwaratkun et al (2017)      | Word to Gaussian Mixture                      | 0.73           |


## References 

* **ConceptNet 5.5: An Open Multilingual Graph of General Knowledge** (AAAI'17), R Speer et al. [[pdf](https://pdfs.semanticscholar.org/26aa/6fe2028b5eefbaa40ab54ef725bbbe7d9810.pdf?_ga=2.99084254.1148628356.1511533367-1361082864.1510655493)]
* **Multimodal Word Distributions** (ACL'17), B Athiwaratkun et al. [[pdf](https://pdfs.semanticscholar.org/9fa7/947a2e5b701c18a38a0a5e240c442db1ba90.pdf?_ga=2.68520913.1148628356.1511533367-1361082864.1510655493)]
* **Different Contexts Lead to Different Word Embeddings** (COLING'16), W Hu  et al. [[pdf](https://pdfs.semanticscholar.org/45aa/106af7a6d7b198fc26b93fabb273f941d3c6.pdf?_ga=2.52218729.1148628356.1511533367-1361082864.1510655493)]
* **Dependency Based Embeddings for Sentence Classification Tasks** (HLT-NAACL'16), A Komninos et al. [[pdf](https://pdfs.semanticscholar.org/fb4c/4d3dcc21f7e78f5c5f989fa81b7458360446.pdf?_ga=2.123530955.1148628356.1511533367-1361082864.1510655493)]
* **Exploring Semantic Representation in Brain Activity Using Word Embeddings** (EMNLP'16), YP Rua et al. [[pdf](https://pdfs.semanticscholar.org/dc6e/0b2096911eb14d4e3e742996ee4a2905bd57.pdf?_ga=2.134529841.1148628356.1511533367-1361082864.1510655493)]
* **Inside Out: Two Jointly Predictive Models for Word Representations and Phrase Representations** (AAAI'16), F Sun et al. [[pdf](https://pdfs.semanticscholar.org/4df7/2c80eb59eae40133838cb967c709f1879939.pdf?_ga=2.135048177.1148628356.1511533367-1361082864.1510655493)]
* **WordRank: Learning Word Embeddings via Robust Ranking** (EMNLP'16), S Ji et al. [[pdf](https://pdfs.semanticscholar.org/6bf2/3e53cbbca9139dd8982f0bfa6072c2029dc0.pdf?_ga=2.29674495.1148628356.1511533367-1361082864.1510655493)]
* **Deep Multilingual Correlation for Improved Word Embeddings** (HLT-NAACL'15), A Lu et al. [[pdf](https://pdfs.semanticscholar.org/1f1a/dbc5a2497102aca3cc28b2382f7e417a17fa.pdf?_ga=2.98429023.1148628356.1511533367-1361082864.1510655493)]
* **Symmetric Pattern Based Word Embeddings for Improved Word Similarity Prediction** (CoNLL'15), R Schwartz et al. [[pdf](https://pdfs.semanticscholar.org/6cce/406529e93fac9f0ca5454b237ea7d099acbc.pdf?_ga=2.34514913.1148628356.1511533367-1361082864.1510655493)]
* **SensEmbed: Learning Sense Embeddings for Word and Relational Similarity** (ACL'15), I Iacobacci et al. [[pdf](https://pdfs.semanticscholar.org/907d/50fcab6dcd8716e3a6ce3f86dae0f60b9867.pdf?_ga=2.60738541.1148628356.1511533367-1361082864.1510655493)]
* **Learning Semantic Word Embeddings based on Ordinal Knowledge Constraints** (ACL'15), Q Liu et al. [[pdf](https://pdfs.semanticscholar.org/e9fa/d5d68cefe975c1bf56695c61c816be7d3136.pdf?_ga=2.119335625.1148628356.1511533367-1361082864.1510655493)]
* **GloVe: Global Vectors for Word Representation** (EMNLP'14), R JeffreyPennington et al. [[pdf](http://www.aclweb.org/anthology/D14-1162)]
* **Efficient Estimation of Word Representations in Vector Space** (ICLR'13), T Mikolov et al. [[pdf](https://arxiv.org/pdf/1301.3781.pdf)]
* **Distributional Semantics in Technicolor** (ACL'12),  E Bruni et al. [[pdf](http://delivery.acm.org/10.1145/2400000/2390544/p136-bruni.pdf?ip=42.112.226.196&id=2390544&acc=OPEN&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E6D218144511F3437&CFID=1009032446&CFTOKEN=24870960&__acm__=1511451235_741e35323a1efb2291c0fbec6a32c583)]
* **A Study on Similarity and Relatedness Using Distributional and WordNet-based Approaches** (ACL'09), E Agirre et al. [[pdf](http://delivery.acm.org/10.1145/1630000/1620758/p19-agirre.pdf?ip=42.112.226.196&id=1620758&acc=OPEN&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E6D218144511F3437&CFID=1009032446&CFTOKEN=24870960&__acm__=1511449973_9a0659b0419093f932a18b2dd7a3b3b2)]
* **Cross-lingual semantic relatedness using encyclopedic knowledge** (EMNLP'09), S Hassan et al. [[pdf](http://delivery.acm.org/10.1145/1700000/1699665/p1192-hassan.pdf?ip=42.112.226.196&id=1699665&acc=OPEN&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E6D218144511F3437&CFID=1009032446&CFTOKEN=24870960&__acm__=1511450594_7b64f74dca366da8642eb5316ec5ec0e)]
* **An Effective, Low-Cost Measure of Semantic Relatedness Obtained from Wikipedia Links** (AAAI'08), I Witten et al. [[pdf](http://www.aaai.org/Papers/Workshops/2008/WS-08-15/WS08-15-005.pdf)]
* **Computing Semantic Relatedness using Wikipedia-based Explicit Semantic Analysis** (AAAI'07), E Gabrilovich et al. [[pdf](http://www.aaai.org/Papers/IJCAI/2007/IJCAI07-259.pdf)]
* **Computing Semantic Relatedness Using Wikipedia** (AAAI'06), M Strube et al. [[pdf](http://www.aaai.org/Papers/AAAI/2006/AAAI06-223.pdf)]
* **Placing Search in Context: The Concept Revisited** (TOIS'02), L Finkelstein et al. [[pdf](http://www.cs.technion.ac.il/~gabr/papers/tois_context.pdf)]

**See Also**

* [☶ Representation (State of The Art)](https://github.com/magizbox/underthesea/wiki/English-NLP-SOTA#representation)