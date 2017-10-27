[TREC question dataset](http://cogcomp.org/Data/QA/QC/)

Task involves classifying a question into 6 question types (whether the question is about person, location, numeric information, etc.) (Li and Roth, 2002)

## Datasets

Data are collected from four sources: 4,500 English questions published by USC (Hovy et al., 2001),
about 500 manually constructed questions for a few rare classes, 894 TREC 8 and TREC 9 questions,
and also 500 questions from TREC 10 which serves as our test set.

6 coarse classes (ABBREVIATION, ENTITY, DESCRIPTION, HUMAN, LOCATION and NUMERIC VALUE) and 50 fine classes

## Results

| Method                        | Model                              | WSJ-PTB * |
|-------------------------------|------------------------------------|--------------------------------|
| (Gimenez and Marquez, 2004)   | SVM with manual feature pattern    | 97.16                          |
| (Collobert et al., 2011)      | MLP with word embeddings + CRF     | 97.29                          |
| (Santos and Zadrozny, 2014)   | MLP with character+word embeddings | 97.32                          |
| (Huang et al., 2015)          | LSTM                               | 97.29                          |
| (Huang et al., 2015)          | Bidirectional LSTM                 | 97.40                          |
| (Huang et al., 2015)          | LSTM-CRF                           | 97.54                          |
| (Huang et al., 2015)          | Bidirectional LSTM-CRF             | 97.55                          |
| (Kumar et al., 2015)          | DMN                                | 97.56                          |

*: per-token accuracy %

**See Also**

* [☶ Text Classification (State of The Art)](https://github.com/magizbox/underthesea/wiki/English-NLP-SOTA#text-classification)
