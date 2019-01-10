# Vmware

 I. **Giới thiệu**
 -
 **VMware Inc.** là một công ty phần mềm lớn vốn thuộc tập đoàn [EMC](https://vi.wikipedia.org/wiki/EMC_Corporation "EMC Corporation") chuyên làm [phần mềm](https://vi.wikipedia.org/wiki/Ph%E1%BA%A7n_m%E1%BB%81m "Phần mềm") tạo máy ảo cho các hệ thống [máy tính](https://vi.wikipedia.org/wiki/M%C3%A1y_t%C3%ADnh "Máy tính") tương thích chip x86 của [Intel](https://vi.wikipedia.org/wiki/Intel "Intel"). Sản phẩm chính của công ty bao gồm phần mềm ảo hóa [VMware Workstation](https://vi.wikipedia.org/w/index.php?title=VMware_Workstation&action=edit&redlink=1 "VMware Workstation (trang chưa được viết)") cho máy tình để bàn và [VMware ESX server](https://vi.wikipedia.org/w/index.php?title=VMware_ESX_server&action=edit&redlink=1 "VMware ESX server (trang chưa được viết)"), [VMware GSX server](https://vi.wikipedia.org/w/index.php?title=VMware_GSX_server&action=edit&redlink=1 "VMware GSX server (trang chưa được viết)") cho máy chủ. Các phần mềm tạo máy ảo của VMware được coi là tốt nhất trên thế giới bởi nó hỗ trợ nhiều hệ điều hành khác nhau như [GNU/Linux](https://vi.wikipedia.org/wiki/Linux "Linux"), [Mac OS X](https://vi.wikipedia.org/wiki/Mac_OS_X "Mac OS X") và [Microsoft Windows](https://vi.wikipedia.org/wiki/Microsoft_Windows). Các phần mềm máy ảo khác như [Virtual PC](https://vi.wikipedia.org/w/index.php?title=Virtual_PC&action=edit&redlink=1 "Virtual PC (trang chưa được viết)") chỉ hoạt động trên hệ điều hành [Microsoft Windows](https://vi.wikipedia.org/wiki/Microsoft_Windows "Microsoft Windows"). Đặc biệt VMware là công ty hàng đầu cung cấp các giải pháp ảo hóa cho các trung tâm dữ liệu với các sản phẩm như: VMware vSphere, VMware vCloud, VMware Director,....


II. **Vmware workstation**

 1. Máy ảo là gì ?
    Máy ảo (Virtual Machine - VM) được xem là một chương trình máy tính ( Client ) được chạy trên một hệ điều hành chủ ( Host ) và hoạt động giống như một máy tính thật , tức  là hệ điều hành và phần mềm hỗ trợ chia sẻ tài nguyên phần cứng của máy thật để máy ảo hoạt động.
    
    - Một máy ảo sẽ có những thành phần giống như một máy thật chẳng hạn như  CPU , RAM , HDD , CARD  mạng hay ổ DVD ......
    
 [Các thành phần của máy ảo ](https://imgur.com/a/YTFYDkt)

![than](https://i.imgur.com/XJCJb6d.png) 

Một máy thật có thể chạy được nhiều máy ảo khác nhau cùng lúc tùy thuộc vào khả năng đáp ứng phần cứng của chính máy thật đó.
**2. cách chạy các OS khác bằng máy ảo trên mính tính**
 Như đã giải thích ở trên, anh em có thể chạy 1 hệ điều hành bất kì nào khác trên chính cái máy tính của mình. Mình sẽ hướng dẫn sơ qua cho anh em thấy được các mà mình tạo các máy ảo như thế nào:

- Trên Windows:
Để tạo máy ảo, anh em tải về hai phần mềm ở trên, mình sẽ hướng dẫn bằng VMWare nhé.
 Anh em chọn File / New Virtual Machine, anh em có thể chọn Typical hoặc Custom tùy ý (Nếu anh em có thể sẽ chép cái máy ảo này đi máy khác sử dụng thì nên chọn custom, rồi chọn phiên bản thấp 1 tí cho dễ nhé)  
  

![Đang tải 3.JPG…](https://photo2.tinhte.vn/data/attachment-files/2018/10/4440475_3.jpg "3.JPG")  
​

Tiếp theo là phần chọn hệ điều hành, như mình nói, anh em có thể chọn rát nhiều hệ điều hành khác nhau như Ubuntu, Solaris, Windows....  
  

![Đang tải 5.JPG…](https://photo2.tinhte.vn/data/attachment-files/2018/10/4440479_5.jpg "5.JPG")  
_Các hệ điều hành có thể tạo trên một máy ảo  
_​

Bước tiếp theo sẽ là đặt tên cho máy ảo và vị trí lưu trữ của nó  
  

![Đang tải 7.JPG…](https://photo2.tinhte.vn/data/attachment-files/2018/10/4440481_7.jpg "7.JPG")  
_Chọn nơi lưu trữ cho máy ảo_​

Sau đó anh em có thể chọn dung lượng ổ cứng cho máy cũng như tùy biến lại các thông số như RAM, CPU... tùy theo khả năng mà máy thật của anh em có thể cung cấp  
  

![Đang tải 8.JPG…](https://photo2.tinhte.vn/data/attachment-files/2018/10/4440482_8.jpg "8.JPG")  
_Chọn dung lượng ổ cứng_  
  
![Đang tải 9.JPG…](https://photo2.tinhte.vn/data/attachment-files/2018/10/4440483_9.jpg "9.JPG")​

Sau đó bấm finish là xong, chỉ vậy thôi, quá trình chạy máy ảo, nó sẽ tốn tài nguyên như lúc anh em cấu hình, còn việc cài đặt thì anh em có thể làm như một cái máy tính bình thường khác.  
  
![Đang tải 10.JPG…](https://photo2.tinhte.vn/data/attachment-files/2018/10/4440484_10.jpg "10.JPG")  

_Màn hình cài đặt máy ảo tương tự như máy thật Ubuntu_​
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTk1MDc1NDkwMywyMDM4NTQwMjYyLDIwND
k5MTQ5ODgsMjk5NzA5NTU1LDIwNDAyOTc2MjJdfQ==
-->