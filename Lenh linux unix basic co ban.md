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
**1. / –  Root**

- Đúng với tên gọi của mình: nút gốc (root) đây là nơi bắt đầu của tất cả các file và thư mục. Chỉ có root user mới có quyền ghi trong thư mục này. Chú ý rằng /root là thư mục home của root user chứ không phải là /.

**2. /bin – Chương trình của người dùng**

- Thư mục này chứa các chương trình thực thi. Các chương trình chung của Linux được sử dụng bởi tất cả người dùng được lưu ở đây. Ví dụ như: ps, ls, ping…

**3. /sbin – Chương trình hệ thống**

- Cũng giống như /bin, /sbinn cũng chứa các chương trình thực thi, nhưng chúng là những chương trình của admin, dành cho việc bảo trì hệ thống. Ví dụ như: reboot, fdisk..

**4. /etc – Các file cấu hình**

- Thư mục này chứa các file cấu hình của các chương trình, đồng thời nó còn chứa các shell script dùng để khởi động hoặc tắt các chương trình khác. Ví dụ: /etc/resolv.conf, /etc/logrolate.conf

**5. /dev – Các file thiết bị**

- Các phân vùng ổ cứng, thiết bị ngoại vi như USB, ổ đĩa cắm ngoài, hay bất cứ thiết bị nào gắn kèm vào hệ thống đều được lưu ở đây. Ví dụ: /dev/sdb1 là tên của USB bạn vừa cắm vào máy, để mở được USB này bạn cần sử dụng lệnh  `mount`

**6. /tmp – Các file tạm**

- Thư mục này chứa các file tạm thời được tạo bởi hệ thống và các người dùng. Các file lưu trong thư mục này sẽ bị xóa khi hệ thống khởi động lại.

**7. /proc – Thông tin về các tiến trình**

- Thông tin về các tiến trình đang chạy sẽ được lưu trong /proc dưới dạng một hệ thống file thư mục mô phỏng. Ví dụ thư mục con /proc/{pid} chứa các thông tin về tiến trình có ID là pid (pid ~ process ID). Ngoài ra đây cũng là nơi lưu thông tin về về các tài nguyên đang sử dụng của hệ thống như: /proc/version, /proc/uptime…

**8. /var – File về biến của chương trình**

- Thông tin về các biến của hệ thống được lưu trong thư mục này. Như thông tin về log file: /var/log, các gói và cơ sở dữ liệu /var/lib…

**9. /usr – Chương trình của người dùng**

- Chứa các thư viện, file thực thi, tài liệu hướng dẫn và mã nguồn cho chương trình chạy ở level 2 của hệ thống. Trong đó

	-   /usr/bin chứa các file thực thi của người dùng như: at, awk, cc, less… Nếu bạn không tìm thấy chúng trong /bin hãy tìm trong /usr/bin
	-   /usr/sbin chứa các file thực thi của hệ thống dưới quyền của admin như: atd, cron, sshd… Nếu bạn không tìm thấy chúng trong /sbin thì hãy tìm trong thư mục này.
	-   /usr/lib chứa các thư viện cho các chương trình trong /usr/bin và /usr/sbin
	-   /usr/local chứa các chương tình của người dùng được cài từ mã nguồn. Ví dụ như bạn cài  apache từ mã nguồn, nó sẽ được lưu dưới /usr/local/apache2

**10. /home – Thư mục người của dùng**

- Thư mục này chứa tất cả các file cá nhân của từng người dùng. Ví dụ: /home/john, /home/marie

**11. /boot – Các file khởi động**

- Tất cả các file yêu cầu khi khởi động như initrd, vmlinux. grub được lưu tại đây. Ví dụ vmlixuz-2.6.32-24-generic

**12. /lib – Thư viện hệ thống**

- Chứa cá thư viện hỗ trợ cho các file thực thi trong /bin và /sbin. Các thư viện này thường có tên bắt đầu bằng ld* hoặc lib*.so.*.

**13. /opt – Các ứng dụng phụ tùy chọn**

- Tên thư mục này nghĩa là optional (tùy chọn), nó chứa các ứng dụng thêm vào từ các nhà cung cấp độc lập khác. Các ứng dụng này có thể được cài ở /opt hoặc một thư mục con của /opt

**14. /mnt – Thư mục để mount**

- Đây là thư mục tạm để mount các file hệ thống. Ví dụ như # mount /dev/sda2 /mnt

**15. /media – Các thiết bị gắn có thể gỡ bỏ**

- Thư mục tạm này chứa các thiết bị như CdRom /media/cdrom. floppy /media/floopy hay các phân vùng đĩa cứng /media/Data (hiểu như là ổ D:/Data trong  Windows

		
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwMjc5MzU4NCwtMTgzMTg0OTcwNiw2MT
M3MDQ2NCwtMTM1ODI3ODE0OSw4NDA0ODI2NTQsMTI0NjUwNTE3
MCwtMTYwODIwMDYxMSwtNjQ3NjU1MTYxXX0=
-->