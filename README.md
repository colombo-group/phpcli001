# phpcli001
Bài tập về làm việc với PHP tạo chương trình tương tác qua command line hoặc chạy như service

# Mục tiêu
- Cách sử dụng composer tạo app PHP, bước đầu tìm hiểu phát triển package như thế nào
- Sử dụng [CLIMATE](http://climate.thephpleague.com/)

# Đề bài
- Sử dụng CLIMATE tạo 1 chương trình PHP cho phép nhập vào 1 số và in ra 1 tam giác, mỗi hàng có 1 màu random khác nhau
- Khi gõ `php program.php`
```
Digic Triangle PHP Program
Input one integer [5]:_
```
- Ví dụ nhập vào 5 thì in ra

```
1
1 2
1 2 3
1 2 3 4 5
```
- Khi gọi `php program.php --num=5` thì không yêu cầu người dùng nhập nữa mà hiển thị luôn với tam giác 5 hàng
