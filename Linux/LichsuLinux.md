# Quá trình phát triển hệ điều hành linux

1. **Nguồn Gốc**

	
	**1.1** **Unix**

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

	**1.3** **Unix && BSD**

	- Nhánh BSD đi đến hồi kết của quá trình phát triển với sự ra đời và của các open source project như: FreeBSD, NetBSD và OpenBSD. BSD phát triển từ version 1 đến version cuối cùng 4.4 năm 1992.

	- Trong khi đó, phiên bản cuối cùng của Unix được phát triển bởi Bell Laps, phiên bản Unix 10, được ra mắt vào năm 1989.

	- Mặc dù phiên bản chính thức của Unix, BSD đã dừng phát triển từ lâu, thế nhưng những di sản mà chúng để lại là rất lớn cho đến ngày hôm nay. Rất nhiều hệ điều hành, từ close source cho đến open source đều dựa trên 2 nhánh này

	![](https://images.viblo.asia/9fdc05b1-a243-4e72-81d4-ab85a4572263.png)

	**1.4** **GNU**
		- 
    Năm 1971, Richard Stallman bắt đầu làm việc tại MIT trong một nhóm nhân viên kĩ thuật chuyên sử dụng phần mềm tự do. Tuy vậy, đến những năm của thập kỉ 80, hầu hết các phần mềm đều có tính chất sở hữu (bản quyền). Nhận thấy điều này có thể ngăn cản việc hợp tác giữa những người phát triển phần mềm, Stallman và những người khác khởi đầu dự án GNU vào năm 1983.
    		![](https://upload.wikimedia.org/wikipedia/commons/3/3d/Richard_Stallman_at_Pittsburgh_University.jpg)

              Richard Stallman tại đại học Pittsburgh 2010

    Mục tiêu của dự án GNU là tạo ra được một hệ điều hành giống Unix nhưng miễn phí, nơi mà mọi người có quyền tự do copy, phát triển, chỉnh sửa và phân phối phần mềm và việc tái phân phối là không bị giới hạn.

    Sau đó vào năm 1985, Stallman bắt đầu thành lập Tổ chức phần mềm tự do và viết ra giấy phép chung GNU (GNU General Public License - GNU GPL) vào năm 1989.

    Khoảng đầu 1990, nhiều chương trình như thư viện, trình biên dịch, trình soạn thảo văn bản, Unix Shell, và một chương trình quản lý cửa sổ đã ra đời, nhưng các thành phần cấp thấp cần thiết như trình điều khiển thiết bị, daemons, và kernel vẫn chưa hoàn thành.

    Như vậy điều Richard Stallman tìm kiếm bây giờ là có phần nhân hệ điều hành để chạy những phần mềm trên.

    Và thế là định mệnh của cuộc tình đôi ta bắt đầu từ đây: GNU và Linux.

    **1.5** **Linux**
    - Vào năm 1991 trong khi đang học tại Helsinki - Phần Lan, Linus Torvalds bắt đầu có ý tưởng về một hệ điều hành, hơn nữa ông cũng nhận thấy hạn chế trong giấy phép của Minix - chỉ cho phép việc sử dụng Minix trong giáo dục mà thôi. Ông bắt đầu viết nên hệ điều hành riêng của mình.
    	![](https://images.viblo.asia/24d02ced-bfc0-4d9f-9d7a-2f10e80b689d.jpg)

           Chân dung Linus Torvalds, tác giả của hệ điều hành mã nguồn mở Linux.

    -	Torvalds phát triển Linux kernel trên môi trường Minix, các ứng dụng viết cho Minix có thể sử dụng trên Linux. Sau này, khi Linux đã "trưởng thành" thì việc phát triển Linux diễn ra ngay trên hệ thống Linux

    **1.6** **GNU/Linux**

    	- Thế là bác Richard Stallman sở hữu các phần mềm của GNU thì thiếu lõi, nhân kernel, còn bác Linus Torvalds thì đã có nhân kernel nhưng để phát triển lên được hệ điều hành hoàn chỉnh là còn nhiếu rất nhiều thứ abc xyz. Cả hai bác đều có chung tư tưởng lớn, muốn xây dựng hệ điều hành mã nguồn mở.

    	- Linus Torvalds làm việc một cách hăng say trong vòng 3 năm liên tục và sự kết hợp của nhân Linux cùng các phần mềm của GNU đã cho ra đời hệ điều hành hoàn toàn miễn phí đầu tiên. Nó được mang tên GNU/Linux với phiên bản 1.0 vào năm 1994 - được phát triển và tung ra trên thị trường dưới bản quyền GNU General Public License. Do đó mà bất cứ ai cũng có thể tải và xem mã nguồn của GNU/Linux.
    			![](https://images.viblo.asia/e65e233c-0198-48d1-b3c4-4c866f877340.jpg)

    	-	Một cách chính xác, thuật ngữ Linux được sử dụng để chỉ nhân hệ điều hành (kernel), chứ bản thân nó chưa phải là hệ điều hành nhé !

		-	Còn hệ điều hành được tạo ra bởi việc đóng gói nhân Linux cùng với các thư viện và công cụ GNU - hệ điều hành bạn đang sử dụng đó, nó có tên là GNU/Linux. Nhưng không hiểu sao người ta gọi ngắn ngọn lại là Linux. Hẳn là một sự bất công bằng cho GNU, nhưng biết làm sao được. Và đành xuôi theo chiều gió, trong series này, mình cũng dùng từ Linux để chỉ hệ điều hành này, còn khi nào cần nhắc tới phần nhân thì mình sẽ nói rõ là kernel Linux.

	kiểm tra bằng cách vào Terminal gõ: 
	![](https://i.imgur.com/74FT48G.png)

