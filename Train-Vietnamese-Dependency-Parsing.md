### Training Data

VLSP 2020 Dataset

Train: 8151 sentences, Test: 1122 sentences

### Models Description

![download](https://user-images.githubusercontent.com/1780281/124057936-99f3d780-da52-11eb-844b-821c555186ec.png)

**Input vectors**

The *i*th input vector is composed of two parts: the word embedding and the CharLSTM word representation vector of w_i

![](http://mathurl.com/render.cgi?e_i%20%3D%20emb%28w_i%29%20%5Coplus%20CharLSTM%28w_i%29%5Cnocache)

Our models:



Choose batch_size (5000) right help us alots

Using wandb logs is very handful. We can easily watch logs, loss graph with nearly zero setup