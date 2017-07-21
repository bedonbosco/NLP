# Awesome Vietnamese NLP Resources ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)

### Table of Content

* [**Spelling Correction**](#spelling-correction)
* [**Word segmentation**](#word-segmentation)
* [**Part-of-Speech tagging**](#part-of-speech-tagging)
* [**Chunking**](#chunking)
* [**Dependency Parsing**](#dependency-parsing)
* [**Text Classification**](#text-classification)
* [**Automatic Summarization**](#automatic-summarization)
* [**Sentiment Analysis**](#sentiment-analysis)
* [**Named Entity Recognition**](#named-entity-recognition)
* [**Semantic Role Labelling**](#semantic-role-labelling)
* [**Machine Translation**](#machine-translation)
* [**Representation**](#representation)
* [**Term Definition Vectors**](#term-definition-vectors)
* [**Resources**](#resources)
* [**Website**](#website)
* [**Technique**](#technique)

### Spelling Correction

**Tools**

* [lebinh/vietnamese-accent-model](https://github.com/lebinh/vietnamese-accent-model) - a simple deep learning model to add accent to Vietnamese text *by Le Binh (2016)* `python` 
* [Vietnamese diacritics restoration tool](https://github.com/kanjirz50/restore-tonemark), [demonstration](http://160.16.58.116/vietnamese/tone) - based on a point-wise diacritics restoration *by Kanji Takahashi (2016)* `python`
* [ngthanhtrung/visc](https://github.com/ngthanhtrung/visc) - Vietnamese spelling correction (ViSC) tool *by Trung Nguyen (2016)* `java`

**Publications**

* Tuan Anh Luu and Kazuhide Yamamoto. A Point-wise Approach for Vietnamese Diacritics Restoration. Proceedings of the International Conference on Asian Language Processing (IALP 2012), pp.189-192 (2012.11)

### Word segmentation

* [UETsegmenter](https://github.com/phongnt570/UETsegmenter) - a toolkit for Vietnamese word segmentation *by Nguyen Tuan Phong (2016)* `java`
* [Vitk](https://github.com/phuonglh/vn.vitk) - toolkit is for large data processing, includes word segmentation, part-of-speech tagging, dependency parsing *by Le Hong Phuong (2016)* `java`
* [pyvi](https://pypi.python.org/pypi/pyvi) - easy to do tokenizing/pos-tagging Vietnamese *by Tran Viet Trung (2016)* `python`
* [vTools](https://github.com/lupanh/vTools) - a simple Vietnamese word segmentation program *by Tran Mai Vu, Le Duc Trong (2015)* `python`
* [manhtai/vietseg](https://github.com/manhtai/vietseg) - Vietnamese NLP toolkit: Tokenizer, Sentence detector, POS tagger, Phrase chunker *by Manh Tai (2015)* `python`
* [DongDu](https://github.com/rockkhuya/DongDu) - a fastest and high accuracy word segmentation tool *by Luu Tuan Anh (2014)* `C++`
* [Roy_VnTokenizer](https://github.com/roy-a/Roy_VnTokenizer) - Vietnamese tokenizer (Maximum Matching and CRF) *by Anindya Roy (2014)* `python`
* [vnTokenizer](http://vlsp.hpda.vn:8080/demo/?page=resources) -  an automatic tokenizer for segmenting Vietnamese texts into lexical units *by Le Hong Phuong (2008)* `java`

### Part-of-Speech tagging

**Tools**

* [pyvi](https://pypi.python.org/pypi/pyvi) - easy to do tokenizing/pos-tagging Vietnamese *by Tran Viet Trung (2016)* `python`
* [Vitk](https://github.com/phuonglh/vn.vitk) - toolkit is for large data processing, includes word segmentation, part-of-sppech tagging, dependency parsing *by Le Hong Phuong (2016)* `java`
* [viet-morphological-analysis-svm](https://github.com/kanjirz50/viet-morphological-analysis-svm), [demonstration](http://160.16.58.116/vietnamese/morph) - Vietnamese joint word segmentation and Part-of-Speech tagging based on SVM *by Kanji Takahashi (2016)* `python` 
* [viet-morphological-analysis-crf](https://github.com/kanjirz50/viet-morphological-analysis-crf), [demonstration](http://160.16.58.116/vietnamese/morph_crf) - Vietnamese joint word segmentation and Part-of-Speech tagging based on CRF *by Kanji Takahashi (2016)* `python`
* [vTools](https://github.com/lupanh/vTools) - Vietnamese NLP toolkit: Tokenizer, Sentence detector, POS tagger, Phrase chunker *by Tran Mai Vu, Le Duc Trong (2015)* `python`
* [RDRPOSTagger](http://rdrpostagger.sourceforge.net/) - a rule-based part-of-speech and morphological tagging toolkit *by  Dat Quoc Nguyen, Dai Quoc Nguyen, Dang Duc Pham, Son Bao Pham (2013-2017)* `python`
* [vnTagger](http://vlsp.hpda.vn:8080/demo/?page=resources) - an automatic part-of-speech tagger for tagging Vietnamese texts *by Le Hong Phuong (2010)* `java`

### Chunking

* [vTools](https://github.com/lupanh/vTools) - Vietnamese NLP toolkit: Tokenizer, Sentence detector, POS tagger, Phrase chunker *by Tran Mai Vu, Le Duc Trong (2015)* `python`
* [VietChunker](https://vlsp.hpda.vn/demo/?page=resources) - chunking tool based on CRF *by VLSP (2010)* `java`

### Dependency Parsing

* [jPTDP](https://github.com/datquocnguyen/jPTDP) - a novel neural network model for joint POS tagging and graph-based dependency parsing *by Dat Quoc Nguyen, Dai Quoc Nguyen (2017)* `java`
* [Vitk](https://github.com/phuonglh/vn.vitk) - toolkit is for large data processing, includes word segmentation, part-of-sppech tagging, dependency parsing *by Le Hong Phuong (2016)* `java`
* [VnDP](http://vndp.sourceforge.net/) - a Vietnamese dependency parsing toolkit *by Dat Quoc Nguyen, Dai Quoc Nguyen (2014)* `java`

### Text Classification

* [duyvuleo/VNTC](https://github.com/duyvuleo/VNTC) - a large-scale Vietnamese news text classification corpus *by Vu Hoang Cong Duy (2017)* `resource`

### Automatic Summarization

* [lupanh/VietnameseMDS](https://github.com/lupanh/VietnameseMDS) - 200 Cụm văn bản tiếng Việt dùng cho tóm tắt đa văn bản *by Tran Mai Vu (2013)* `resource` 

### Sentiment Analysis

* [polyglot](http://polyglot.readthedocs.io/en/latest/Sentiment.html) - a natural language pipeline that supports massive multilingual applications *by polyglot (2014-2017)* `c++,java,python`
* [pyurgent](https://github.com/tiendung/pyurgent) - life-long learning for sentiment analysis, supporting Vietnamese and English *by Alex Nguyen (2016)* `python,corpus`
* [VietSentiWordNet](https://github.com/magizbox/underthesea/wiki/VietSentiWordNet) - SentiwordNet dictionary for Vietnamese *by sonvxcoltech (2014)* `corpus`

### Named Entity Recognition

* [ntson2002/lstm-crf-tagging](https://github.com/ntson2002/lstm-crf-tagging) - nested named entity recognition using multilayer recurrent neural networks *by Son Nguyen (2017)* `python`
* [polyglot](http://polyglot.readthedocs.io/en/latest/NamedEntityRecognition.html) - a natural language pipeline that supports massive multilingual applications *by polyglot (2014-2017)* `c++,java,python`
* [Vitk.NER](https://github.com/phuonglh/ai.vitk.ner) - Vietnamese Named Entity Recognition *by Le Hong Phuong (Jul 2017)* `scala,java`

### Semantic Role Labelling

* [pth1993/vnSRL](https://github.com/pth1993/vnSRL) - tool for Vietnamese Semantic Role Labelling Task *by Pham Thai Hoang (2016)* `python`

### Machine Translation

* [polyglot](http://polyglot.readthedocs.io/en/latest/Transliteration.html) - a natural language pipeline that supports massive multilingual applications *by polyglot (2014-2017)* `c++,java,python`

### Representation

* [sonvx/word2vecVN](https://github.com/sonvx/word2vecVN) - Word2Vec model for Vietnamese *by Vu Xuan Son (2016)* `resource`

### Term Definition Vectors

* [WikTDV: Wiktionary-based Term Definition Vectors](https://github.com/dscarvalho/tdv) - an implementation of the Term Definition Vectors (TDV) method for language representation *by Danilo S. Carvalho, Minh Le Nguyen (Jul 2017)* `python`

### Resources

**Dictionary**

* [pclouds/words-vi](https://github.com/pclouds/words-vi) - Vietnamese vocabulary list *by Duy Nguyen (2017)* `resource`

**Treebank**

* [UniversalDependencies/UD_Vietnamese](https://github.com/UniversalDependencies/UD_Vietnamese) - Vietnamese Universal Dependency Treebank *by Nguyen Thi Luong, Ha My Linh, Le Hong Phuong, Nguyen Thi Minh Huyen (2017)* `python`
* [Vietnamese Treebank](http://vlsp.hpda.vn:8080/demo/?page=resources) *by VLSP (2010)* `corpus`

**Corpus**

* [VNESEcopus.txt](http://viet.jnlp.org/download-du-lieu-tu-vung-corpus). 650 thousand sentences.
* [VNTQcorpus(small).txt](http://viet.jnlp.org/download-du-lieu-tu-vung-corpus). 300 thousand sentences.
* [VNTQcorpus(big).txt](http://viet.jnlp.org/download-du-lieu-tu-vung-corpus). 1.75 million sentences.

**Bilingual Corpus**

* [English-Vietnamese bilingual corpus](http://vlsp.hpda.vn:8080/demo/?page=resources) *by VLSP (2010)* `corpus`

### Website

* [VLSP](http://vlsp.org.vn/)
* [Facebook: Cộng đồng xử lý ngôn ngữ tự nhiên](https://www.facebook.com/groups/vietnlp/)
* [Xử lý tiếng Việt Wiki](http://xltiengviet.wikia.com/wiki/X%E1%BB%AD_l%C3%BD_ti%E1%BA%BFng_Vi%E1%BB%87t_Wiki)
* [Vietnamese NLP tools, resources and techniques related on Vietnamese](https://github.com/kanjirz50/vnlp-outline)

### Technique

**Unicode normalization**

NFC is a one of the unicode normalization form.
It is suitable for Vietnamese text preprocessing.