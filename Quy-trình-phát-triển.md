Tài liệu mô tả quy trình phát triển thêm các tính năng, xử lý các bug và phát hành phiên bản mới của nhóm underthesea

> Mục tiêu phát triển là phát hành các phiên bản với các tính năng ổn định, hữu ích

![](https://i.imgur.com/5b4dfpm.png)

## Các bước trong quá trình phát triển 

* Bước 1: Tạo Major Issue, đây là issue ứng với phiên bản chính (ví dụ: LanguageFlow v1.2.0)
* Bước 2: Tạo các issue ứng với các tính năng, bug 
* Bước 3: Thêm các issue này vào các phiên bản phụ (minor version) trong Major Issue
* Bước 4: Xử lý các issue này 
* Bước 5: Merge vào các minor version
* Bước 6: Phát hành rc version cho minor version
* Bước 7: Phát hành minor version (sau rc version khoảng 7 ngày)
* Bước 8: Phát hành rc version cho major version 
* Bước 9: Phát hành phiên bản major version

## Xử lý một issue trên underthesea

Các bước thực hiện: 

1. Tạo một nhánh mới tương ứng với Issue. Ví dụ: `GH-163`
2. Thực hiện code trên nhánh này
3. Commit với prefix của issue tương ứng: Ví dụ: `GH-163: add sent_tokenize function`
4. Cập nhật lên git bằng `git push orgin GH-163`
5. Chờ xem có pass test trên travis-CI
6. Cập nhật path version
7. Cập nhật lên git bằng `git push orgin GH-163`
8. Chờ xem có pass test trên travis-CI
9. Merge pull request.

Sau khoảng 20 phút, phiên bản của underthesea sẽ được cập nhật với tính năng mới.

## Quản lý phiên bản

### Nhánh release-x.y.z 

1. Từ nhánh master, tạo một nhánh release-x.y.z ứng với phiên bản đang phát triển
2. Các tính năng sẽ được phát triển, sau đó merge vào nhánh này
3. Tạo phiên bản rc
    * Bump version của phiên bản thành x.y.z-rc, sau đó merge vào nhánh master để phát hành phiên bản rc 
4. Tạo phiên bản chính 
    * Bump version của phiên bản thành x.y.z, sau đó merge vào nhánh master để phát hành phiên bản chính

### Cách đặt tên commit

* Đặt tên commit với prefix `GH-[ISSUE_NUMBER]: nội dung` trỏ đến issue tương ứng
  * ví dụ: `GH-206: fix flake8`

### Cách đặt tên branch

* Tên branch để phát hành có dạng `release-[VERSION]`
  * ví dụ: `release-1.1.9`

## Tài liệu tham khảo

* [Dự án Flair](https://github.com/zalandoresearch/flair) - Dự án này có rất nhiều điểm rất hay để học hỏi, như cách thêm issue id vào commit message, pinned issue cho kế hoạch phát triển từng phiên bản
* [Dự án allennlp](https://github.com/allenai/allennlp) - Học hỏi từ dự án này cách quản lý phiên bản
* [What is the master branch and release branch for?](https://stackoverflow.com/questions/20755434/what-is-the-master-branch-and-release-branch-for) - Ý nghĩa và sự khác nhau của master và release branch

## Phụ lục: Lịch sử chỉnh sửa 

| Người viết        | Vũ Anh     |
|-------------------|------------|
| Phiên bản         | 1.1.0      |
| Cập nhật lần cuối | 24/04/2019 |

<table>
<tr>
<th>Phiên bản</th>
<th>Ngày cập nhật</th>
<th>Nội dung</th>
</tr>
<tr>
<td>1.1.0</td>
<td>24/04/2019</td>
<td>
- Gộp các tài liệu vào một văn bản duy nhất
</td>
</tr>
<tr>
<td>1.0.0</td>
<td>13/01/2019</td>
<td></td>
</tr>
</table>