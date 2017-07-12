Welcome to the underthesea wiki!

# Sentiment Analysis

[VietSentiWordNet](https://github.com/magizbox/underthesea/wiki/VietSentiWordNet)


## Tools

### Diacritics restoration

* [Vietnamese diacritics restoration tool](https://github.com/kanjirz50/restore-tonemark), [demonstration](http://160.16.58.116/vietnamese/tone). This tool is based on a point-wise diacritics restoration.

### Word segmentation

* [DongDu](https://github.com/rockkhuya/DongDu) by DongDu. DongDu is a fastest and high accuracy word segmentation tool based on SVMs.
* [vnTokenizer](http://vlsp.hpda.vn:8080/demo/?page=resources) vnTokenizer provides Java interface.

### Part-of-Speech tagging

**Tools**

* [vnTagger](http://vlsp.hpda.vn:8080/demo/?page=resources) This tool provides Java interface.
* [viet-morphological-analysis-svm](https://github.com/kanjirz50/viet-morphological-analysis-svm), [demonstration](http://160.16.58.116/vietnamese/morph). Vietnamese joint word segmentation and Part-of-Speech tagging based on SVM. This tool provides Python interface.
* [viet-morphological-analysis-crf(https://github.com/kanjirz50/viet-morphological-analysis-crf), [demonstration](http://160.16.58.116/vietnamese/morph_crf). Vietnamese joint word segmentation and Part-of-Speech tagging based on CRF This tool provides Python interface.


### Other Tools

#### Vitk -- a Vietnamese text processing toolkit
[Github](https://github.com/phuonglh/vn.vitk)

This toolkit is for large data processing, includes word segmentation, part-of-sppech tagging, dependency parsing.


## Resources
### Treebank
Vietnamese treebank

[website](http://vlsp.hpda.vn:8080/demo/?page=resources)

### Corpus
#### VNESEcopus.txt
[website](http://vlsp.hpda.vn:8080/demo/?page=resources)

650 thousand sentences.

#### VNTQcorpus(small).txt
[website](http://viet.jnlp.org/download-du-lieu-tu-vung-corpus)

300 thousand sentences.

#### VNTQcorpus(big).txt
[website](http://viet.jnlp.org/download-du-lieu-tu-vung-corpus)

1.75 million sentences.

### Bilingual Corpus
#### English-Vietnamese bilingual corpus
[website](http://vlsp.hpda.vn:8080/demo/?page=resources)


## Technique
### Unicode normalization
NFC is a one of the unicode normalization form.
It is suitable for Vietnamese text preprocessing.

### Syllable normalization

## Articles
- Tuan Anh Luu and Kazuhide Yamamoto. A Point-wise Approach for Vietnamese Diacritics Restoration. Proceedings of the International Conference on Asian Language Processing (IALP 2012), pp.189-192 (2012.11)