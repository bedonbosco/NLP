SNLI Corpus (Bowman 2015)

The SNLI corpus (Bowman 2015) is a collection of 570k human-written English sentence pairs manually labeled for balanced classification with the labels entailment, contradiction, and neutral, supporting the task of natural language inference (NLI), also known as recognizing textual entailment (RTE). We aim for it to serve both as a benchmark for evaluating representational systems for text, especially including those induced by representation learning methods, as well as a resource for developing NLP models of any kind.


## Dataset

Stanford Natural Language Inference (SNLI) corpus is a collection of sentence pairs labeled for entailment, contradiction, and semantic independence. At 570,152 sentence pairs, SNLI is two orders of magnitude larger than all other resources of its type. And, in contrast to many such resources, all of its sentences and labels were written by humans in a grounded, naturalistic context. In a separate validation phase, we collected four additional judgments for each label for 56,941 of the examples. Of these, 98% of cases emerge with a threeannotator consensus, and 58% see a unanimous consensus from all five annotators.


## Results

| References              | Model                                      | Test Accuracy (%) |
|-------------------------|--------------------------------------------|-------------------|
| Bowman et al (2015)     | LSTM                                       | 80.6              |
| Bowman et al (2016)     | SPINN-PI                                   | 83.2              |
| Conneau et al (2017)    | BiLSTM-Max                                 | 83.9              |
| Lai et al (2017)        | LSTM + CPR                                 | 78.2              |
| Chen et al (2017)       | HIM (600D ESIM + 300D Syntactic tree-LSTM) | 88.6              |
| Nie et al (2017)        | Shortcut-Stacked Encoder                   | 86.1              |
| Chen et al (2017)       | Gated-Att BiLSTM                           | 85.5              |
| Min et al (2017)        | BiDAF                                      | 83.20             |
| Munkhdalai et al (2017) | NSE                                        | 84.6              |
| Munkhdalai et al (2017) | NTI                                        | 83.4              |


## References 

* **Supervised Learning of Universal Sentence Representations from Natural Language Inference Data** (EMNLP'17), A Conneau et al. [[pdf](https://pdfs.semanticscholar.org/ccb4/2d732b94a2d9ad942cad22107389591fc980.pdf?_ga=2.198254639.1229478610.1512832600-1361082864.1510655493)]
* **Learning to Predict Denotational Probabilities For Modeling Entailment** (EACL'17), A Lai et al. [[pdf](https://pdfs.semanticscholar.org/1468/d174aa49ec091d92c4709c48f24d65927f93.pdf?_ga=2.134889969.1229478610.1512832600-1361082864.1510655493)]
* **Enhanced LSTM for Natural Language Inference** (ACL'17), Q Chen et al. [[pdf](https://pdfs.semanticscholar.org/9b84/3ea293e72d83c14a7a6ee8165037a9cc484a.pdf?_ga=2.234423454.1229478610.1512832600-1361082864.1510655493)]
* **Shortcut-Stacked Sentence Encoders for Multi-Domain Inference** (RepEval@EMNLP'17), Y Nie et al. [[pdf](https://pdfs.semanticscholar.org/a887/d1031398f01f0f01e9167567e8bc49537419.pdf?_ga=2.121203080.1229478610.1512832600-1361082864.1510655493)]
* **Recurrent Neural Network-Based Sentence Encoder with Gated Attention for Natural Language Inference** (RepEval@EMNLP'17), Q Chen et al. [[pdf](https://pdfs.semanticscholar.org/ceb7/dddbd0c51f511c4ba97d328b48fd10d2a7fc.pdf?_ga=2.221332632.1229478610.1512832600-1361082864.1510655493)]
* **Question Answering through Transfer Learning from Large Fine-grained Supervision Data** (ACL'17), S Min et al. [[pdf](https://pdfs.semanticscholar.org/dea0/9775b944e96d3099ae4c2e9187c97cb20090.pdf?_ga=2.226697373.1229478610.1512832600-1361082864.1510655493)]
* **Neural Semantic Encoders** (EACL'17),T Munkhdalai et al. [[pdf](https://arxiv.org/abs/1607.04315)]
* **A Fast Unified Model for Parsing and Sentence Understanding** (ACL'16), SR Bowman et al. [[pdf](https://arxiv.org/pdf/1603.06021.pdf)]
* **A large annotated corpus for learning natural language inference.** (EMNLP'15), SR Bowman et al. [[pdf](https://nlp.stanford.edu/pubs/snli_paper.pdf)]

**See Also**

* [☶ Textual Entailment (State of The Art)](https://github.com/magizbox/underthesea/wiki/English-NLP-SOTA#textual-entailment)