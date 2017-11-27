Rare Word (RW) dataset [(Luong 2013)](https://nlp.stanford.edu/~lmthang/morphoNLM/)

Most existing word similarity datasets contain frequent words and few of them possesses enough rare or morphologically complex words that we could really attest the expressiveness of our morphoRNN models. Good embedding in general should be able to learn useful representations for not just frequent words but also rare ones. Rare Word (Luong 2013) is dataset focusing on rare words to complement existing ones.

## Dataset

Dataset construction proceeds in three stages: (1) select a list of rare words, (2) for each of the rare words, find another word (not necessarily rare) to form a pair, and (3) collect human judgments on how similar each pair is. 

**Rare word selection**: choices of rare words (word1) are based on their frequencies – based on five bins (5, 10], (10, 100], (100, 1000], (1000, 10000], and the affixes they possess. To create a diverse set of candidates, randomly select 15 words for each configuration (a frequency bin, an affix).

**Pair construction**: Create pairs with interesting relationships for each word1 as follow. This stage collected 3145 pairs.

**Human judgment**: Use Amazon Mechanical Turk to collect 10 human similarity ratings on a scale of [0, 10] per word pair. After this stage only 2034 pairs are retained.

## Results

| References                | Method                          | Spearman's rho |
|---------------------------|---------------------------------|----------------|
| Luong et al (2013)        | C&W + csmRNN                    | 0.34           |
| Botha et al (2014)        | CLBL++                          | 0.30           |
| Qiu et al (2014)          | HSMN +MorphemeCBOW              | 0.32           |
| Soricut et al (2015)      | Skip Gram + Morphology          | 0.41           |
| Cui et al (2015)          | Skip Gram + LCS-Relation Matrix | 0.37           |
| Bhatia et al (2016)       | VAREMBED                        | 0.24           |
| Bojanowski et al (2016)   | Subword Information Skip Gram   | 0.48           |
| Sun et al (2016)          | BEING                           | 0.50           |
| Pilehvar et al (2017)     | Inducing Embeddings             | 0.43           |
| Wang et al (2017)         | Function (Ent.)                 | 0.37           |
| Wang et al (2017)         | Baseline (Joint)                | 0.35           |
| Barkan (2017)             | Bayesian Skip-Gram              | 0.52           |
| Athiwaratkun et al (2017) | w2gm/me                         | 0.35           |
| Cocos et al (2017)        | Text5                           | 0.36           |
| Sanu et al (2017)         | FOFE+SVD                        | 0.50           |

## References 

* **Bayesian Neural Word Embedding** (AAAI'17), O Barkan et al. [[pdf](https://pdfs.semanticscholar.org/2333/2a035751a2ba468f42501ce55753b6c07079.pdf?_ga=2.114343303.1439917160.1511745511-1361082864.1510655493)]
* **Enriching Word Vectors with Subword Information** (TACL'17), P Bojanowski et al. [[pdf](https://pdfs.semanticscholar.org/ca48/cae4ce00055dce2bca328f1ea2bc09ddc069.pdf?_ga=2.46740647.1439917160.1511745511-1361082864.1510655493)]
* **Multimodal Word Distributions** (ACL'17), B Athiwaratkun et al. [[pdf](https://pdfs.semanticscholar.org/9fa7/947a2e5b701c18a38a0a5e240c442db1ba90.pdf?_ga=2.43553573.1439917160.1511745511-1361082864.1510655493)]
* **The Language of Place: Semantic Value from Geospatial Context** (EACL'17), A Cocos et al. [[pdf](https://pdfs.semanticscholar.org/bd14/3f6fe886ddc137783864ee42fef8927571d0.pdf?_ga=2.148936118.1439917160.1511745511-1361082864.1510655493)]
* **Word Embeddings based on Fixed-Size Ordinally Forgetting Encoding** (EMNLP'17), J Sanu et al. [[pdf](https://pdfs.semanticscholar.org/3c6c/e537d53a16ef321210ae0055d808ce70594a.pdf?_ga=2.39359907.1439917160.1511745511-1361082864.1510655493)]
* **Inducing Embeddings for Rare and Unseen Words by Leveraging Lexical Resources** (EACL'17), MT Pilehvar et al. [[pdf](https://pdfs.semanticscholar.org/d939/7470d8499b98a272e1f7e7458e6e64952f3a.pdf?_ga=2.39493027.1439917160.1511745511-1361082864.1510655493)]
* **Integrating Semantic Knowledge into Lexical Embeddings Based on Information Content Measurement** (EACL'17), HY Wang et al. [[pdf](https://pdfs.semanticscholar.org/400a/bca3aac8663b60b3901aefac45cde9b466aa.pdf?_ga=2.109838085.1439917160.1511745511-1361082864.1510655493)]
* **Morphological Priors for Probabilistic Neural Word Embeddings** (EMNLP'16), P Bhatia et al. [[pdf](https://pdfs.semanticscholar.org/4f95/42c8a1df0eb4170347a488966ce9a81b7888.pdf?_ga=2.13351095.1439917160.1511745511-1361082864.1510655493)]
* **Inside Out: Two Jointly Predictive Models for Word Representations and Phrase Representations** (AAAI'16), F Sun et al. [[pdf](https://pdfs.semanticscholar.org/4df7/2c80eb59eae40133838cb967c709f1879939.pdf?_ga=2.42646693.1439917160.1511745511-1361082864.1510655493)]
* **KNET: A General Framework for Learning Word Embedding Using Morphological Knowledge** (TOIS'15), Q Cui et al. [[pdf](https://www.cc.gatech.edu/~hdai8/pdf/CuiGaoBiaQiuetal15.pdf)]
* **Unsupervised Morphology Induction Using Word Embeddings** (HLT-NAACL'15), R Soricut et al. [[pdf](https://pdfs.semanticscholar.org/f165/09bd147fd63ec1e295af9b2e18e1897e49bc.pdf?_ga=2.10040501.1439917160.1511745511-1361082864.1510655493)]
* **Compositional Morphology for Word Representations and Language Modelling** (ICML'14), J Botha et al. [[pdf](https://pdfs.semanticscholar.org/8047/7a905fd007b4d6e1320068250d7004e0eda9.pdf?_ga=2.155844027.1439917160.1511745511-1361082864.1510655493)]
* **Co-learning of Word Representations and Morpheme Representations** (COLING'14), S Qiu et al. [[pdf](https://pdfs.semanticscholar.org/750f/26d613d3bda4ce043944aa3ef358b0c5de68.pdf?_ga=2.39435043.1439917160.1511745511-1361082864.1510655493)]
* **Better Word Representations with Recursive Neural Networks for Morphology** (CoNLL'13), MT Luong et al. [[pdf](https://pdfs.semanticscholar.org/8047/1217ac67ad3b74719dd1fa3216ca481a08a2.pdf?_ga=2.118120201.1439917160.1511745511-1361082864.1510655493)]

**See Also**

* [☶ Representation (State of The Art)](https://github.com/magizbox/underthesea/wiki/English-NLP-SOTA#representation)