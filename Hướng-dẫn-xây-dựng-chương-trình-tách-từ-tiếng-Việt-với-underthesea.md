(đang hoàn thiện)

# Giới thiệu bài toán 

Bài toán tách từ là bài toán cơ bản của xử lý ngôn ngữ tự nhiên. Khi cho đầu vào là một câu 

"Chúng ta thường nói đến Rau sạch, Rau an toàn để phân biệt với các rau bình thường bán ngoài chợ"

Ta cần nhận diện và tách các từ

[u"Chúng ta", u"thường", u"nói", u"đến", u"Rau sạch", u",", u"Rau", u"an toàn", u"để", u"phân biệt", u"với",
u"các", u"rau", u"bình thường", u"bán", u"ngoài", u"chợ", u"."]

# Chuẩn bị dữ liệu

Có nhiều cách để biểu diễn bài toán tách từ. `underthesea` sử dụng định dạng CoNLL format. Mỗi một câu được biểu diễn thành

```
Chúng BW
ta IW
thường BW
nói BW
đến BW
Rau BW
sạch IW
```

