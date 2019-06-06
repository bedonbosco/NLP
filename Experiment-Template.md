Tài liệu này chứa mẫu dự án cho các thử nghiệm của nhóm underthesea

## Cấu trúc repo 

* Description: Tên tiếng Anh (ví dụ: Vietnamese Automatic Speech Recognition)
* Topic: vietnamese,nlp,vietnamese-nlp,[topic]

## Cấu trúc file README

* [title]: tiếng việt
* badges: made with love, opensource vietnamese, contributions welcome
* Lời giới thiệu	
* Nhóm tác giả	
* Tham gia đóng góp	
* Mục lục
* Yêu cầu hệ thống
* Thiết lập môi trường
* Hướng dẫn sử dụng
  * Sử dụng mô hình đã huấn luyện
  * Huấn luyện mô hình
* Kết quả thử nghiệm
* Trích dẫn
* Bản quyền
* Kết quả thử nghiệm	

## Cấu trúc thư mục

* `egs`: Viết tắt của example scripts, mỗi một thư mục con trong egs, là một thử nghiệm với một mô hình trên một tập dữ liệu
  * `[example_id]`: Tên của thử nghiệm
    * `data`: Chứa dữ liệu cho thử nghiệm
    * `train.py`
    * `evaluate.py`
* `report`
* `tmp`
* `util`
* `README.md`
* `ner.py`	
* `requirements.txt`
* `.gitignore`

**Tham số của train.py**

```
usage: train.py [-h] --train TRAIN -s SERIALIZATION_DIR

optional arguments:
  -h, --help            show this help message and exit
  --train TRAIN         train data path
  -s SERIALIZATION_DIR, --serialization-dir SERIALIZATION_DIR
                        directory in which to save the model and its logs
```

### Phụ lục

Phiên bản 

| Người viết        | Vũ Anh     |
|-------------------|------------|
| Phiên bản         | 1.2.0-alpha|
| Cập nhật lần cuối | 06/06/2019 |

Danh sách thay đổi 

<table>
<tr>
<td>Phiên bản</td>
<td>Thời gian</td>
<td>Người cập nhật</td>
<td>Thay đổi</td>
</tr>
<tr>
<td>1.2.0-alpha</td>
<td>06/06/2019</td>
<td>Vũ Anh</td>
<td>Cập nhật repo theo cấu trúc của flair</td>
</tr>
<tr>
<td>1.1.0</td>
<td></td>
<td>Vũ Anh</td>
<td>Thay đổi cấu trúc thư mục theo flair<br>- Xóa thư mục data</td>
</tr>
<tr>
<td>1.0.2</td>
<td></td>
<td>Vũ Anh</td>
<td>train.py option<br> (<a href="https://allenai.github.io/allennlp-docs/api/allennlp.commands.train.html">example</a>)</td>
</tr>
<tr>
<td>1.0.1</td>
<td></td>
<td>Vũ Anh</td>
<td>Có thư mục egs<br> (<a href="https://github.com/undertheseanlp/classification/tree/master/egs">example</a>)</td>
</tr>
<tr>
<td>1.0.0</td>
<td></td>
<td>Vũ Anh</td>
<td>Có thư mục data</td>
</tr>
</table>