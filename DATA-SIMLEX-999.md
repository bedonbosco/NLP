SimLex-999 Dataset [(Hill 2014)](https://arxiv.org/pdf/1408.3456.pdf)

SimLex-999 is a gold standard resource for evaluating distributional semantic models that improves on existing resources in several important ways. this focus on similarity, SimLex-999 incentivizes the development of models with a different, and arguably wider range of applications than those which reflect conceptual association. SimLex-999 contains a range of concrete and abstract adjective, noun and verb pairs, together with an independent rating of concreteness and (free) association strength for each pair. This diversity enables fine-grained analyses of the performance of models on concepts of different types, and consequently greater insight into how architectures can be improved. 

## Dataset

[Download](https://www.cl.cam.ac.uk/~fh295/simlex.html)

SimLex-999 is structured to facilitate focused evaluations based around the following conceptual distinctions: 

* Concreteness: Each concept in each SimLex-999 pair is rated for its conceptual concreteness. Because abstract concepts are more common than concrete concepts in most everyday language ( and can behave quite differently in semantic models ), SimLex-999 contains a balanced selection of concrete ( dog, cup ) and abstract ( envy, deny ) concepts. 

* Part-Of-Speech: SimLex-999 comprises 666 Noun-Noun pairs, 222 Verb-Verb pairs and 111 Adjective-Adjective pairs. 

* Free-Association: SimLex-999 includes an independent empirical measure of the strength of association (or relatedness) between each of its pairs, taken from the University of South Florida Free Association Norms.

## Results

| References             | Method                                    | Spearman's rho |
|------------------------|-------------------------------------------|---------------|
| Collobert et al (2008) | Neural language model                     | 0.268         |
| Huang et al (2012)     | Neural language model with global context | 0.098         |
| Han et al (2013)       | UMBC                                      | 0.558         |
| Hill et al (2014)      | RNNenc                                    | 0.52          |
| Banjade et al (2015)   | SVR4                                      | 0.642         |
| Banjade et al (2015)   | ESA                                       | 0.271         |
| Banjade et al (2015)   | Lesk                                      | 0.404         |
| Schwartz et al (2015)  | SP+                                       | 0.52          |
| Schwartz et al (2015)  | joint(SP+, skip-gram)                     | 0.56          |
| Hill et al (2015)      | NMT embeddings (RNNenc)                   | 0.52           | 
| Faruqui et al (2015)   | Ling Dense                                | 0.58           |
| Wieting et al (2015)   | PARAGRAM                                  | 0.68           |
| Recski et al (2016)    | Embeddings+wordnet+4lang                  | 0.76           |
| Mrksic et al (2016)    | Annotator/gold standard agreement         | 0.78           |


## References 

* **Measuring semantic similarity of words using concept networks** (RepL4NLP'16), G Recski et al. [[pdf](http://aclweb.org/anthology/W/W16/W16-1622.pdf)]
* **Measuring semantic similarity of words using concept networks** (EMNLP'16), N Mrksic et al. [[pdf](https://arxiv.org/pdf/1603.00892.pdf)]
* **Lemon and Tea Are Not Similar: Measuring Word-to-Word Similarity by Combining Different Methods** (CICLing'15),  R Banjade et al. [[pdf](http://nobalniraula.com/papers/LemonTeaNotSimilar_CICLing_2015.pdf)]
* **Embedding Word Similarity with Neural Machine Translation.** (ICLR'15.), F Hill et al. [[pdf](https://arxiv.org/pdf/1412.6448.pdf)]
* **Non-Distributional Word Vector Representations.** (ACL'15), M Faruqui et al. [[pdf](http://www.aclweb.org/anthology/P15-2076)]
* **From Paraphrase Database to Compositional Paraphrase Model and Back** (TACL'15), J Wieting et al. [[pdf](http://ttic.uchicago.edu/~wieting/wieting2015TACL.pdf)]
* **Symmetric Pattern Based Word Embeddings for Improved Word Similarity Prediction** (CoNLL'15), R Schwartz et al. [[pdf](http://www.aclweb.org/anthology/K15-1026)]
* **Not All Neural Embeddings are Born Equal** (NIPS'14), F Hill et al. [[pdf](https://arxiv.org/pdf/1410.0718.pdf)]
* **SimLex-999: Evaluating Semantic Models With (Genuine) Similarity Estimation** (ACL'14), F Hill et al. [[pdf](https://arxiv.org/pdf/1408.3456.pdf)]
* **UMBC EBIQUITY-CORE: Semantic Textual Similarity Systems** (SEM'13), L Han et al. [[pdf](http://cs.jhu.edu/~jonny/pub/674.pdf)]
* **Improving Word Representations via Global Context and Multiple Word Prototypes** (ACL'12), EH Huang et al. [[pdf](http://www.aclweb.org/anthology/P12-1092)]
* **A unified architecture for natural language pro- cessing: Deep neural networks with multitask learning** (ICML'08), R Collobert et al. [[pdf](https://ronan.collobert.com/pub/matos/2008_nlp_icml.pdf)]


**See Also**

* [☶ Representation (State of The Art)](https://github.com/magizbox/underthesea/wiki/English-NLP-SOTA#representation)]