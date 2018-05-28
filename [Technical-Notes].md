### Word Embeddings

**Word Embeddings là gì?**

Word Embeddings là một phương pháp biểu diễn từ (hay tổng quát hơn, các đối tượng trong từ điển) thành vector.

**Có những phương pháp word embeddings nào?**

Cùng với sự phát triển mạnh mẽ của deep learning, nhiều phương pháp word embeddings ra đời như `word2vec` ([Tomas Mikolov et al., NIPS 2013](https://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf)), `GloVe` ([Jeffrey Pennington et al., EMNLP 2014](https://pdfs.semanticscholar.org/1baa/3f4fda7c92600a5c192adaed80a834d13ff9.pdf?_ga=2.125811018.1992130065.1527492614-471416995.1523351844)), `RAND-WALK` ([Sanjeev Arora et al., 2015](https://pdfs.semanticscholar.org/5be3/cec621dbe5bfd88352c293727334cf35e372.pdf?_ga=2.113546567.1992130065.1527492614-471416995.1523351844)), `fastText` ([Bag of Tricks for Efficient Text Classification et al., EACL 2017](https://pdfs.semanticscholar.org/ba05/67e9548d7d27edf25c66bf25ccfaa6307851.pdf?_ga=2.46053476.1992130065.1527492614-471416995.1523351844)), `StarSpace` ([Ledell Yu Wu et al., AAAI 2018]) và các phương pháp khác.

Trong đó, fastText gây ấn tượng bằng việc cung cấp một thư viện huấn luyện cực kì nhanh. Các corpus khoảng 100000 văn bản chỉ cần huấn luyện trong vòng vài giây. word2vec được cho là phương pháp tiên phong, trong các báo cáo về sử dụng deep learning cho văn bản, thường sử dụng các embedded vector cho các từ được huấn luyện bởi word2vec trong các input layer.

Tham khảo

* [Beyond word2vec: GloVe, fastText, StarSpace. Konstantinos Perifanos. pydata 2018](https://code.google.com/archive/p/word2vec/)

### word2vec

word2vec là một phương pháp biểu diễn từ thành vector, được tác giả Tomas Mikolov và cộng sự giới thiệu trong báo cáo [Distributed Representations of Words and Phrases and their Compositionality](http://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf) tại hội nghị NIPS năm 2013.

Hai thuật toán để học mô hình word2vec là continous bag-of-words (CBOW) và continous skip-gram. Tư tưởng chính của skip-gram là từ một từ dự đoán ngữ cảnh của từ đó.

word2vec đưa ra các phương pháp để cải thiện hiệu năng của hệ thống như negative sampling, hierarchical softmax, async SGD.

Tham khảo

* [https://code.google.com/archive/p/word2vec/](https://code.google.com/archive/p/word2vec/)

### fastText

fastText là một thuật toán mở rộng từ word2vec, được tác giả Armand Joulin và cộng sự giới thiệu trong báo cáo [Bag of Tricks for Efficient Text Classification](https://arxiv.org/abs/1607.01759) vào năm 2016.

1. Sự khác biệt giữa fastText và word2vec?

> word2vec coi các từ trong corpus như một phần tử độc lập và sinh ra một vector cho mỗi từ. 

Trong khi đó,

> fastText coi mỗi từ là một tập hợp các các ký tự ngrams. Nên một vector của một từ là tổng của các ký tự n grams của nó.

Ví dụ, vector cho từ "apple" là tổng của các vector của các n-gram "<ap", "app", "apple", "apple", "apple>", "ppl", "pple", "pple>", "ple", "ple>", "le>" (giả sử cấu hình cho ngrams min là 3 và nagrams max là 6).

Tham khảo:

* [https://www.quora.com/What-is-the-main-difference-between-word2vec-and-fastText](https://www.quora.com/What-is-the-main-difference-between-word2vec-and-fastText)