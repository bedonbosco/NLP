Bài viết này mô tả môi trường phát triển khi phát triển các module của underthesea, mình nghĩ nó cũng khá hữu ích nếu các bạn muốn phát triển các ứng dụng học máy và AI.

## Thiết bị

<table>
<tr>
<th></td>
<th>Cấu hình tối thiểu</th>
<th>Cấu hình đề nghị</th>
</tr>
<tr>
<td>CPU</td>
<td>Intel® Core™ i5</td>
<td>Intel® Core™ i7</td>
</tr>
<tr>
<td>RAM</td>
<td>8 GB</td>
<td>16 GB</td>
</tr>
<tr>
<td>Ổ cứng</td>
<td>HDD 500 GB</td>
<td>SDD 256 GB</td>
</tr>
<tr>
<td>GPU</td>
<td></td>
<td>GTX 1070 Ti</td>
</tr>
</table>

CPU tốt giúp chương trình của bạn load nhanh, tăng tốc quá trình tiền xử lý dữ liệu và huấn luyện mô hình.

Ram tối thiểu 8 GB giúp bạn có thể chạy hệ điều hành, IDE mượt mà. Ram càng cao, bạn càng đỡ gặp vấn đề khi đối mặt với các bộ dữ liệu "to"

Ổ cứng SDD giúp quá trình đọc, ghi dữ liệu nhanh hơn, ảnh hưởng đến quá trình tiền xử lý dữ liệu, save và load mô hình.

Việc sắm ít nhất một GPU là một điều cần thiết (với các mô hình ensemble như XGBoost, Catboost), và là một **điều bắt buộc** khi bạn phát triển một chương trình deep learning. Tất nhiên, bạn có thể không cần GPU, nếu bạn sẵn sàng chờ chương trình chạy 3 tiếng thay vì 5 phút!

## Hệ điều hành

Điều đầu tiên: Hãy nói lời tạm biệt với Windows! Rất nhiều framework, các chương trình không hỗ trợ Windows. 

Ubuntu 16.04 vẫn là một sự lựa chọn hoàn hảo tại thời điểm viết bài.

Hãy chắc chắn bạn biết sử dụng

* `ls`, `cd`, `cat`, `pwd`, `rm`
* `du`, `df`, `lscpu`, `free`, `nvidia-smi`
* `chmod`, `chown`
* `top`, `htop`
* `gcc`, `g++`, `make`
* git: `remote`, `brach`, `Fork`, `clone`, `push`, `pull`, `checkout`, merge, `Pull requests`
* `which python`

Hãy chắc chắn bạn biết ý nghĩa của các đường dẫn

* `/home/`, `/var`
* `/etc/hosts`
* `/usr/share/`

Hãy chắc chắn bạn biết giá trị của các biến

* `PATH`, `LD_PATH`

## Môi trường phát triển

Python + Anaconda: Bộ đôi hoàn hảo

Hãy chắc chắn là bạn biết lập trình python, và sử dụng python 3.6+

* Kiểu dữ liệu `number`, `string`, `dict`, `list`, `set`
* Sử dụng `if`, `for`, `while`, `break`, `continue`, `yield` (generator)
* Cách import một module `from`, `import`
* Cách viết một hàm `def`, một class `class`
* Cách làm việc với file, folder `listdir`, `open`, `rm`, `shutil.rmtree`
* Cách lấy tham số `sys.args` 

Và biết các tạo, activate môi trường, cài đặt các gói qua pip và conda.

* `pip install`, `python setup.py install`
* `conda install`, `source activate`, `deactivate`