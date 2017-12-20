**Multi30K  dataset (Elliott 2017)**

Multi30K (Elliott 2017) is an extension of the Flickr30K dataset (Young 2014) with 31,014 German translations of English descriptions and 155,070 independently collected German descriptions. The translations were collected from professionally contracted translators, whereas the descriptions were collected from untrained crowdworkers. The key difference between these corpora is the relationship between the sentences in different languages. In the translated corpus, we know there is a strong correspondence between the sentences in both languages. In the descriptions corpus, we only know that the sentences, regardless of the language, are supposed to describe the same image.


## Dataset

The Flickr30K Dataset contains 31,014 images sourced from online photo-sharing websites (Young 2014). Each image is paired with five English descriptions, which were collected from Amazon Mechanical Turk2 . The dataset contains 145,000 training, 5,070 development, and 5,000 test descriptions. The Multi30K dataset extends the Flickr30K dataset with translated and independent German sentences.


## Results

| References             | Model          | TER Score |
|------------------------|----------------|-----------|
| Calixto et al (2017)   | PBSMT          | 54.9      |
| Calixto et al (2017)   | NMT            | 55.5      |
| Calixto et al (2017)   | NMT(SRC+IMG)   | 43.7      |
| Delbrouck et al (2017) | Soft attention | 42.8      |

## References 

* **Using Images to Improve Machine-Translating E-Commerce Product Listings** (EACL'17), I Calixto et al. [[pdf](https://pdfs.semanticscholar.org/bb9e/02ad5e907a7f0c619b33904f28ec4075a020.pdf?_ga=2.189508779.1229478610.1512832600-1361082864.1510655493)]
* **Doubly-Attentive Decoder for Multi-modal Neural Machine Translation** (ACL'17),  I Calixto et al. [[pdf](https://pdfs.semanticscholar.org/b4a4/4316624d00b4b7298ecbb38d5d40b1f8a5a2.pdf?_ga=2.20472888.1229478610.1512832600-1361082864.1510655493)]
* **An empirical study on the effectiveness of images in Multimodal Neural Machine Translation** (EMNLP'17), JB Delbrouck et al. [[pdf](https://pdfs.semanticscholar.org/e9c3/d6d2dc07a9868bb39ad67c386156a028ed2b.pdf?_ga=2.221923352.1229478610.1512832600-1361082864.1510655493)]
* **Multi30K: Multilingual English-German Image Descriptions** (VL@ACL'16), D Elliott et al. [[pdf](http://aclweb.org/anthology/W16-3210.pdf)]

**See Also**

* [☶ Machine Translation (State of The Art)](https://github.com/magizbox/underthesea/wiki/English-NLP-SOTA#machine-translation)