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
      
       ` cp -r [file nguồn] [file đích]`

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
  8. **mkdir - Tạo thư mục mới **
	  `mkdir <tên thư mục mới muốn tạo>`
	  Tạo một thư mục mới , nó cũng tương tự với việc bạn chọn new/create directory để tạo một thư mục mới trên giao diện người dùng . 
  ---
  9. **rmdir - xóa thư mục**
	  `rmdir <tên thư mục cần xóa> xóa thư mục trong thư mục hiện tại
  ---
  10. **rm - xóa, xóa hết, xóa sạch**
	  `rm <tên file>` xóa file. Bạn cũng có thể sử dụng 
	  `rm -r <tên thư mục>` để xóa thư mục và toàn bộ dữ liệu trong thư mục đó.
---	  
  12. **less – print LESS**
	  `less <tên file>` in ra nội dung của một file theo từng trang trong trường hợp nội dung của file quá lớn và phải đọc theo trang. Bạn có thể dùng *Ctrl+F* để chuyển trang tiếp theo và *Ctrl+B* để chuyển về trang trước
	  
	  ----
  13. **grep**
	  `grep <chuỗi> <tên file>` tìm kiếm nội dung của file theo chuỗi cung cấp.  
		- Có thể dùng
 `grep -i <chuỗi> <tên file>`để tìm kiếm không phân biệt hoa thường 
 hoặc
  `grep -r <chuỗi> <tên thư mục>`để tìm kiếm trong toàn thư mục

  15. **find**
	  `find <thư mục>` -name `<tên file>` tìm kiếm file trong `<thư mục>` theo `<tên file>` .  
		- Ta cũng có thể dùng `find <thư mục>` -iname `<tên file>` để tìm kiếm không phân biệt hoa thường.
  16. **tar**
		 `tar -cvf <tên-file-nén.tar> <file1 hoặc file2 ...>`  tạo file nén (.tar) từ các file có sẵn.

		`tar -tvf <tên-file-nén.tar>`  xem nội dung file nén (.tar).

		`tar -xvf <tên-file-nén.tar>`  giải nén (file .tar).
  17. **gzip**
		  `gzip <tên file>` tạo file nén (.gz). Sử dụng `gzip -d <tên file>` để giải nén (file .gz).
  18. **unzip**
		  `unzip <file-nén.zip>` giải nén một file nén (.zip).
		  
		 - Sử dụng `unzip -l <file-nén.zip>` để xem nội dung file zip mà không cần giải nén

## Cấu trúc phân lớp
-   Trên nhiều hệ điều hành, bao gồm cả linux , file system thường có dạng cây. Linux filesystem sẽ thường được bắt đầu từ thư mục root. Tất cả các thư mục khác là con của thư mục này. Các định dạng file system mà linux sp là: ext2, ext3, ext4, XFS, JFS, btrfs
-   1./ (root): thư mục gốc, thư mục cha toàn bộ hệ thống
-   2./ bin: chứa các tệp binary, chứa các lệnh của người dùng và toàn hệ thống
-   3./ boot: chứa các thư mục và tệp tin trong bootloader
-   4./dev: chứa các thiết bị ngoại vi, thiết bị đầu cuối gắn vào hệ thống
-   5./etc: chứa các câu hình của package, và system
-   6./home: chứa các tập tin, thư mục người dùng trên hệ thống
-   7./lib: chứa các thư viện cho các chương trình trong /bin và /sbin
-   8./media: là các điểm gắn kết system với các thiết bị bên ngoài
-   9./mnt: điểm gắn kết cho phép gắn trực tiếp filesystem
-   10./opt: chứa các gói phần mềm từ các package đã cài đặt
-   11./tmp: chứa các file tạm thời, của các package đang chạy, sẽ mất đi khi root
- 
1. **Thư mục home**
		-   Trong những hệ thống UNIX, mỗi người dùng có đường dẫn sở hữu của họ. Thông thường được đặt /home. Thư mục /home thường được mount 1 filesystem riêng biệt trên partition
		
2. **Thư mục var**
		
<!--stackedit_data:
eyJoaXN0b3J5IjpbNjUxMzg4MjM0LDYxMzcwNDY0LC0xMzU4Mj
c4MTQ5LDg0MDQ4MjY1NCwxMjQ2NTA1MTcwLC0xNjA4MjAwNjEx
LC02NDc2NTUxNjFdfQ==
-->