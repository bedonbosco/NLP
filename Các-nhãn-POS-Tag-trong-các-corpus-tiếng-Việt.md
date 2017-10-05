Tài liệu này có mục đích liệt kê và nêu ra ý nghĩa của các nhãn POS Tag trong các corpus tiếng Việt. Sau đó đưa ra ánh xạ chung và chuẩn hóa các nhãn POS Tag.

| Tag  | UTS | UD    | C   | Tiếng anh                 | Ý nghĩa           | Ví dụ                             |
|------|-----|-------|-----|---------------------------|-------------------|-----------------------------------|
| A    |     | ADJ   | 1   | Adjective                 | Tính từ           | nhiều, hơn, khác, gần, lớn        |
| Ab   | A   |       | 2   |                           | Tính từ mượn      | sexy, Peace, đờmi                 |
| B    | FW  |       | 1   | Borrow                    | Từ mượn           | karaoke, nilông, fax, oxy         |
| C    |     | CCONJ | 1   | Coordinating Conjunction  | Liên từ           | thì, nhưng, như, mà               |
| Cc   |     | SCONJ | 2   | Subordinating conjunction | Liên từ đẳng lập  | và, hay, hoặc, cùng               |
| CH   |     | PUNCT | 1,2 | Chunk                     | Dấu câu           | ,, ., ", ..., “, ”                |
| E    |     | ADP   | 1,2 | Adposition                | Giới từ           | của, trong, với, ở, cho,          |
| Fw   | FW  |       | 2   | Foreign Word              | Từ nước ngoài     | Eleocharis, karaoke, Internationa |
| FW   |     |       | 2   | Foreign Word              | Từ nước ngoài     | photo, knock-out, chat            |
| I    |     | INTJ  | 1,2 | Interjection              | Thán từ           | ơi, ạ, Ôi, à, Vâng                |
| L    |     | DET   | 1,2 | Determiner                | Định từ           | những, các, mấy, mọi, một số      |
| M    |     | NUM   | 1,2 | Numeral                   | Số từ             | một, hai, ba, Một, triệu, 1       |
| N    |     | NOUN  | 1,2 | Noun                      | Danh từ           | người, khi, nhà, năm, ngày        |
| Nb   |     |       | 2   |                           | Danh từ mượn      | tivi, két, casino, golf, bar      |
| Nc   |     | NOUN  | 1,2 | Noun Category             | Danh từ chỉ loại  | con, cái, chiếc, ngôi             |
| Ne   |     |       | 2   |                           |                   | bọn, bộ, đoàn, tụi                |
| Ni   | Np  |       | 2   |                           | Danh từ kí hiệu   | A5, 1A, A4, B, A, 2032TS          |
| Np   |     | NOUN  | 1,2 | Proper Noun               | Danh từ riêng     |                                   |
| NNP  | Np  |       | 2   |                           |                   | VN, Nguyễn, Văn                   |
| NNPY | Np  |       | 2   |                           |                   | IMB                               |
| NPP  | Np  |       | 2   |                           |                   | Tôn Đản, Gò, Mả                   |
| Ns   | Nc  |       | 2   |                           |                   | ông, anh, người, chị,             |
| Nu   |     | NOUN  | 1,2 | Noun Unit                 | Danh từ đơn vị    | đồng, m, tuổi, ha                 |
| Ny   |     |       | 1,2 |                           | Danh từ viết tắt  | VN, TP, UBND, SV, ĐL              |
| P    |     | PROPN | 1,2 | Pronoun                   | Đại từ            | này, tôi, đó, mình, đây           |
| R    |     | X     | 1,2 |                           | Phó từ (Trạng từ) | không, đã, cũng, lại              |
| S    | Z   |       | 1   |                           |                   | phó, trưởng, nguyên, Phó          |
| T    |     | PART  | 1,2 | Particle                  | Trợ từ            | cả, ngay, chính, đến              |
| V    |     | VERB  | 1,2 | Verb                      | Động từ           | có, là, được, đi, làm             |
| Vb   | V   |       | 2   |                           | Động từ mượn      | photo, knock-out, chat, bye       |
| Vy   |     |       | 1,2 |                           | Động từ viết tắt  | XKLĐ, PCCC, QLTT                  |
| X    |     |       | 1,2 |                           | Không phân loại   | như vậy, làm sao, nhất là         |
| Y    | Np  |       | 1   |                           |                   |                                   |
| Z    |     |       | 2   |                           | Yếu tố cấu tạo từ | phó, viên, bất, siêu, tái, tổng   |

Chú thích:

* `b`: borrow: Từ mượn
* `y`: Viết tắt

Corpus:

* `[1]`: VietTreeBank
* `[2]`: VLSP2016-NER