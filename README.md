# Chương trình thu thập dữ liệu nói tục

## Chạy code
- Đầu tiên clone project về máy local, mở vscode và mở đúng cái thư mục vừa clone về (dùng chức năng open folder trong vscode và trỏ đúng thư mục vừa clone về đấy)

- Chạy lệnh `cmd` trong thư mục đó để tải thư viện cần thiết:

```bash
    pip install -r requirements.txt
```

Hoặc tải từng thư viện cần thiết sau:
    `mediapipe==0.10.10` `opencv-python` `numpy` `pandas` `pillow`

## Cách chạy

- Chạy file `colecting.py` sau khi đã cài đủ thư viện yêu cầu

- Nhìn vào phần hướng dẫn trên màn hình trước khi thu thập dữ liệu, nhìn từ để nói và chuẩn bị nói. Tiến hành lấy dữ liệu cụ thể như sau:

    - Nhấn phím `s` mỗi khi lấy dữ liệu ,tức bắt đầu nói để ghi dữ liệu, sau khi nhấn thì nói ngay từ cần nói ngay lập tức, không quá nhanh và chậm, không dừng giữa chừng khi lấy dữ liệu mỗi từ. 
    - Sau khi lấy dữ liệu xong nhấn phím `d` ngay lập tức để tiến hành đến từ tiếp theo. Nếu cần thu thập lại data trước đó thì nhấn `b`.

    - Từ tiếp theo cũng như từ đầu cũng là đọc từ hiển thị trên màn để chuẩn bị đọc --> nhấn `s` và lập tức đọc từ đấy để chương trình ghi, đọc hết từ thì nhấn `d` ngay lập tức để chuẩn bị lấy từ tiếp theo như tương tự.

# Cảm ơn các bạn
- Các bạn có thể trợ giúp ghi thêm các từ nói tục vào file `bad_words.csv` và không tục (đời thường) vào file `good_words.csv` và chạy lại từ đầu.

