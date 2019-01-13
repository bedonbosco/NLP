Tài liệu hướng dẫn phát triển của nhóm underthesea

| Người viết        | Vũ Anh     |
|-------------------|------------|
| Phiên bản         | 1.0.0      |
| Cập nhật lần cuối | 13/01/2019 |

# Xử lý một issue 

Các bước thực hiện: 

1. Tạo một nhánh mới tương ứng với Issue. Ví dụ: `GH-163`
2. Thực hiện code trên nhánh này
3. Commit với prefix của issue tương ứng: Ví dụ: `GH-163: add sent_tokenize function`
4. Cập nhật lên git bằng `git push orgin GH-163`
5. Chờ xem có pass test trên travis-CI
6. Cập nhật path version
7. Cập nhật lên git bằng `git push orgin GH-163`
8. Chờ xem có pass test trên travis-CI
9. Merge request.

Sau khoảng 20 phút, phiên bản của underthesea sẽ được cập nhật với tính năng mới.