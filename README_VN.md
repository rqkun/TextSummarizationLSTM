# Về project
Project này sử dụng bộ nhớ dài-ngắn hạn (LSTM), [GloVe](https://nlp.stanford.edu/projects/glove/) làm ma trận embedding và tập [Amazon Fine Foods Reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews) làm dữ liệu huấn luyện, từ đó chúng tôi tạo ra một mô hình có khả năng tóm tắt văn bản theo hướng Abstractive.

# Hướng dẫn sử dụng
**Bước 1:** Thực hiện cell đầu tiên để cài đặt các thư viện cần thiết.
> [!WARNING]
> Chỉ chạy cell này 1 lần duy nhất.
```
%pip install -r requirements.txt
```

**Bước 2:** Ở cell thứ hai, những đường dẫn như ```PATH_TO_DATA```, ```PATH_TO_MODELS``` và ```PATH_TO_CHECKPOINT``` có thể được thay đổi tùy vào nhu cầu người dùng.
> [!NOTE]
> Nếu không có nhu cầu thay đổi thư mục lưu trữ các file được đề cập thì không cần thay đổi đường dẫn.
```
PATH_TO_DATA = '<Đường dẫn mới>'
PATH_TO_MODELS = '<Đường dẫn mới>'
PATH_TO_CHECKPOINT = '<Đường dẫn mới>'
```

**Bước 3:** Chạy những cells phía sau theo thứ tự một cách tuần tự.

# Giảng viên hướng dẫn
- ThS. Trần Trọng Bình

# Người thực hiện
1. Ngô Hoàng Khánh Duy
2. Huỳnh Nhật Minh
