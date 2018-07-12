# OntoNotes

The OntoNotes project has created a large-scale corpus of accurate and integrated annotation of multiple layers of syntactic, semantic and discourse information in text. The English language portion comprises roughly 1.7M words and Chinese language portion comprises roughly 1M words of newswire, magazine articles, broadcast news, broadcast conversations, web data and conversational speech data . The Arabic portion is smaller, comprising 300K words of newswire articles. This rich, integrated annotation covering many layers aims at facilitating the development of richer, cross-layer models and enabling better automatic semantic analysis. The corpus is tagged with syntactic trees, propositions for most verb and some noun instances, partial verb and noun word senses, coreference, and named entities. 

## Dataset

Coverage for each layer in the OntoNotes v5.0 corpus, by number of documents, words, and some other attributes. The numbers in parenthesis are the total number of parts in the documents.

<table>
  <tr>
    <th rowspan="2">Language</th>
    <th colspan="2">Parse</th>
    <th colspan="3">Proposition</th>
    <th colspan="3">Sense</th>
    <th colspan="2">Name</th>
    <th colspan="2">Coreference</th>
  </tr>
  <tr>
    <td>Documents</td>
    <td>Words</td>
    <td>Documents</td>
    <td>Verb Prop.</td>
    <td>Noun Prop.</td>
    <td>Documents</td>
    <td>Verb Sense</td>
    <td>Noun Sense</td>
    <td>Documents</td>
    <td>Words</td>
    <td>Documents</td>
    <td>Words</td>
  </tr>
  <tr>
    <td>English</td>
    <td>7969</td>
    <td>2.6M</td>
    <td>6124</td>
    <td>300K</td>
    <td>18K</td>
    <td>12K</td>
    <td>173K</td>
    <td>120J</td>
    <td>3637</td>
    <td>2.0M</td>
    <td>2384</td>
    <td>1.7M</td>
  </tr>
  <tr>
    <td>Chinese</td>
    <td>2002</td>
    <td>1.0M</td>
    <td>1861</td>
    <td>148K</td>
    <td>7K</td>
    <td>1573</td>
    <td>83K</td>
    <td>1K</td>
    <td>1911</td>
    <td>988K</td>
    <td>1729</td>
    <td>950K</td>
  </tr>
  <tr>
    <td>Arabic</td>
    <td>599</td>
    <td>402K</td>
    <td>599</td>
    <td>30K</td>
    <td>-</td>
    <td>310</td>
    <td>4.3K</td>
    <td>8.7K</td>
    <td>446</td>
    <td>298K</td>
    <td>447</td>
    <td>300K</td>
  </tr>
</table>

## References

* :scroll: [OntoNotes on SRL paper (Pradhan et al. CoNLL'13)](http://www.aclweb.org/anthology/W13-3516)
* :file_folder: [OntoNotes v12 release](https://github.com/ontonotes/conll-formatted-ontonotes-5.0/releases/tag/v12)
* :link: [OntoNotes on SRL Website](http://cemantix.org/data/ontonotes.html)

## Leaderboard

<table>
<tr>
<td><b>Date</b></td>
<td><b>Model</b></td>
<td><b>F1</b></td>
<td><b>Code</b></td>
</tr>
<tr>
<td><code>Mar 22, 2018</code></td>
<td>He et al. (2017) + ELMo<br/>
<i>Allen Institute for Artificial Intelligence</i><br/>
<code><a href='http://aclweb.org/anthology/P17-1044'>Peters et al. NAACL'18</a></code>
</td>
<td>84.6</td>
<td><a href=''></a></td>
</tr>
<tr>
<td><code>Jul 30, 2017</code></td>
<td>He et al. (2017)<br/>
<i>FAIR & Allen Institute for Artificial Intelligence</i><br/>
<code><a href=''>He et al. ACL'17</a></code>
</td>
<td>81.7</td>
<td><a href='https://github.com/luheng/deep_srl'>Official</a></td>
</tr>

</table>

**See Also**

* [☶ Semantic Role Labeling (State of The Art)](https://github.com/magizbox/underthesea/wiki/English-NLP-SOTA#semantic-role-labeling)