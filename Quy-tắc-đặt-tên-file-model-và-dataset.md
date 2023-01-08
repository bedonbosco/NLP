# 1. Đặt tên file model 

Đề xuất đặt tên theo `task-id_model-name_timestamp`

Ví dụ:

* `wt_crf_2018_05_06.tar.gz`
* `tc_naive-bayes_2019_03_03.tar.gz`

Danh sách các task id 

task | id | chú thích
-- | -- | --
sent_tokenize | st |
word_tokenize | wt |
pos_tag | pos |
chunk | chunk | 
ner | ner | 
classify | tc | text classify
sentiment | se

# 2. Đặt tên file dataset 

Các quy tắc đặt tên file dataset 

* Ưu tiên sử dụng tên gốc của dataset 

```
Ví dụ: VietTreeBank, VNTC
```

* Thêm task tương ứng của dataset

```
Ví dụ:
- Task NER: VLSP2016_NER, 
- Task SA: VLSP2016_SA_RESTAURANT
```

* Lưu ý: Sử dụng ký tự `_` (không phải `-` để tách các thành phần trong folder của dataset)

```
Ví dụ:
- Nên: VLSP2016_NER, VLSP2016_SA_RESTAURANT
- Không nên: VLSP2016-NER, VLSP2016-SA-RESTAURANT
```

Các dataset hiện tại

* `CP_Vietnamese_VLC_v2_2022`

# Ghi chú 

Tham khảo 

* Data versioning in machine learning projects - Dmitry Petrov. https://www.youtube.com/watch?v=BneW7jgB298

Tham khảo cách đặt tên của các model ở dự án repo [tensorflow/models](https://github.com/tensorflow/models)


Model | TF-Slim File | Checkpoint | Top-1 Accuracy | Top-5 Accuracy
-- | -- | -- | -- | --
Inception V1 | Code | inception_v1_2016_08_28.tar.gz | 69.8 | 89.6
Inception V2 | Code | inception_v2_2016_08_28.tar.gz | 73.9 | 91.8
Inception V3 | Code | inception_v3_2016_08_28.tar.gz | 78.0 | 93.9
Inception V4 | Code | inception_v4_2016_09_09.tar.gz