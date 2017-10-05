Tài liệu này có mục đích liệt kê và nêu ra ý nghĩa của các nhãn chunking trong các corpus tiếng Việt. Sau đó đưa ra ánh xạ chung và chuẩn hóa các nhãn chunking.

| Tag   | UTS  | C   | Tiếng anh            | Ý nghĩa             | Ví dụ                |
|-------|------|-----|----------------------|---------------------|----------------------|
| B-AP  |      | 1,2 | Adjective Phrase     | Cụm tính từ         |                      |
| B-IP  | O    | 2   |                      | Cụm thán từ         | ơi, nhé, à, ạ        |
| B-MP  | O    | 2   |                      |                     |                      |
| B-NP  |      | 1,2 | Noun Phrase          | Cụm danh từ         |                      |
| B-NPb | B-NP | 2   |                      |                     |                      |
| B-PP  |      | 1,2 | Prepositional Phrase | Cụm giới từ         | của, trong, với, cho |
| B-QP  | B-NP | 1   | Quantifier Phrase    | Cụm từ chỉ số lượng |                      |
| B-RP  | O    | 1   |                      |                     |                      |
| B-VP  |      | 1,2 | Verb Phrase          | Cụm động từ         |                      |
| B-VPb | B-VP | 2   |                      |                     |                      |
| I-AP  |      | 1,2 |                      |                     |                      |
| I-NP  |      | 1,2 |                      |                     |                      |
| I-PP  | B-PP | 1   |                      |                     |                      |
| I-QP  | I-NP | 1   |                      |                     |                      |
| I-RP  | O    | 2   |                      |                     |                      |
| I-VP  |      | 1,2 |                      |                     |                      |
| O     |      | 1,2 |                      |                     |                      |

Chú thích:


Chú thích:

* `b`: borrow: Từ mượn
* `y`: Viết tắt

Corpus:

* `[1]`: VietTreeBank
* `[2]`: VLSP2016-NER

# Tài liệu tham khảo

* **Báo cáo kỹ thuật SP8.4: Xây Dựng Bộ Xác Định Nhóm Cụm Từ Tiếng Việt** (2009), L. Nguyen [[pdf](http://www.jaist.ac.jp/~bao/VLSP-text/Mar2009/SP84_baocaokythuat2009thang3.pdf)]