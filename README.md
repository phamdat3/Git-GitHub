## Tìm hiểu Git/Github
---
  Thực hiện: **Phạm Văn Đạt**

  Cập nhập lần cuối: *12/2/2017*

## Mục lục 

<a href="#Git">1.Gi</a>
  <ul>
    <li><a href="#Nội dung1">1.1Nội dung</a></li>
    <li><a href="#Công dụng1">1.2Công dụng</a></li>
  </ul>
<a href="#Cài đặt">2.Cài đặt git trên máy tính</a>  
<a href="#Cách sử dụng">3.Cách sử dụng git trên cmd</a>   
<a href="#commit&push">4.Sử dụng git để commit/ push file README.md lên github</a>

## Nội dung.

<id ="Git">
###I. Git. 

<id ="Nội dung1">
####1. Nội dung.

Git là tên gọi của một Hệ thống quản lý phiên bản phân tán (Distributed Version Control System – DVCS) là mộttrong những hệ thống quản lý phiên bản phân tán phổ biến nhất hiện nay. DVCS nghĩa là hệ thống giúp mỗi máy tính có thể lưu trữ nhiều phiên bản khác nhau của một mã nguồn được nhân bản (clone) từ một kho chứa mã nguồn (repository), mỗi thay đổi vào mã nguồn trên máy tính sẽ có thể ủy thác (commit) rồi đưa lên máy chủ nơi đặt kho chứa chính. Và một máy tính khác (nếu họ có quyền truy cập) ũng có thể clone lại mã nguồn từ kho chứa hoặc clone lại một tập hợp các thay đổi mới nhất trên máy tính kia. 

<id ="Công dụng1">
####2. Công dụng.

Git là một hệ thống dùng để quản lý và kiểm tra các phiên bản mã nguồn khác nhau trong quá trình phát triển mã nguồn

<id ="Cài đặt">
###II. Cài đặt git trên máy tính

####1. Tải **file Git** về để cài đặt.

- Đầu tiên bạn truy cập vào [Git](https://git-scm.com/) để tải phần mềm **Git** về để cài đặt.

<img src="https://viblo.asia/uploads/f4bff516-3b2f-499c-83e7-35b42d6d9179.jpeg">

- Sau đó bạn nhấp vào **Download** 
- Như vậy là **Git** đã được tải về

####2. Tiến hành cài đặt.

- Bạn tìm đến **file Git** vừa tải xuống và cài đặt mặc định.

####3. Cập nhập thông tin cá nhân.

- Bạn bật `Git` lên và gõ lệnh
```
 $ git config --global user.name "Tên đăng nhập của bạn"

 $ git config --global user.email "Email của bạn"
```
<id="Cách sử dụng">
###III. Cách sử dụng Git trên cmd.

- Tạo ra một bản sao làm việc của một kho lưu trữ địa phương bằng cách chạy lệnh:
 `git clone <địa chỉ file trên github>`
- Bạn có thể đề xuất những thay đổi (thêm nó vào các chỉ số ) sử dụng lệnh:
`git add "tên file"` hoặc `git add *` để chon tất cả.
- Bây giờ tập tin được cam kết với TRỤ , nhưng không phải trong kho lưu trữ từ xa của bạn dùng lệnh: 
`git commit -m"cam kết"`
- Để gửi những thay đổi đó đến kho lưu trữ từ xa của bạn, thực hiện:
`git push`

<id="commit&push">
###IV. Sử dụng Git để commit/ push file `README.md` lên github.

- Trước hết ta phải tạo 1 file README.md trên `Github`. Và copy link của file đó, trên `Github` ta nhấp vào **Clone or download** và chọn **Use SSh**, song ta copy link đó. 
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

---
## Hoàn thành Task 02
---
