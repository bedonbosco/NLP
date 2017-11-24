WordSim353 Dataset [(Gabrilovich 2002)](http://www.cs.technion.ac.il/~gabr/resources/data/wordsim353/)

The WordSimilarity-353 Test Collection (Gabrilovich 2002) contains two sets of English word pairs along with human-assigned similarity judgements. The collection can be used to train and/or test computer algorithms implementing semantic similarity measures.

## Dataset

The first set (set1) contains 153 word pairs along with their similarity scores assigned by 13 subjects. The second set (set2) contains 200 word pairs, with their similarity assessed by 16 subjects. Subjects' names have been replaced by ordinal numbers (1..13, or 1..16) to protect their privacy; identical numbers in the two sets do not necessarily correspond to the same individual.
All the subjects in both experiments possessed near-native command of English. Their instructions were to estimate the relatedness of the words in pairs on a scale from 0 (totally unrelated words) to 10 (very much related or identical words).

Each set provides the raw scores assigned by each subject, as well as the mean score for each word pair. For convenience, a combined set (combined) is provided that contains a list of all 353 words, along with their mean similarity scores. The combined set is merely a concatenation of the two smaller sets.

## Results

| References                     | Method                                       | Spearman's rho |
|--------------------------------|----------------------------------------------|----------------|
| Strube et al (2006)            | SVM                                          | 0.59           |
| Gabrilovich et al (2007)       | ESA-Wikipedia                                | 0.75           |
| Witten et al (2008)            | WLM                                          | 0.69           |
| Agirre et al (2009)            | WN30g, bag of words                          | 0.78           |
| Agirreet al (2009)             | WN30g, bag of words, context windows, syntax | 0.78           |
| Hassan et al (2009)            | Cross-lingual relatedness                    | 0.71           |
| Bruni et al (2012)             | Window2                                      | 0.70           |
| Bruni et al (2012)             | Window20                                     | 0.70           |
| JeffreyPennington et al (2014) | GloVe                                        | 0.76           |


## References 

* **GloVe: Global Vectors for Word Representation** (EMNLP'14), R JeffreyPennington et al. [[pdf](http://www.aclweb.org/anthology/D14-1162)]
* **Distributional Semantics in Technicolor** (ACL'12),  E Bruni et al. [[pdf](http://delivery.acm.org/10.1145/2400000/2390544/p136-bruni.pdf?ip=42.112.226.196&id=2390544&acc=OPEN&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E6D218144511F3437&CFID=1009032446&CFTOKEN=24870960&__acm__=1511451235_741e35323a1efb2291c0fbec6a32c583)]
* **A Study on Similarity and Relatedness Using Distributional and WordNet-based Approaches** (ACL'09), E Agirre et al. [[pdf](http://delivery.acm.org/10.1145/1630000/1620758/p19-agirre.pdf?ip=42.112.226.196&id=1620758&acc=OPEN&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E6D218144511F3437&CFID=1009032446&CFTOKEN=24870960&__acm__=1511449973_9a0659b0419093f932a18b2dd7a3b3b2)]
* **Cross-lingual semantic relatedness using encyclopedic knowledge** (EMNLP'09), S Hassan et al. [[pdf](http://delivery.acm.org/10.1145/1700000/1699665/p1192-hassan.pdf?ip=42.112.226.196&id=1699665&acc=OPEN&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E6D218144511F3437&CFID=1009032446&CFTOKEN=24870960&__acm__=1511450594_7b64f74dca366da8642eb5316ec5ec0e)]
* **An Effective, Low-Cost Measure of Semantic Relatedness Obtained from Wikipedia Links** (AAAI'08), I Witten et al. [[pdf](http://www.aaai.org/Papers/Workshops/2008/WS-08-15/WS08-15-005.pdf)]
* **Computing Semantic Relatedness using Wikipedia-based Explicit Semantic Analysis** (AAAI'07), E Gabrilovich et al. [[pdf](http://www.aaai.org/Papers/IJCAI/2007/IJCAI07-259.pdf)]
* **Computing Semantic Relatedness Using Wikipedia** (AAAI'06), M Strube et al. [[pdf](http://www.aaai.org/Papers/AAAI/2006/AAAI06-223.pdf)]
* **Placing Search in Context: The Concept Revisited** (TOIS'02), L Finkelstein et al. [[pdf](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.29.1912&rep=rep1&type=pdf)]

**See Also**

* [☶ Representation (State of The Art)](https://github.com/magizbox/underthesea/wiki/English-NLP-SOTA#representation)