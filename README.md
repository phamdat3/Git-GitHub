## Tìm hiểu Git/Github
---
  Thực hiện: **Phạm Văn Đạt**

  Cập nhập lần cuối: *12/2/2017*

## Mục lục 

[Git](#1)
  <ul>
    <li>[1.1Nội dung](#1.1)</li>
    <li>[1.2Công dụng](#1.2)</a></li>
  </ul>
[2.Cài đặt git trên máy tính](#2)    
[3.Cách sử dụng git trên cmd](#3)  
[4.Sử dụng git để commit/ push file README.md lên github](#4)  

## Nội dung.

<a name="1"></a>
###I. Git. 

<a name="1.1"></a>
####1. Nội dung.

Git là tên gọi của một Hệ thống quản lý phiên bản phân tán (Distributed Version Control System – DVCS) là mộttrong những hệ thống quản lý phiên bản phân tán phổ biến nhất hiện nay. DVCS nghĩa là hệ thống giúp mỗi máy tính có thể lưu trữ nhiều phiên bản khác nhau của một mã nguồn được nhân bản (clone) từ một kho chứa mã nguồn (repository), mỗi thay đổi vào mã nguồn trên máy tính sẽ có thể ủy thác (commit) rồi đưa lên máy chủ nơi đặt kho chứa chính. Và một máy tính khác (nếu họ có quyền truy cập) ũng có thể clone lại mã nguồn từ kho chứa hoặc clone lại một tập hợp các thay đổi mới nhất trên máy tính kia. 

<a name="1.2"></a>
####2. Công dụng.

Git là một hệ thống dùng để quản lý và kiểm tra các phiên bản mã nguồn khác nhau trong quá trình phát triển mã nguồn

<a name="2"></a>
###II. Cài đặt git trên máy tính

####1. Tải **file Git** về để cài đặt.

- Đầu tiên bạn truy cập vào [Git](https://git-scm.com/) để tải phần mềm **Git** về để cài đặt.

<img="http://imageshack.com/a/img922/9312/qX8zjd.png">

- Sau đó bạn nhấp vào **Download**  

<img="http://imageshack.com/a/img924/1405/CvzMCk.png">
<img="http://imageshack.com/a/img923/9486/hesLZo.png">
- Như vậy là **Git** đã được tải về

####2. Tiến hành cài đặt.

- Bạn tìm đến **file Git** vừa tải xuống và cài đặt mặc định.

####3. Cập nhập thông tin cá nhân.

- Bạn bật `Git` lên và gõ lệnh
```
 $ git config --global user.name "Tên đăng nhập của bạn"

 $ git config --global user.email "Email của bạn"
```

<img="http://imageshack.com/a/img923/4314/wGAsqm.png"> 

<a name="3"></a>
###III. Cách sử dụng Git trên cmd.

- Tạo ra một bản sao làm việc của một kho lưu trữ địa phương bằng cách chạy lệnh:
 `git clone <địa chỉ file trên github>`
- Bạn có thể đề xuất những thay đổi (thêm nó vào các chỉ số ) sử dụng lệnh:
`git add "tên file"` hoặc `git add *` để chon tất cả.
- Bây giờ tập tin được cam kết với TRỤ , nhưng không phải trong kho lưu trữ từ xa của bạn dùng lệnh: 
`git commit -m"cam kết"`
- Để gửi những thay đổi đó đến kho lưu trữ từ xa của bạn, thực hiện:
`git push`

<a name="4"></a>
###IV. Sử dụng Git để commit/ push file `README.md` lên github.

- Trước hết ta phải tạo 1 file README.md trên `Github`. Và copy link của file đó, trên `Github` ta nhấp vào **Clone or download** và chọn **Use SSh**, song ta copy link đó.

<img="http://imageshack.com/a/img922/4171/lyqweW.png">

- Ta tạo 1 thu mục ở dưới máy và nhấp vào file đó để chạy **Git**.
- Vào được **Git** ta gõ lệnh:
`git clone <địa chỉ lúc nãy copy trên github>` 
  để tạo ra một bản sao làm việc của một kho lưu trữ dưới máy.
- Gõ tiếp lệnh:
`git status` 
 để kiểm tra sự đồng bộ dữ liệu trên máy tính và trên github.
- Gõ tiếp lệnh:
`git add "tên file"` hoặc `git add *` để chon tất cả.
- Gõ tiếp lệnh:
`git commit -m"cam kết"`
 để cam kết dưới máy nhưng chưa được cam kết trên Github.
-Gõ tiếp lệnh:
`git push`
 để lưu trữ và đồng bộ dữ kiệu.

 <img="http://imageshack.com/a/img923/6923/1W8FAc.png">

---
## Hoàn thành Task 02
---
