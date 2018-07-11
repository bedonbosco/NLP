# SNLI Corpus

The SNLI corpus (Bowman 2015) is a collection of 570k human-written English sentence pairs manually labeled for balanced classification with the labels entailment, contradiction, and neutral, supporting the task of natural language inference (NLI), also known as recognizing textual entailment (RTE). We aim for it to serve both as a benchmark for evaluating representational systems for text, especially including those induced by representation learning methods, as well as a resource for developing NLP models of any kind.


## Dataset

Stanford Natural Language Inference (SNLI) corpus is a collection of sentence pairs labeled for entailment, contradiction, and semantic independence. At 570,152 sentence pairs, SNLI is two orders of magnitude larger than all other resources of its type. And, in contrast to many such resources, all of its sentences and labels were written by humans in a grounded, naturalistic context. In a separate validation phase, we collected four additional judgments for each label for 56,941 of the examples. Of these, 98% of cases emerge with a threeannotator consensus, and 58% see a unanimous consensus from all five annotators.

## References

* :scroll: [SNLI paper (Bowman et al. EMNLP'15)](https://nlp.stanford.edu/pubs/snli_paper.pdf)
* :file_folder: [SNLI v1.0 (zip, ~100MB)](https://nlp.stanford.edu/projects/snli/snli_1.0.zip)
* :link: [SNLI Website](https://nlp.stanford.edu/projects/snli/)

## Leaderboard

<table>
<tr>
<td><b>Date</b></td>
<td><b>Model</b></td>
<td><b>Train<br/>(% acc)</b></td>
<td><b>Test<br/>(% acc)</b></td>
</tr>
<tr>
<td><code>May 29, 2018</code></td>
<td>Densely-Connected Recurrent and Co-Attentive <br/> Network (Ensemble)<br/>
<i>Naver Corporation</i><br/>
<code><a href='http://arxiv.org/abs/1606.05250'>Kim et al. '18</a></code>
</td>
<td>95.0</td>
<td>90.1</td>
</tr>
<tr>
<td><code>Jun 11, 2018</code></td>
<td>Fine-Tuned LM-Pretrained Transformer<br/>
<i>OpenAI</i><br/>
<code><a href='https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf'>Radford et al. '18</a></code>
</td>
<td>96.6</td>
<td>89.9</td>
</tr>
<tr>
<td><code>Dec 30, 2017</code></td>
<td>300D CAFE (Ensemble)<br/>
<i>Nanyang Technological</i><br/>
<code><a href='https://arxiv.org/pdf/1801.00102.pdf'>Tay et al. '17</a></code>
</td>
<td>92.5</td>
<td>89.3</td>
</tr>
<tr>
<td><code>Mar 22, 2018</code></td>
<td>ESIM + ELMo (Ensemble)<br/>
<i>Allen Institute for Artificial Intelligence</i><br/>
<code><a href='https://arxiv.org/pdf/1801.00102.pdf'>Peters et al. NAACL'18</a></code>
</td>
<td>92.1</td>
<td>89.3</td>
</tr>
<tr>
<td><code>Feb 15, 2018</code></td>
<td>450D DR-BiLSTM Ensemble<br/>
<i>Oregon State University</i><br/>
<code><a href='https://arxiv.org/pdf/1802.05577.pdf'>Ghaeini et al. NAACL-HLT'18</a></code>
</td>
<td>94.8</td>
<td>89.3</td>
</tr>
<tr>
<td><code>May 29, 2018</code></td>
<td>Densely-Connected Recurrent and Co-Attentive <br/> Network<br/>
<i>Naver Corporation</i><br/>
<code><a href='http://arxiv.org/abs/1606.05250'>Kim et al. '18</a></code>
</td>
<td>93.1</td>
<td>88.9</td>
</tr>
<tr>
<td><code>May 26, 2018</code></td>
<td>448D Densely Interactive Inference Network (DIIN) Ensemble<br/>
<i>New York University</i><br/>
<code><a href='https://arxiv.org/pdf/1709.04348.pdf'>Yichen Gong et al. ICLR'18</a></code>
</td>
<td>92.3</td>
<td>88.9</td>
</tr>
<tr>
<td><code>Aug 4, 2017</code></td>
<td>KIM<br/>
<i>University of Science and Technology of China</i><br/>
<code><a href='https://pdfs.semanticscholar.org/ceb7/dddbd0c51f511c4ba97d328b48fd10d2a7fc.pdf?_ga=2.221332632.1229478610.1512832600-1361082864.1510655493'>Chen et al. RepEval@EMNLP'17</a></code>
</td>
<td>94.1</td>
<td>88.6</td>
</tr>
<tr>
<td><code>Aug 4, 2017</code></td>
<td>KIM Ensemble<br/>
<i>University of Science and Technology of China</i><br/>
<code><a href='https://pdfs.semanticscholar.org/ceb7/dddbd0c51f511c4ba97d328b48fd10d2a7fc.pdf?_ga=2.221332632.1229478610.1512832600-1361082864.1510655493'>Chen et al. RepEval@EMNLP'17</a></code>
</td>
<td>94.1</td>
<td>88.6</td>
</tr>
<tr>
<td><code>Feb 15, 2018</code></td>
<td>450D DR-BiLSTM<br/>
<i>Oregon State University</i><br/>
<code><a href='https://arxiv.org/pdf/1802.05577.pdf'>Ghaeini et al. NAACL-HLT'18</a></code>
</td>
<td>94.1</td>
<td>88.5</td>
</tr>
<tr>
<td><code>May 26, 2018</code></td>
<td>448D Densely Interactive Inference Network (DIIN)<br/>
<i>New York University</i><br/>
<code><a href='https://arxiv.org/pdf/1709.04348.pdf'>Yichen Gong et al. ICLR'18</a></code>
</td>
<td>91.2</td>
<td>88.0</td>
</tr>
<tr>
<td><code>Nov 28, 2017</code></td>
<td>600D Residual stacked encoders<br/>
<i>UNC Chapel Hill</i><br/>
<code><a href='https://arxiv.org/pdf/1708.02312.pdf'>Nie and Bansal RepEval@EMNLP'17</a></code>
</td>
<td>91.0</td>
<td>86.0</td>
</tr>
<tr>
<td><code>Nov 28, 2017</code></td>
<td>300D Residual stacked encoders<br/>
<i>UNC Chapel Hill</i><br/>
<code><a href='https://arxiv.org/pdf/1708.02312.pdf'>Nie and Bansal RepEval@EMNLP'17</a></code>
</td>
<td>89.8</td>
<td>85.7</td>
</tr>
<tr>
<td><code>Aug 4, 2017</code></td>
<td>600D (300+300) Deep Gated Attn. BiLSTM encoders<br/>
<i>University of Science and Technology of China</i><br/>
<code><a href='https://pdfs.semanticscholar.org/ceb7/dddbd0c51f511c4ba97d328b48fd10d2a7fc.pdf?_ga=2.221332632.1229478610.1512832600-1361082864.1510655493'>Chen et al. RepEval@EMNLP'17</a></code>
</td>
<td>90.5</td>
<td>85.5</td>
</tr>
<tr>
<td><code>Sep 20, 2016</code></td>
<td>Gated-Att BiLSTM<br/>
<i>University of Science and Technology of China</i><br/>
<code><a href='https://pdfs.semanticscholar.org/9b84/3ea293e72d83c14a7a6ee8165037a9cc484a.pdf?_ga=2.234423454.1229478610.1512832600-1361082864.1510655493'>Chen et al. ACL'17</a></code>
</td>
<td></td>
<td>85.5</td>
</tr>
<tr>
<td><code>Jul 14,  2016</code></td>
<td>300D MMA-NSE encoders with attention<br/>
<i>University of Massachusetts</i><br/>
<code><a href='https://arxiv.org/abs/1607.04315'>Munkhdalai et al. EACL'17</a></code>
</td>
<td>86.9</td>
<td>85.4</td>
</tr>
<tr>
<td><code>Jul 14,  2016</code></td>
<td>300D NSE encoders<br/>
<i>University of Massachusetts</i><br/>
<code><a href='https://arxiv.org/abs/1607.04315'>Munkhdalai et al. EACL'17</a></code>
</td>
<td>86.2</td>
<td>84.6</td>
</tr>
<tr>
<td><code>May 9, 2017</code></td>
<td>4096D BiLSTM with max-pooling<br/>
<i>Facebook AI Research</i><br/>
<code><a href='https://arxiv.org/pdf/1705.02364.pdf'>Conneau et al. EMNLP'17</a></code>
</td>
<td>85.6</td>
<td>84.5</td>
</tr>
<tr>
<td><code>Mar 19, 2016</code></td>
<td>300D SPINN-PI encoders<br/>
<i>Stanford University</i><br/>
<code><a href='https://arxiv.org/abs/1603.06021'>Bowman et al. ACL'16</a></code>
</td>
<td>89.2</td>
<td>83.2</td>
</tr>
<tr>
<td><code>Sep 20,  2016</code></td>
<td>BiDAF<br/>
<i>University of Science and Technology of China</i><br/>
<code><a href='https://pdfs.semanticscholar.org/9b84/3ea293e72d83c14a7a6ee8165037a9cc484a.pdf?_ga=2.234423454.1229478610.1512832600-1361082864.1510655493'>Min et al. ACL'17</a></code>
</td>
<td></td>
<td>83.2</td>
</tr>
<tr>
<td><code>Mar 19, 2016</code></td>
<td>300D LSTM encoders<br/>
<i>Stanford University</i><br/>
<code><a href='https://arxiv.org/abs/1603.06021'>Bowman et al. ACL'16</a></code>
</td>
<td>83.9</td>
<td>80.6</td>
</tr>
<tr>
<td><code>Apr 3, 2017 </code></td>
<td>LSTM + CPR <br/>
<i>University of Illinois</i><br/>
<code><a href='https://pdfs.semanticscholar.org/1468/d174aa49ec091d92c4709c48f24d65927f93.pdf?_ga=2.134889969.1229478610.1512832600-1361082864.1510655493'>Lai et al. EACL'2017</a></code>
</td>
<td></td>
<td>78.2</td>
</tr>
<tr>
<td><code>Aug 21, 2015</code></td>
<td>Unlexicalized features + Unigram and bigram features<br/>
<i>Stanford University</i><br/>
<code><a href='https://arxiv.org/pdf/1508.05326.pdf'>Bowman et al. EMNLP'15</a></code>
</td>
<td>99.7</td>
<td>78.2</td>
</tr>
<tr>
<td><code>Aug 21, 2015</code></td>
<td>100D LSTM encoders<br/>
<i>Stanford University</i><br/>
<code><a href='https://arxiv.org/pdf/1508.05326.pdf'>Bowman et al. EMNLP'15</a></code>
</td>
<td>84.8</td>
<td>77.6</td>
</tr>
<tr>
<td><code>Aug 21, 2015</code></td>
<td>Unlexicalized features<br/>
<i>Stanford University</i><br/>
<code><a href=https://arxiv.org/pdf/1508.05326.pdf>Bowman et al. EMNLP'15</a></code>
</td>
<td>49.4</td>
<td>50.4</td>
</tr>

</table>

**See Also**

* [☶ Textual Entailment (State of The Art)](https://github.com/magizbox/underthesea/wiki/English-NLP-SOTA#textual-entailment)