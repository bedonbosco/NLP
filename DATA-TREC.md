[TREC question dataset](http://cogcomp.org/Data/QA/QC/)

Task involves classifying a question into 6 question types (whether the question is about person, location, numeric information, etc.) (Li and Roth, 2002)

## Datasets

5952 sentences. Data are collected from four sources: 4,500 English questions published by USC (Hovy et al., 2001),
about 500 manually constructed questions for a few rare classes, 894 TREC 8 and TREC 9 questions,
and also 500 questions from TREC 10 which serves as our test set.

6 coarse classes (ABBREVIATION, ENTITY, DESCRIPTION, HUMAN, LOCATION and NUMERIC VALUE) and 50 fine classes

## Results

| References           | Model  | Accuracy (%) |
|----------------------|--------|--------------|
| Li et al (2002)      | HIER   | 91.0         |
| Blunsom et al (2006) | MAXENT | 92.6         |
| Huang et al (2008)   | MAXENT | 93.6         |
| Silva et al (2011)   | SVM    | 95.0         |

**See Also**

* [☶ Text Classification (State of The Art)](https://github.com/magizbox/underthesea/wiki/English-NLP-SOTA#text-classification)
