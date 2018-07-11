# SQuAD Dataset

Stanford Question Answering Dataset (Rajpurkar 2016) is a new reading comprehension dataset, consisting of questions posed by crowdworkers on a set of Wikipedia articles, where the answer to every question is a segment of text, or span, from the corresponding reading passage.

## Dataset

Stanford Question Answering Dataset contains 107,785 questions and 23,215 passages coming from 536 Wikipedia articles. The data was randomly partitioned into a training set (80%), a development set (10%) and an unreleased test set (10%). Rajpurkar et al. (2016) build a leaderboard to evaluate and publish results on the test set. 

## References

* :scroll: [SQuAD2.0 paper (Rajpurkar & Jia et al. '18)](https://arxiv.org/abs/1806.03822)
* :scroll: [SQuAD1.0 paper (Rajpurkar et al. '16)](http://arxiv.org/abs/1606.05250)
* :file_folder: [Training Set v2.0 (40 MB)](https://rajpurkar.github.io/SQuAD-explorer/dataset/train-v2.0.json)
* :file_folder: [Dev Set v2.0 (4 MB)](https://rajpurkar.github.io/SQuAD-explorer/dataset/dev-v2.0.json)
* :link: [SQuAD Website](https://rajpurkar.github.io/SQuAD-explorer/)
* :link: [Evaluation Script v2.0](https://worksheets.codalab.org/rest/bundles/0x6b567e1cf2e041ec80d7098f031c5c9e/contents/blob/)
* :link: [Sample Prediction File (on Dev v2.0)](https://worksheets.codalab.org/bundles/0x8731effab84f41b7b874a070e40f61e2/)

## SQuAD1.1 Leaderboard


<table>
<tr>
<td><b>Date</b></td>
<td><b>Model</b></td>
<td><b>EM</b></td>
<td><b>F1</b></td>
</tr>

<tr>
<td></td>
<td>Human Performance<br/>
<i>Stanford University</i><br/>
<code><a href="http://arxiv.org/abs/1606.05250">(Rajpurkar et al. '16)</a></code>
</td>
<td>82.304</td>
<td>91.221</td>
</tr>

<tr>
<td><code>Jun 20, 2018</code></td>
<td>MARS (ensemble)<br/>
<i>YUANFUDAO research NLP</i><br/>
<code><a href="https://arxiv.org/pdf/1803.00191.pdf">(Wang et al. '18)</a></code>
</td>
<td><b>83.982</b></td>
<td><b>89.796</b></td>
</tr>

<tr>
<td><code>Mar 19, 2018</code></td>
<td>QANet (ensemble)<br/>
<i>Google Brain & CMU</i><br/>
<code><a href="https://arxiv.org/abs/1804.09541">(Yu et al. ICLR'18)</a></code>
</td>
<td>83.877</td>
<td>89.737</td>
</tr>

<tr>
<td><code>Nov 17, 2017</code></td>
<td>BiDAF + Self Attention + ELMo (ensemble)<br/>
<i>Allen Institute for Artificial Intelligence</i><br/>
<code><a href="https://arxiv.org/abs/1802.05365">(Peters, et al. NAACL'18)</a></code>
</td>
<td>81.003</td>
<td>87.432</td>
</tr>

<tr>
<td><code>Dec 05, 2017</code></td>
<td>SAN (ensemble model)<br/>
<i>Microsoft Business AI Solutions Team</i><br/>
<code><a href="https://arxiv.org/abs/1712.03556">(Liu  et al. ACL'18)</a></code>
</td>
<td>79.608</td>
<td>86.496</td>
</tr>

<tr>
<td><code>Dec 28, 2016</code></td>
<td>FastQAExt<br/>
<i>German Research Center for Artificial Intelligence</i><br/>
<code><a href="https://arxiv.org/abs/1703.04816">(Weissenborn  et al. ConLL'17)</a></code>
</td>
<td>70.849</td>
<td>78.857</td>
</tr>
</table>

**See Also**

* [☶ Question Answering (State of The Art)](https://github.com/magizbox/underthesea/wiki/English-NLP-SOTA#question-answering)