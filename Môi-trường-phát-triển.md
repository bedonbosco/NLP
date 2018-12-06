Bài viết này mô tả môi trường phát triển khi phát triển các module của underthesea, mình nghĩ nó cũng khá hữu ích nếu các bạn muốn phát triển các ứng dụng học máy và AI.

## Thiết bị

Cấu hình tối thiểu:

* CPU: Core i5
* RAM: 8 GB
* Ổ cứng: HDD 500 GB

Cấu hình đề nghị

* CPU: Core i7
* RAM: 16 GB
* Ổ cứng: SDD 256 GB
* GPU

CPU tốt giúp chương trình của bạn load nhanh, quá trình huấn luyện và tiền xử lý dữ liệu của bạn cũng diễn ra nhanh hơn.

Ram tối thiểu 8 GB giúp bạn có thể chạy hệ điều hành, IDE mượt mà. Ram càng cao, bạn càng đỡ gặp vấn đề khi đối mặt với các bộ dữ liệu "to"

Ổ cứng SDD giúp quá trình đọc, ghi dữ liệu nhanh hơn, ảnh hưởng đến quá trình tiền xử lý dữ liệu, save và load mô hình.

Việc sắm ít nhất một GPU là một điều cần thiết (với các mô hình ensemble như XGBoost, Catboost), và là một điều bắt buộc khi bạn phát triển một chương trình deep learning. Tất nhiên, bạn có thể không cần GPU, nếu bạn sẵn sàng chờ chương trình chạy 3 tiếng thay vì 5 phút!

## Hệ điều hành

Điều đầu tiên: Hãy nói lời tạm biệt với Windows! Rất nhiều framework, các chương trình không hỗ trợ Windows. 

Ubuntu 16.04 vẫn là một sự lựa chọn hoàn hảo tại thời điểm viết bài.

## Môi trường phát triển

Python + Anaconda: Bộ đôi hoàn hảo

Hãy chắc chắn là bạn sử dụng python 3.6. Và biết các tạo, activate, cài đặt các gói qua pip và conda.