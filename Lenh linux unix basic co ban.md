# -  Tìm hiểu về linux và lệnh basic cơ bản của linux/unix

 **- Các lệnh về thư mục tệp tin -**
  1. **pwd - Mình đang ở đâu ?**

   pwd là viết tắt của Print Working Directory (In ra thư mục hiện tại). Nếu bạn để ý thì sẽ thấy hầu hết các lệnh trong Linux đều là viết tắt của một từ hay cụm từ nào đó.

   Khi dùng lệnh pwd chúng ta sẽ có full path của thư mục mà chúng ta đang dùng ở hiện tại. Ở trên Gnome thì trên thanh tiêu đề Terminal có hiển thị sẵn thư mục đang dùng rồi
    `pwd`

---
  2. **ls - Có những gì ở đây**

  ls sẽ liệt kê toàn bộ những file, directory có trong thư mục hiện tại. Nếu các bạn sử dụng Linux thì đây sẽ là một lệnh có thể nói là dùng nhiều nhất nhì. Cách sử dụng:
  ` ls [option]`

    - ls -l sẽ hiển thị tên file, directory cùng với size, ngày tháng chỉnh sửa gần nhất, user sở hữu và các permisson của user đó. Chúng ta còn có thể sử dụng ll cho ngắn gọn hơn ls -l

    - ls -a sẽ hiển thị toàn bộ file/thư mục, kể các các file/thư mục ẩn.

    - ls -h hiển thị size dưới dạng dễ hiểu hơn, như kb, mb ...

    - ls -R hiện thị cả các file ở các sub-directory

    - ls [directory_path] sẽ hiển thị các file/thư mục ở directory đó, có thể dùng thêm các options bên trên.
---
  3. **cd đến nơi khác**

  cd viết tắt của Change Directory, nghĩa là đổi sang thư mục khác. Dùng cực kỳ thường xuyên, ngày nào cũng phải dùng 
  chuyển một thư mục thành thư mục hiện hành cho phiên làm việc hiện tại. Nó cũng tương tự với việc bạn mở một thư mục và thao tác với các file và thư mục bên trong đó trên giao diện người dùng
    - cd đến thư mục /usr/local

       `CentOS1: ~$ cd /usr/local`

    - cd tiếp đến /usr/local/lib

       `CentOS1: ~$ cd /usr/local/lib`
    hoặc
       `CentOS1:/usr/local$ cd /usr/local/lib`

    - chuyển sang thư mục mẹ

       `CentOS1:/usr/local/lib$ cd ..`
        `CentOS1:/usr/local$`

    - di chuyển về thư mục *Home*

       `CentOS1:/usr/local$ cd`
       `CentOS1:~$`

    - Quay về thư mục trước (folder)

       `CentOS1:/usr/local/lib$ cd -`
       `CentOS1:/usr/local$`   
  ---      
  4. **cp - Tạo bản copy**
  cp viết tắt của copy là sao chép thư mục khác
     - Để tạo bản copy của 1 file nhưng với tên khác trong cùng directory

       ` cp [file nguồn] [file đích]`

     - Để copy 1 hay nhiều file đến directory khác

       ` cp [file_1] [file_2] [file_n] [dir_path]`

     - Để copy dir này sang dir khác . (folder cần copy không được có dấu "/" ở cuối nếu không sẽ lỗi) 
      
       ` cp -r [file nguồn] [file đích]

      - Để hiển thị quá trình copy (ta dùng option '-v')

       ` cp -v a.txt b.txt c.txt lab/`
      
       `a.txt` -> `lab/a.txt` -
       `b.txt` -> `lab/b.txt` -
       `c.txt` -> `lab/c.txt` -
---
  5. **mv - di chuyển hoặc đổi tên**
	  -  `mv <file nguồn> <file đích>`  di chuyển một file hoặc thư mục từ vị trí này sang vị trí khác . Lệnh này cũng dùng để đổi tên tệp tin/thư mục khi thư mục nguồn và đích trùng nhau
	  
---
  6. **Cat - Xem tâp tin**
	  `cat <tên tập tin> `
	  - Dùng để xem hoặc in nội dung tệp tin nào đó . tương tự như việc mở một tập tin bằng công cụ hỗ trợ như Notepad trong Windown
 ---
 
  7. **tail - print Tail**
	  `tail <tên file>` đọc và in ra nội dung 10 dòng cuối cùng của file (mặc định)
	  `tail -n N <tên file>` trong đó N chỉ định số dòng muốn xem, in ra màn hình
---
  8. **mkdir **
  9. **rm - xóa, xóa hết, xóa sạch**
	  
  10. **Các lệnh về thông tin hệ thống**

  11. **df -kiểm tra dung lượng các partition**
  12. **du - kiểm tra dung lượng các directory**
  13. **free - thông tin về Ram**
  14. **top - Một Task Manager của Linux**
  15. **uname - Thông tin về kernel**
  16. **ifconfig - Hiển thị thông tin mạng**
  17. ** **
<!--stackedit_data:
eyJoaXN0b3J5IjpbNDg3NDAyMjY2LDg0MDQ4MjY1NCwxMjQ2NT
A1MTcwLC0xNjA4MjAwNjExLC02NDc2NTUxNjFdfQ==
-->