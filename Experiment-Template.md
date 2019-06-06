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

* egs	Viết tắt của example scripts, mỗi một thư mục con trong egs, là một thử nghiệm với một mô hình trên một tập dữ liệu
  * [example_id]	Tên của thử nghiệm
    * data	Chứa dữ liệu cho thử nghiệm
    * train.py	"usage: train.py [-h] --train TRAIN -s SERIALIZATION_DIR

optional arguments:
  -h, --help            show this help message and exit
  --train TRAIN         train data path
  -s SERIALIZATION_DIR, --serialization-dir SERIALIZATION_DIR
                        directory in which to save the model and its logs"
    evaluate.py	

* report	
* tmp	
* util	
* README.md	
* ner.py	
* requirements.txt	
* .gitignore	

### Phụ lục

Phiên bản 

| Người viết        | Vũ Anh     |
|-------------------|------------|
| Phiên bản         | 1.2.0-alpha|
| Cập nhật lần cuối | 06/06/2019 |

Danh sách thay đổi 

<table>
<tr>
<th>Phiên bản</th>
<th>Thời gian</th>
<th>Người cập nhật</th>
<th>Thay đổi</th>
</tr>
<tr>
<td>1.2.0-alpha</td>
<td>06/06/2019</td>
<td>Vũ Anh</td>
<td>Cập nhật repo theo cấu trúc của flair</td>
</tr>
</table>