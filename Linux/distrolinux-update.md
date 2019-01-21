 TÌM HIỂU DISTRO VÀ CÁC PHÂN PHỐI DISTRO PHỔ BIẾN

# Mục lục

[1. Khái niệm Distro](#1)

- [1.1. Khái niệm distro ](#1.1)


[2. Các nhánh distro phổ biến](#2)

- [2.1. Debian](#2.1)

- [2.2. Ubuntu](#2.2)

- [2.3. Red Hat Enterprise linux (RHEL) và Fedora](#2.3)

- [2.4. CentOS](#2.4)

- [2.5. Slackware](#2.5)

[3. Các nhóm các distro phổ biến ](#3)



---

<a name="1"></a>
# 1. Khái niệm distro

<a name="1.1"></a>
## 1.1. Giới thiệu distro  

- ***Distro*** là từ viết tắt thay thế cho **Linux Distribution** - bản phân phối của Linux - là một **hệ điều hành**
được tập hợp từ nhiều phần mềm dựa trên nhân Linux (**Linux Kernel**) và thường có một hệ thống quản lý các gói tin.

- **Thành phần:** Một bản distro điển hình bao gồm: một kernel Linux, các công cụ và thư viện GNU,
các phần mềm thêm vào, phần document, một hệ thống window system (mà phần lớn là sử dụng X 
Window System - hệ thống cửa sổ dùng để hiển thị đồ họa Bitmap), window manager và desktop environment.

- Hiện tại, có khoảng 600 bản distro tồn tại, với gần 500 trong số đó phát triển tích cực, liên tục được
sửa đổi và cải thiện. Bởi sự sẵn có của số lượng lớn phần mềm, distro khá là đa dạng về hình thức - 
phù hợp với từ desktop, server, laptop, netbooks, điện thoại di động, máy tính bảng cũng như môi trường tối
thiếu thường để sử dụng trong các hệ thống nhúng. 

 - Có nhiều bản phân phối thương mại như Fedora (Red hat), OpenSUSE (SUSE), Ubuntu (Canonical Ltd); và hoàn
 toàn phân phối dựa vào cộng đồng như Debian, Slackware, Gentoo hay Arch Linux.  

<a name="1.2"></a>
# 2. Các nhánh distro phổ biến.

-  Dù nhiều nhưng về cơ bản đều dựa trên 3 nhánh lớn chính đó là **Debian**, **Red Hat** và **Slackware**. Lí do là do Linux "mở" nên bất cứ ai nếu thích đều có thể tạo một Distro và đặt tên nó theo ý thích của mình, miễn là tuân theo "luật". Tất nhiên sẽ có những Distro sẽ không có ai sử dụng và chết theo thời gian. Những Distro nào kiếm được tiền, cộng đồng mạnh, có uy tín thì sẽ sống.


- Sau một thời gian dài phát triển thì iện nay, 2 nhánh distro phổ biến nhất trong cộng đồng Phần mềm mã nguồn mở là **Debian** và **Fedora** (Có mối quan hệ chặt chẽ với **Red hat**). 

<a name="2.1"></a>
## 2.1. Debian 

<img src="https://st.quantrimang.com/photos/image/2018/09/18/ban-phan-phoi-linux-2.jpg">

- Debian là một trong những bản phân phối Linux đầu tiên. Nó được Ian Murdock công bố lần đầu vào ngày 16 tháng 8 năm 1993, nhưng phải đến năm 1996 mới phát hành phiên bản ổn định đầu tiên của nó. Về cơ bản, nhà phát triển muốn tạo một bản phân phối ổn định để mọi người có thể tải và sử dụng miễn phí, thay vì phải thu thập từng ứng dụng và tự biên dịch

- Là một bản phân phối phi thương mại và là một trong những bản phân phối ra đời sớm nhất, duy trì bởi một cộng đồng phát triển tình nguyện với một cam kết mạnh mẽ cho nguyên tắc phần mềm miễn phí và quản lý dự án dân chủ. 

- Có 3 dạng khác nhau: 

  - Phiên bản ổn định mà người dùng được khuyến khích sử dụng.

  - Phiên bản không ổn định.

  - Phiên bản thử nghiệm cho những ai mong muốn có được phần mềm mới nhất.

- Hệ thống gói quản lý phần mềm sử dụng: 

  - **`dpkg `** cài đặt các gói phần mềm .deb 

  - **`apt`** cài đặt phần mềm từ các kho trên mạng. 

Debian có chính sách nghiêm ngặt đối với chất lượng các gói và bản phát hành cũng như tiến trình phát triển và kiểm tra mở. Cách này giúp cho việc nâng cấp các bản phát hành cũng như việc đặt hay gỡ bỏ dễ dàng hơn.

- Có khá nhiều distro phát triển dựa trên distro Debian như: Raspbian, Knoppix, Astra Linux, Kali Linux, ... và phổ biến nhất là nhánh **Ubuntu**

<a name="2.2"></a>
### 2.2 Ubuntu

<img src="http://imgur.com/7FhdGO1.png"  hight="700px" width="300px"> 

\-  Do công ty Canonical phân phối chỉ mới xuất hiện vào quý 3/2004 và không lâu sau đó HĐH này đã trở nên phổ biến, uy tín về chất lượng và dễ dàng sử dụng.

\- Dựa trên hệ thống quản lý gói mạnh mẽ **APT** của Debian, nhắm đến đối tượng người dùng đầu cuối, nhỏ gọn chỉ với 1 đĩa cài đặt. Người dùng Ubuntu có thể cảm nhận được sự tự do, tùy biến cao trong sử dụng, quản lý hệ thống. 

\- Theo thống kê của trang [Distrowatch](https://distrowatch.com/), cho đến hiện nay Ubuntu là distro phổ biến nhất với khoảng hơn 2.000 lượt người truy cập/ngày.

\- Cứ 6 tháng, Ubuntu sẽ ra bản phát hành mới, còn với các phiên bản Long Term Support (LTS) thì việc cập nhật trình bảo mật sẽ từ 3 đến 5 năm.

\- Cách đặt tên của Ubuntu theo định dạng YY.MM trong đó YY là năm phát hành và MM là tháng phát hành. 

\- Ubuntu sử dụng giao diện đồ họa thân thiện GNOME, hướng đến sự đơn giản hóa trong quá trình sử dụng. Ngoài ra, Ubuntu còn có bộ ứng dụng văn phòng OpenOffice, trình duyệt Firefox, trình gửi tin nhắn tức thời Pidgin, trình biên tập đồ họa GIMP…

  - Ngoài Ubuntu, các nhà phát triển còn sản sinh ra các distro mang hơi hướng tương tự Ubuntu như **Kubuntu**, **Xubuntu** và **Lunbuntu**, **Linux Mint**. Các distro này chủ yếu khác biệt với Ubuntu ở giao diện màn hình.

<a name="2.3"></a>
## 2.3 Red Hat Enterprise linux (RHEL) và Fedora 

<img src="http://imgur.com/2YngFp8.png">


- Là một bản phân phối cộng đồng được ***"đỡ đầu"*** bởi một công ty của Mỹ - Red Hat. Nó được tạo ra nhằm kiểm thử các công nghệ cho một bản phân phối thương mại khác của Red Hat - nơi mà các phần mềm nguồn mở mới được tạo lập, phát triển và kiểm thử trong môi trường cộng đồng trước khi được đưa vào Red Hat Enterprise Linux.

- Red Hat Enterprise Linux là phiên bản kế thừa của Red Hat Linux, một trong những bản Linux cũ nhất. Phiên bản gốc được phát hành năm 1995 và được thay thế bởi Red Hat Enterprise Linux năm 2003. Đây là một bản phân phối trả phí và dành cho người dùng doanh nghiệp
	
	<img src="https://access.redhat.com/sites/default/files/video/thumbnails/rhel7_docker_overview_tn.jpg">

- Fedora là phiên bản miễn phí thay thế, dành cho người dùng gia đình. Nó có nhiều tính năng của RHEL và một số tính năng thử nghiệm chưa được triển khai trong RHEL. Cả hai phiên bản này đều sử dụng định dạng gói .rmp, do đó các phần mềm từ các bản phân phối khác như Debian không thể chạy trên distro này


- Chu kì ra phiên bản mới của Fedora là 6 tháng. Phiên bản mới với các tính năng bảo mật mà các chuyên gia đánh giá khá tốt.

- Có thể nâng cấp lên phiên bản mới mà không cần cài đặt lại.

- Dùng **`yum`** để quản lý các gói phần mềm định dạng .rpm

-  Fedora có thể dùng cho máy tính để bàn và máy trạm, thậm chí máy chủ; dành cho những người mới tiếp cận PMTDNM hay những người đã có nhiều kinh nghiệm. 

- 2 distro phổ biến nhất được phát triển dựa trên Fedora là **Red Hat Enterprise Linux** - với đối tượng hướng tới là các doanh nghiệp và công ty lớn (tất nhiên là có tính phí) ; và **CentOS** - free và hướng tới đối tượng là người sử dụng cá nhân.

<a name="2.4"></a>
## 2.4 CentOS
- CentOS là một Linux distribution mã nguồn mở dựa trên linux kernel. Nó có nguồn gốc hoàn toàn từ bản phân phối Redhat Enterprise Linux(RHEL), bản được dùng nhiều nhất trong giới doanh nghiệp thế giới IT . CentOS cũng là một hệ điều hành cap cấp được hỗ trợ bởi chính cộng đồng của nó và được phát hành năm 2004. 
- Dễ dàng tùy chỉnh,bảo mật ổn định, có nhiều cấp độ bảo mật chuẩn doanh nghiệp, khiến nó trở thành lựa chọn an toàn cho người dùng .


<a name="2.5"></a>
## 2.5 Slackware

- Được Patrick Volkerding phát hành vào năm 1992, Slackware là bản phân phối Linux tồn tại lâu đời nhất và cho đến giữa những năm 1990, nó chiếm khoảng 80% trong tổng số bản phân phối được sử dụng. Tuy nhiên mọi thứ đã thay đổi khi Red Hat Linux xuất hiện và ngày nay Slackware không còn nổi tiếng như xưa. Lý do không phải là do nó không tốt, trái lại nó vẫn là một trong những distro Linux hàng đầu nhưng Slackware có khả năng tùy chỉnh cao và mạnh mẽ, không thân thiện với người dùng. Chính điều này ảnh hưởng đến sự phổ biến của nó. Slackware sử dụng hệ thống gói pkgtools, không có kho lưu trữ gói chính thức và có rất nhiều cấu hình phải thực hiện thủ công
			<img src="https://i.ytimg.com/vi/TtMNuaiqnYw/maxresdefault.jpg">
			

<a name="3"></a>
# 3.Các nhóm Distro phổ biến

- Linux có hàng trăm bản distro khác nhau đủ để phù hợp với nhu cầu của nhiều đối tượng sử dụng: từ người mới bắt đầu tới những người đã có hiểu biết chuyên sâu.
 
  - Với người sử dụng cá nhân thì các distro phổ biến là: Ubuntu, Linux Mint, Arch Linux, CentOS, Fedora, openSuSE ...

  - Với đối tượng sử dụng là hệ thống sever có thể kể đến như là : Red Hat Enterprise Linux, Ubuntu Server, CentOS, SUSE Enterprise Linux.. 

- Dựa trên các quy tắc, định hướng cũng như là mục tiêu mà Linux chia các distro phổ biến thành 4 nhóm: 

  - **Nhóm 1**: 
    - Nhắm vào người dùng am hiểu về hệ thống Linux. Hầu hết phương thức xây dựng và cấu hình hệ thống đều phải thực hiện qua môi trường dòng lệnh.

    - Đặc điểm: cấu trúc gọn nhẹ, uyển chuyển để có thể xây dựng một hệ thống hoàn toàn tuân theo ý của mình.

    - Các distro tiêu biểu: Arch, Gentoo, Slackware.

  - **Nhóm 2**: 
    - Nhắm vào những người dùng am hiểu hệ thống, tuy nhiên cung cấp nhiều công cụ hơn cho những người chưa thật sự hiểu rõ hoàn toàn về Linux. 
    
    - Nhóm này tương đối thân thiện với người dùng mới bắt đầu hơn nhóm 1. Tuy nhiên, các distro nhóm này lại có một quy trình phát triển và kiểm tra chất lượng các gói phần mềm cực kì khắt khe so với các distro còn lại. 
    
    - Để trở thành một lập trình viên chính thức của Debian hay Fedora cần phải có thời gian đóng góp khá dài, và phải được chứng nhận bởi các lập trình viên khác. Do vậy, môi trường để lập trình và nghiên cứu ở 2 distro này khá tốt.

    - Distro tiêu biểu: Debian và Fedora. 

  - **Nhóm 3**: 
    - Chủ yếu nhắm vào thị trường doanh nghiệp, cơ quan, thị trường máy chủ… Các dòng distro này có nhiều đặc tính phù hợp cho mảng thị trường đòi hỏi sự ổn định cao như: thời gian ra phiên bản mới thường khá lâu, 3 – 5 năm tùy distro

    - Ít sử dụng các công nghệ mới nhất, thường tập trung phát triển các công nghệ lâu đời và đáng tin cậy.

    - Distro tiêu biểu: Centos, RHEL, SUSE EL...

  - **Nhóm 4**: 
    - Nhắm đến người dùng cuối và người mới bắt đầu sử dụng Linux.

    - Đặc tính của các distro này là thời gian phát hành ngắn, ứng dụng liên tục các công nghệ mới với nhiều công cụ đồ họa để cấu hình hệ thống, thiết kế với mục đích dễ dùng, dễ làm quen, không cần đọc tài liệu đối với người mới.

    - Distro tiêu biểu: Ubuntu, Open SUSE, Linux Mint.

    - **Bảng so sánh - CentOS và Ubuntu** -
    |Ubuntu|CentoS|
    |:------|:-------|
    |Dựa trên Debian|Dựa trên nền RHEL|
    |Cập nhật thường xuyên|Cập nhật quan trọng|
    |Không hỗ trợ Cpanel( có phương pháp thế )|Hỗ trợ Cpanel/WHM|
    |Cộng đồng người dùng lập trình viên lớn|Cộng đồng người dùng lập trình viên nhỏ hơn |
    |Dễ học cho người mới dùng, và có bản Ubuntu desktop phổ biến|Khó học cho người mới và không có bản desktop phổ biến|
    |Sử dụng **apt-get** package manager để cài đặt .deb packages|Dùng lệnh **yum** pakckage manager để cài .rpm packages|

## Tổng quan lại: Các distro của Linux được mô tả như hình sau:

<img src="http://imgur.com/gXpAMgY.png"> 
