# Awesome Vietnamese NLP Resources ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)

## Table of Content

* [**Diacritics restoration**](#diacritics-restoration)
* [**Word segmentation**](#word-segmentation)
* [**Part-of-Speech tagging**](#part-of-speech-tagging)
* [**Sentiment Analysis**](#sentiment-analysis)
* [**Term Definition Vectors**](#term-definition-vectors)
* [**Name Entity Recognition**](#name-entity-recognition)
* [**Resources**](#resources)
* [**Technique**](#technique)

### Diacritics restoration

**Tools**

* [Vietnamese diacritics restoration tool](https://github.com/kanjirz50/restore-tonemark), [demonstration](http://160.16.58.116/vietnamese/tone). This tool is based on a point-wise diacritics restoration.

**Publications**

1. Tuan Anh Luu and Kazuhide Yamamoto. A Point-wise Approach for Vietnamese Diacritics Restoration. Proceedings of the International Conference on Asian Language Processing (IALP 2012), pp.189-192 (2012.11)

### Word segmentation

1. [DongDu](https://github.com/rockkhuya/DongDu) by DongDu. DongDu is a fastest and high accuracy word segmentation tool based on SVM (Nov 2014)
2. [vnTokenizer](http://vlsp.hpda.vn:8080/demo/?page=resources) vnTokenizer provides Java interface.

### Part-of-Speech tagging

**Tools**

* [vnTagger](http://vlsp.hpda.vn:8080/demo/?page=resources) - an automatic part-of-speech tagger for tagging Vietnamese texts
* [viet-morphological-analysis-svm](https://github.com/kanjirz50/viet-morphological-analysis-svm), [demonstration](http://160.16.58.116/vietnamese/morph). Vietnamese joint word segmentation and Part-of-Speech tagging based on SVM. This tool provides Python interface.
* [viet-morphological-analysis-crf](https://github.com/kanjirz50/viet-morphological-analysis-crf), [demonstration](http://160.16.58.116/vietnamese/morph_crf). Vietnamese joint word segmentation and Part-of-Speech tagging based on CRF This tool provides Python interface.
* [Vitk](https://github.com/phuonglh/vn.vitk). This toolkit is for large data processing, includes word segmentation, part-of-sppech tagging, dependency parsing.

## Sentiment Analysis

* [VietSentiWordNet](https://github.com/magizbox/underthesea/wiki/VietSentiWordNet) - SentiwordNet dictionary for Vietnamese

## Term Definition Vectors

* [WikTDV: Wiktionary-based Term Definition Vectors](https://github.com/dscarvalho/tdv) - an implementation of the Term Definition Vectors (TDV) method for language representation by Danilo S. Carvalho, Minh Le Nguyen (Jul 2017)

## Named Entity Recognition

* [Vitk.NER](https://github.com/phuonglh/ai.vitk.ner) - Vietnamese Named Entity Recognition by Le Hong Phuong (Jul 2017)

## Resources

**Treebank**

* [Vietnamese treebank](http://vlsp.hpda.vn:8080/demo/?page=resources)

**Corpus**

* [VNESEcopus.txt](http://vlsp.hpda.vn:8080/demo/?page=resources). 650 thousand sentences.
* [VNTQcorpus(small).txt](http://viet.jnlp.org/download-du-lieu-tu-vung-corpus). 300 thousand sentences.
* [VNTQcorpus(big).txt](http://viet.jnlp.org/download-du-lieu-tu-vung-corpus). 1.75 million sentences.

**Bilingual Corpus**

* [English-Vietnamese bilingual corpus](http://vlsp.hpda.vn:8080/demo/?page=resources)


## Technique

### Unicode normalization
NFC is a one of the unicode normalization form.
It is suitable for Vietnamese text preprocessing.