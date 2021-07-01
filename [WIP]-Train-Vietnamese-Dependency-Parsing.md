### Training Data

VLSP 2020 Dataset

Train: 8151 sentences, Test: 1122 sentences

### Models Description

![download](https://user-images.githubusercontent.com/1780281/124057936-99f3d780-da52-11eb-844b-821c555186ec.png)

**Input vectors**

The ![](https://latex.codecogs.com/gif.latex?ith) input vector is composed of two parts: the word embedding and the CharLSTM word representation vector of ![](https://latex.codecogs.com/gif.latex?w_i)

![](http://mathurl.com/render.cgi?e_i%20%3D%20emb%28w_i%29%20%5Coplus%20CharLSTM%28w_i%29%5Cnocache)

**Biaffine Attention Mechanism**

Compute the score of a dependency ![](https://latex.codecogs.com/gif.latex?i%20%5Cto%20j) via biaffine attention:

![](https://latex.codecogs.com/gif.latex?s%28i%2C%20j%29%20%3D%20%5Cbegin%7Bbmatrix%7D%20r_j%5Em%20%5C%5C%201%20%5Cend%7Bbmatrix%7D%5E%7BT%7D%20W%5E%7Bbiaffine%7D%20r_i%5Eh)

**Parameter settings**

Model parameters

<table>
<tr>
<th></th>
<th>Component</th>
<th>Hyper-Parameter</th>
<th>Value</th>
</tr>
<tr>
<td>Embedding</td>
<td>BERT</td>
<td>
n_bert_layers<br/>
dimension
</td>
<td>
4<br/>
768
</td>
</tr>
<tr>
<td>LSTM</td>
<td>Encoder</td>
<td>
n_lstm_hidden<br/>
n_lstm_layers<br/>
lstm_dropout
</td>
<td>
400<br/>
3<br/>
0.33
</td>
</tr>
</table>

Training Parameters

<table>
<tr>
<th>Hyper-Parameter</th>
<th>Value</th>
</tr>
<tr>
<td>optimizer</td>
<td>Adam</td>
</tr>
</table>

Choose batch_size (5000) right help us alots

### Notes

* Using wandb logs is very handful. We can easily watch logs, loss graph with nearly zero setup