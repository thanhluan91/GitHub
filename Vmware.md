# Vmware

 I. **Giới thiệu**
 -
 **VMware Inc.** là một công ty phần mềm lớn vốn thuộc tập đoàn [EMC](https://vi.wikipedia.org/wiki/EMC_Corporation "EMC Corporation") chuyên làm [phần mềm](https://vi.wikipedia.org/wiki/Ph%E1%BA%A7n_m%E1%BB%81m "Phần mềm") tạo máy ảo cho các hệ thống [máy tính](https://vi.wikipedia.org/wiki/M%C3%A1y_t%C3%ADnh "Máy tính") tương thích chip x86 của [Intel](https://vi.wikipedia.org/wiki/Intel "Intel"). Sản phẩm chính của công ty bao gồm phần mềm ảo hóa [VMware Workstation](https://vi.wikipedia.org/w/index.php?title=VMware_Workstation&action=edit&redlink=1 "VMware Workstation (trang chưa được viết)") cho máy tình để bàn và [VMware ESX server](https://vi.wikipedia.org/w/index.php?title=VMware_ESX_server&action=edit&redlink=1 "VMware ESX server (trang chưa được viết)"), [VMware GSX server](https://vi.wikipedia.org/w/index.php?title=VMware_GSX_server&action=edit&redlink=1 "VMware GSX server (trang chưa được viết)") cho máy chủ. Các phần mềm tạo máy ảo của VMware được coi là tốt nhất trên thế giới bởi nó hỗ trợ nhiều hệ điều hành khác nhau như [GNU/Linux](https://vi.wikipedia.org/wiki/Linux "Linux"), [Mac OS X](https://vi.wikipedia.org/wiki/Mac_OS_X "Mac OS X") và [Microsoft Windows](https://vi.wikipedia.org/wiki/Microsoft_Windows). Các phần mềm máy ảo khác như [Virtual PC](https://vi.wikipedia.org/w/index.php?title=Virtual_PC&action=edit&redlink=1 "Virtual PC (trang chưa được viết)") chỉ hoạt động trên hệ điều hành [Microsoft Windows](https://vi.wikipedia.org/wiki/Microsoft_Windows "Microsoft Windows"). Đặc biệt VMware là công ty hàng đầu cung cấp các giải pháp ảo hóa cho các trung tâm dữ liệu với các sản phẩm như: VMware vSphere, VMware vCloud, VMware Director,....


II. **Vmware workstation** 

 1. Máy ảo là gì ?
    Máy ảo (Virtual Machine - VM) được xem là một chương trình máy tính ( Client ) được chạy trên một hệ điều hành chủ ( Host ) và hoạt động giống như một máy tính thật , tức  là hệ điều hành và phần mềm hỗ trợ chia sẻ tài nguyên phần cứng của máy thật để máy ảo hoạt động.
    
    Các thành phần của máy ảo  

    ![](https://imgur.com/a/YTFYDkt)

    - Một máy ảo sẽ có những thành phần giống như một máy thật chẳng hạn như  CPU , RAM , HDD , CARD  mạng hay ổ DVD ......
    

![](https://i.imgur.com/XJCJb6d.png) 

Một máy thật có thể chạy được nhiều máy ảo khác nhau cùng lúc tùy thuộc vào khả năng đáp ứng phần cứng của chính máy thật đó.

**2. cách chạy các OS khác bằng máy ảo trên mính tính**

 Như đã giải thích ở trên, anh em có thể chạy 1 hệ điều hành bất kì nào khác trên chính cái máy tính của mình. Mình sẽ hướng dẫn sơ qua cho anh em thấy được các mà mình tạo các máy ảo như thế nào:

- Trên Windows:
Để tạo máy ảo, anh em tải về hai phần mềm ở trên, mình sẽ hướng dẫn bằng VMWare nhé.
 Anh em chọn File / New Virtual Machine, anh em có thể chọn Typical hoặc Custom tùy ý (Nếu anh em có thể sẽ chép cái máy ảo này đi máy khác sử dụng thì nên chọn custom, rồi chọn phiên bản thấp 1 tí cho dễ nhé)
 như mình đang chạy phiên bản `vmware wokstation pro12`  
  

![](https://i.imgur.com/BSXOSvo.png)

Tiếp theo là phần chọn hệ điều hành, như mình nói, anh em có thể chọn rát nhiều hệ điều hành khác nhau như Ubuntu, Solaris, Windows....  
  

![Đang tải 5.JPG…](https://photo2.tinhte.vn/data/attachment-files/2018/10/4440479_5.jpg "5.JPG")

-	Các hệ điều hành có thể tạo trên một máy ảo  
​

Bước tiếp theo sẽ là đặt tên cho máy ảo và vị trí lưu trữ của nó  
  

![Đang tải 7.JPG…](https://photo2.tinhte.vn/data/attachment-files/2018/10/4440481_7.jpg "7.JPG")  

-	Chọn nơi lưu trữ cho máy ảo​

Sau đó anh em có thể chọn dung lượng ổ cứng cho máy cũng như tùy biến lại các thông số như RAM, CPU... tùy theo khả năng mà máy thật của anh em có thể cung cấp  
  

![Đang tải 8.JPG…](https://photo2.tinhte.vn/data/attachment-files/2018/10/4440482_8.jpg "8.JPG")

-	Chọn dung lượng ổ cứng  
  
![Đang tải 9.JPG…](https://photo2.tinhte.vn/data/attachment-files/2018/10/4440483_9.jpg "9.JPG")​
-	Chọn dung lượng Ram 

Sau đó bấm finish là xong, chỉ vậy thôi, quá trình chạy máy ảo, nó sẽ tốn tài nguyên như lúc anh em cấu hình, còn việc cài đặt thì anh em có thể làm như một cái máy tính bình thường khác.  
  
![Đang tải 10.JPG…](https://photo2.tinhte.vn/data/attachment-files/2018/10/4440484_10.jpg "10.JPG")  

_Màn hình cài đặt máy ảo tương tự như máy thật Ubuntu_​

III. Networking Vmware

Để xem các card mạng đã có trong VMware Workstation ta chỉ cần bật VMware lên, chọn Edit => Virtual Network Editor

![](https://i.imgur.com/ZLzcEsW.png)

Ta có thể thấy trong hình card bridge có tên là VMnet0, card Nat có tên là VMnet8 , Host-only VMnet1

Card bridge không có địa chỉ IP do nó sẽ sử dụng dải IP của máy thật. VMware sẽ tự sinh một dải IP và gán cho VMnet8. Trong trường hợp của tôi là dải 10.10.0.0/24.
-* car mạng Bridgerd

Use bridged connection: cho phép card mạng máy ảo kết nối trực tiếp với card mạng máy thật, giống như khi chúng được kết nối vào chung một  switch. Khi đó, địa chỉ IP của máy ảo phải nằm cùng subnet với địa chỉ IP mà card mạng máy thật đang dùng. Đây là lựa chọn thường được sử dụng nhiều nhất khi tạo một mạng máy tính ảo.

Use network address translation (NAT): máy ảo sẽ nằm ở một vùng địa chỉ IP khác và phải thực hiện việc kỹ thuật chuyển đổi địa chỉ (NAT) khi liên lạc với máy tính bên ngoài.

Use host-only networking: máy tính ảo sẽ kết nối với máy tính thật bằng một vùng mạng riêng, nhưng không liên lạc được với bên ngoài.

## 1. Các thao tác với một card mạng ảo trong VMware Workstation

### 1.1. Thêm, xóa một vmnet

##### Thêm một vmnet

Cũng trong Virtual Network Editor ta chọn như sau:

![](https://i.imgur.com/HOhmzkr.png)

-   Bước 1: chọn Add Network
-   Bước 2: chọn card cần add thêm (ở đây là VMnet10)
-   Bước 3: ấn OK

Lúc này trên cửa sổ Virtual Network Editor sẽ xuất hiện thêm card VMnet1 và được gắn tự động một dải IP, như hình dưới đây:

![](https://i.imgur.com/nog7IBA.png)

Làm tương tự để add thêm các vmnet tiếp theo.

##### Xóa một vmnet

Trong Virtual Network Editor chọn một vmnet và ấn Remove Network (button cạnh Add Network)
![](![](https://i.imgur.com/e6GoDz1.png))

### 1.2. Sửa dải IP của một vmnet

Có thể thấy các dải IP mà VMware tự sinh ra và gắn cho các card mạng rất khó nhớ. Ta có thể thay đổi dải IP này bằng cách ấn vào vmnet muốn đổi địa chỉ.

Trong dòng Subnet IP chọn dải IP và subnet muốn thay đổi.

![](https://i.imgur.com/nog7IBA.png)

- Cài đặt subnet : 192.168.220.0/24

Click Apply và OK

### 1.3. Cấu hình DHCP

Các card mạng này có thể cấp DHCP cho các máy ảo sử dụng nó.

để làm việc này ta ấn vào DHCP Settings, sau đó chọn dải IP dùng để cấp DHCP

![](https://i.imgur.com/ynbSglH.png)

- Cấp DHCP 	 từ 192.168.220.10 đến 192.168.220.50 

#### 1.4 Khởi tạo máy ảo theo cấu hình 

- 2 cpu
- 2GB RAM
- ổ cứng 20 GB
- Không có card sound
- không có cổng usb	
-  card mạng ra internet

![](https://i.imgur.com/6fqMhOl.png)

##### 1.5 Khởi tạo snapshot 

![](https://i.imgur.com/fjwdjjM.png)
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTE0MjcyNTAzMSwtMjA0MTkyODA4NywtMT
Q3MTQ1ODU4OCwtMTM4OTUyMDksOTE2NjcxMjc0LC0xMDE2NDI5
MTE0LC0xMTI2MDUwOTUzLC0yNzExMjcwNTEsMjAzODU0MDI2Mi
wyMDQ5OTE0OTg4LDI5OTcwOTU1NSwyMDQwMjk3NjIyXX0=
-->