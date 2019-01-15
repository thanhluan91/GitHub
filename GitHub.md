# GitHub
**I. Mở Đầu** 
- `Github` là một phần mềm dùng để quản lý phiên bản của mã nguồn tương tự như `SVN` nhưng có nhiều ưu điểm hơn, `Github` đang được sủ dụng rộng rãi hiện nay. Tuy nhiên trong bài viết này, tôi sẽ nói về git một cách "cá nhân" hơn, mang tính chia sẻ những cái tôi hay làm và hướng tới những người là sysadmin ,mới tìm hiểu về `Github`
- **`Khái Niệm`**
GitHub là một trang web, cho phép bạn lưu các source code của mình lên đó. Bạn có thể thay đổi đoạn code của mình mọi lúc mọi nơi mà không sợ bị ghi đè lên hay mất dữ liệu do hỏng hóc vì dữ liệu của bạn được lưu trên web GitHub và máy tính cá nhân . Bạn cũng có thể thay đổi code của mình ở một thời điểm bất kỳ nào đó.

Github có bản free và mất phí. Với Github free thì source code của bạn sẽ công khai, có nghĩa là ai cũng có thể xem code của bạn. Nó phù hợp với các phần mềm nguồn mở, và cũng có thể trở thành một blog cá nhân của chính các bạn như các trang blogspot, wordpress,...

Nếu muốn mình có thể tạo một kho code bí mật của riêng mình thì bạn phải trả phí .
nhưng không cần bí mật thì Github free là quá đủ cho mục đích lưu trữ và chia sẻ thông tin .

**Cần làm gì để sử dụng GitHub ?**

 1.Đăng ký tài khoản tại github.com và đăng nhập
 1. Học cách sử dụng ngôn ngữ `markdown`
 2. Tạo một Repo đầu tiên và gõ những gì mình muốn bằng markdown . Sau đó tạo các Repo tùy mục đích , clone nó về client và code
  --
  

