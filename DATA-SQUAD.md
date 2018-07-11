SQuAD Corpus (Rajpurkar 2016)

Stanford Question Answering Dataset (Rajpurkar 2016) is a new reading comprehension dataset, consisting of questions posed by crowdworkers on a set of Wikipedia articles, where the answer to every question is a segment of text, or span, from the corresponding reading passage.

## Dataset

Stanford Question Answering Dataset contains 107,785 questions and 23,215 passages coming from 536 Wikipedia articles. The data was randomly partitioned into a training set (80%), a development set (10%) and an unreleased test set (10%). Rajpurkar et al. (2016) build a leaderboard to evaluate and publish results on the test set. 

<table>
<tr>
<td><b style="color:red">Date</b></td>
<td><b>Model</b></td>
<td><b>EM</b></td>
<td><b>F1</b></td>
</tr>
<tr>
<td>
</td>
<td>
Human Performance<br/>
<i>Stanford University</i><br/>
<small><a href="http://arxiv.org/abs/1606.05250">(Rajpurkar et al. '16)</a></small>
</td>
<td>82.304</td>
<td>91.221</td>
</tr>
<tr>
<td>
<code>Jun 20, 2018</code>
</td>
<td style="text-align: center;">
<center>
MARS (ensemble)<br/>
<small><i>YUANFUDAO research NLP</i></small><br/>
<small><a href="http://arxiv.org/abs/1606.05250">(Rajpurkar et al. '16)</a></small>
</center>
</td>
<td><b>83.982</b></td>
<td><b>89.796</b></td>
</tr>
</table>

`abc`

## SQuAD1.1 Leaderboard

| References               | Model                      | F1 (%) |
|--------------------------|----------------------------|--------|
| Xie et al (2017)         | CCNN (ensemble)            | 82.6   |
| Golub et al (2017)       | BIDAF                      | 52.2   |
| Wiese et al (2017)       | Neural Domain Adaptation   | 8.1    |
| Weissenborn et al (2017) | FastQAExt                  | 78.9   |
| Raiman et al (2017)      | Globally Normalized Reader | 76.21  |
| Wang et al (2017)        | R-NET                      | 82.9   |
| Liu et al (2017)         | SEDT-LSTM                  | 80.84  |
| Chen et al (2017)        | DrQA                       | 79.0   |


## References 

* **A Constituent-Centric Neural Architecture for Reading Comprehension** (ACL'17), P Xie et al. [[pdf](https://pdfs.semanticscholar.org/6044/3b601f50e8934319dff7803ca81a275499c0.pdf?_ga=2.255339464.1368387525.1513004549-1361082864.1510655493)]
* **Two-Stage Synthesis Networks for Transfer Learning in Machine Comprehension** (EMNLP'17), D Golub et al. [[pdf](https://pdfs.semanticscholar.org/598d/8d69ba0cba5831f54f1af7066f18dc3af760.pdf?_ga=2.255339464.1368387525.1513004549-1361082864.1510655493)]
* **Neural Domain Adaptation for Biomedical Question Answering** (ConLL'17), G Wiese et al. [[pdf](https://pdfs.semanticscholar.org/4c16/a6fd7b4aad8c1331e4753b30701fdf6d12f4.pdf?_ga=2.221769304.1368387525.1513004549-1361082864.1510655493)]
* **Making Neural QA as Simple as Possible but not Simpler** (CoNLL'17), D Weissenborn et al. [[pdf](https://pdfs.semanticscholar.org/e460/0ece1f09236d082eca4537ee9c1efe687f6c.pdf?_ga=2.254747208.1368387525.1513004549-1361082864.1510655493)]
* **Globally Normalized Reader** (EMNLP'17), J Raiman et al. [[pdf](https://pdfs.semanticscholar.org/6c8d/50492748f50681b19ce1c6652f4f3efda289.pdf?_ga=2.53765096.1368387525.1513004549-1361082864.1510655493)]
* **Gated Self-Matching Networks for Reading Comprehension and Question Answering** (ACL'17), W Wang et al. [[pdf](https://pdfs.semanticscholar.org/b798/cfd967e1a9ca5e7bc995d33a907bf65d1c7f.pdf?_ga=2.217858902.1368387525.1513004549-1361082864.1510655493)]
* **Structural Embedding of Syntactic Trees for Machine Comprehension** (EMNLP'17), R Liu et al. [[pdf](https://pdfs.semanticscholar.org/583d/56e59f722873fb3729f890761dd870bb3b11.pdf?_ga=2.213380692.1368387525.1513004549-1361082864.1510655493)]
* **Reading Wikipedia to Answer Open-Domain Questions** (ACL'17), D Chen et al. [[pdf](https://pdfs.semanticscholar.org/d83a/682015e6f47e26ff216d47520d5e54edbfd9.pdf?_ga=2.216819542.1368387525.1513004549-1361082864.1510655493)]
* **SQuAD: 100,000+ Questions for Machine Comprehension of Text** (EMNLP'16), P Rajpurkar et al. [[pdf](https://arxiv.org/pdf/1606.05250.pdf)]

**See Also**

* [☶ Question Answering (State of The Art)](https://github.com/magizbox/underthesea/wiki/English-NLP-SOTA#question-answering)