# Quá trình phát triển hệ điều hành linux

1. **Nguồn Gốc**

	
	**1.1 **Unix**

	-hệ điều hành Unix bắt nguồn từ một đề án nghiên cứu tại phòng thì nghiệm Bell Labs của công ty AT&T và được dẫn dắt bởi Ken Thompson, Dennis Ritchie hai nhà khoa học máy tính nổi tiếng.

	![](https://upload.wikimedia.org/wikipedia/commons/4/46/Ken_Thompson_and_Dennis_Ritchie.jpg)


   		Chân dung Ken Thompson (bên trái), Dennis Ritchie (bên phải)

 	- Phiên bản đầu tiên của Unix được ra đời vào tháng 3 năm 1971, tiếp đó là phiên bản thứ 2 ra đời năm 1972.

 	- Trong 10 năm đầu, việc phát triển Unix giới hạn bên trong Bell Labs là chính. Những phiên bản trong thời gian này được gọi là Version n (Vn).

 	- Unix bắt đầu được viết bằng ngôn ngữ Assembly nhưng sau đó Dennis Ritchie - cha đẻ của ngôn ngữ lập trình C đã chuyển qua viết lại Unix bằng chính ngôn ngữ C (trừ nhân kernel, I/O). Và rồi:

 	- Năm 1973, V4 được viết bằng C. Đây là sự kiện đáng chú ý nhất trong lịch sử hệ điều hành này vì lợi ích của việc viết hệ điều hành bằng ngôn ngữ bậc cao là có khả năng mang mã nguồn của hệ sang các nền máy tính khác và biên dịch lại, chính nhờ điều này mà hệ điều hành sẽ có các bản chạy trên các hệ máy tính khác nhau.

 	- Năm 1976, V6 được phát miễn phí cho các trường đại học.

 	- Năm 1979, V7 được phát hành rộng rãi với giá $100$ cho các trường đại học và $21,000 cho những thành phần khác. V7 là phiên bản căn bản cho các phiên bản sau này của Unix.

	**1.2** **BSD**    

	- Những năm của thập niên 70, AT&T chia sẻ Unix cho những tổ chức giáo dục, hay tổ chức thương mại bên ngoài, từ đó dẫn đến sự ra đời của nhiều phiên bản Unix khác nhau.

    Từ năm 1977, Computer Systems Research Group (CSRG) của trường đại học California, Berkeley được quyền sử dụng code của Unix để phát triển ra nhãn hiệu UNIX khác là BSD (Berkeley Software Distribution)

    Có nhiều công ty lớn sử dụng FreeBSD cho hệ thống máy chủ như Yahoo, Sony.


    Khi AT&T bắt đầu khai thác Unix như sản phẩm thương mại thì tiền bản quyền Unix tăng lên nhanh chóng (đoạn $21,000 ở trên đó) làm cho Berkeley phải đặt kế hoạch thay mã nguồn của AT&T bằng mã riêng. Việc này tốn rất nhiều thời gian và không kịp hoàn thành khi Berkeley bị ngưng tài trợ nghiên cứu hệ điều hành, CSRG giải tán.

    BSD Unix và AT&T Unix là hai dòng chính của Unix.

    BSD giúp cho Unix trở nên phổ biến và có nhiều đóng góp về mặt kỹ thuật như: csh, termcap, curses, vi, TCP/IP socket, long file name, symbolic link

	**1.3 **Unix && BSD**

	- Nhánh BSD đi đến hồi kết của quá trình phát triển với sự ra đời và của các open source project như: FreeBSD, NetBSD và OpenBSD. BSD phát triển từ version 1 đến version cuối cùng 4.4 năm 1992.

	- Trong khi đó, phiên bản cuối cùng của Unix được phát triển bởi Bell Laps, phiên bản Unix 10, được ra mắt vào năm 1989.

	- Mặc dù phiên bản chính thức của Unix, BSD đã dừng phát triển từ lâu, thế nhưng những di sản mà chúng để lại là rất lớn cho đến ngày hôm nay. Rất nhiều hệ điều hành, từ close source cho đến open source đều dựa trên 2 nhánh này

	![](https://images.viblo.asia/9fdc05b1-a243-4e72-81d4-ab85a4572263.png)