## **II. Ngôn Ngữ Markdown** 
 Ngôn ngữ này khá đơn giản , bạn có thể đọc tại [đây](https://viblo.asia/helps/cach-su-dung-markdown-bxjvZYnwkJZ) để biết cách sử dụng chi tiết hơn 
 Tôi thường dụng theo cách sau:
  

 

 - Tạo một file có tên bất kỳ với đuôi `.md`. Có thể dùng `notepad`, `noteped++`. `nano`,......hay bất kỳ ứng dụng nào bạn biết
 - Tôi hay viết trực tiếp trên trang [này](https://stackedit.io/) để làm quen với markdown

 1. Thẻ tiêu đề

Markdown sử dụng kí tự # để bắt đầu cho các thẻ tiêu đề, có thể dùng từ 1 đến 6 ký tự # liên tiếp. Mức độ riêu đề giảm dần từ 1 đến 6

Tùy mục đích và ý thích bạn có thể sử dụng cách này để thể hiện các chỉ mục khác nhau.

Ví dụ:

```
# 1.Tiêu đề cấp 1

```

1.Tiêu đề cấp 1

```
## 2.Tiêu đề cấp 2

```

2.Tiêu đề cấp 2

```
###### 6.Tiêu đề cấp 6

```

###### [](https://github.com/hocchudong/git-github-for-sysadmin#6ti%C3%AAu-%C4%91%E1%BB%81-c%E1%BA%A5p-6)6.Tiêu đề cấp 6

2. Chèn link, chèn ảnh

Để chèn hyperlink bạn chỉ cần paste luôn linh đó vào file .md

```
https://github.com

```

[https://github.com](https://github.com/)

Hoặc bạn cũng có thể sử dụng cú pháp sau để thu ngắn đường dẫn của link

```
[Github](https://github.com)

```

Kết quả là:

[Github](https://github.com/)

Để chèn ảnh thì bạn hãy sử dụng cú pháp sau:

```
<img src="link_anh_cua_ban">

```

Tôi thường sử dụng công cụ  [Lightshot](https://app.prntscr.com/en/index.html)  để chụp ảnh màn hình và up hình đó lên trang  [http://i.imgur.com/](http://i.imgur.com/)  để lấy đường dẫn ảnh đưa vào Github

Hai công cụ này khá dễ sử dụng, bạn chỉ cần chụp màn hình bằng Lightshot ấn Ctrl + C để copy và Ctrl + V để paste vào trình duyệt tại trang web  [http://i.imgur.com/](http://i.imgur.com/)

3. Ký tự in đậm, in nghiêng

-   Để in đậm một đoạn text bạn chỉ cần làm như sau:

```
**từ cần in đậm**

```

**từ cần in đậm**

-   Để in nghiên một đoạn text bạn chỉ cần làm như sau:

```
*từ cần in nghiêng*

```

_từ cần in nghiêng_

4. Trích dẫn, bo chữ

Để bo một đoạn text thì bạn chỉ cần sử dụng cú pháp sau:

```
`đoạn cần bo`

```

Kết quả là:  `đoạn cần bo`

Để làm nổi bật một đoạn, chẳng hạn như một đoạn shell hay file cấu hình bạn có thể sử dụng cú pháp như ví dụ sau:

```
```sh
auto eth0
iface eth0 inet static
ipaddress 10.10.10.10
netmask 255.255.255.0
gateway 10.10.10.1
dns-nameservers 8.8.8.8
```



Kết quả như sau:
```
auto eth0
iface eth0 inet static
ipaddress 10.10.10.10
netmask 255.255.255.0
gateway 10.10.10.1
dns-nameservers 8.8.8.8
```

5. Gạch đầu dòng

Để sử dụng gạch đầu dòng bạn chỉ cần sử dụng cú pháp sau:


- Gạch đầu dòng thứ nhất
  
  - Thụt với đầu dòng 1
  
  - Thụt với đầu dòng 1
 
- Gạch đầu dòng thứ hai
  
  - Thụt với đầu dòng 2
  
  - Thụt với đầu dòng 2
  

```

-   Gạch đầu dòng thứ nhất
    
    -   Thụt với đầu dòng 1
        
    -   Thụt với đầu dòng 1
        
-   Gạch đầu dòng thứ hai
    
    -   Thụt với đầu dòng 2
        
    -   Thụt với đầu dòng 2
        
```
 6. Tạo bảng

Bạn có thể sử dụng cú pháp sau để tạo bảng:


`| Cột 1 Hàng 1 | Cột 2 | Cột 3| Cột 4 |`
`|--------------|-------|------|-------|`
`| Hàng 2 | 2 x 1 | 2 x 2 | 2 x 3 | 2 x 4 |`
`| Hàng 3 | 3 x 1 | 3 x 2 | 3 x 3 | 3 x 4 |`
`| Hàng 4 | 4 x 1 | 4 x 2 | 4 x 3 | 4 x 4 |`

kết quả như sau 

| Cột 1 Hàng 1 | Cột 2 | Cột 3| Cột 4 |
|--------------|-------|------|-------|
| Hàng 2 | 2 x 1 | 2 x 2 | 2 x 3 | 2 x 4 |
| Hàng 3 | 3 x 1 | 3 x 2 | 3 x 3 | 3 x 4 |
| Hàng 4 | 4 x 1 | 4 x 2 | 4 x 3 | 4 x 4 |

### **III. Basic Git commands**
  | Git task| Notes|Git commands |
  |:------------------------------|:------------------------------|:-------------|
  | Khai Báo tài khoản với Git | Cấu hình tên và địa chỉ mail để tạo key và liên kết xác thực tài khoản với Git | Git config   --global   user.name  `Thanhluan91`  -  Git config  --global  user.email `lamchidinhdn@gmail.com`| 
 |Tạo kho dữ liệu ( repository ) cục bộ mới|| `Git  init`|
 |||`Git|
 ||||
 ||||
 ||||
 ||||








 

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0NTc1NjU0MTYsNDQxNzM2MTg1LC0xND
E2MzY3MjczLDE3MDIzMzU5NywtMTIxNDM0NzM5MywtMTM0MDA4
ODg2MiwzNDk0OTQxMzFdfQ==
-->