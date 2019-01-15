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

!![](https://i.imgur.com/ZLzcEsW.png)

Ta có thể thấy trong hình card bridge có tên là VMnet0, card Nat có tên là VMnet8 , Host-only VMnet1

Card bridge không có địa chỉ IP do nó sẽ sử dụng dải IP của máy thật. VMware sẽ tự sinh một dải IP và gán cho VMnet8. Trong trường hợp của tôi là dải 10.10.0.0/24.

## 2. Các thao tác với một card mạng ảo trong VMware Workstation

### 2.1. Thêm, xóa một vmnet

##### Thêm một vmnet

Cũng trong Virtual Network Editor ta chọn như sau:

![](https://i.imgur.com/HOhmzkr.png)

-   Bước 1: chọn Add Network
-   Bước 2: chọn card cần add thêm (ở đây là VMnet10)
-   Bước 3: ấn OK

Lúc này trên cửa sổ Virtual Network Editor sẽ xuất hiện thêm card VMnet1 và được gắn tự động một dải IP, như hình dưới đây:

[![](https://camo.githubusercontent.com/5ed4c02e4de5da0bb048bf66ac48b2bd2aa4f965/687474703a2f2f692e696d6775722e636f6d2f4b3644435347382e706e67)](https://camo.githubusercontent.com/5ed4c02e4de5da0bb048bf66ac48b2bd2aa4f965/687474703a2f2f692e696d6775722e636f6d2f4b3644435347382e706e67)

Làm tương tự để add thêm các vmnet tiếp theo.

##### Xóa một vmnet

Trong Virtual Network Editor chọn một vmnet và ấn Remove Network (button cạnh Add Network)

### 2.2. Sửa dải IP của một vmnet

Có thể thấy các dải IP mà VMware tự sinh ra và gắn cho các card mạng rất khó nhớ. Ta có thể thay đổi dải IP này bằng cách ấn vào vmnet muốn đổi địa chỉ.

Trong dòng Subnet IP chọn dải IP và subnet muốn thay đổi.

[![](https://camo.githubusercontent.com/a22f66e3d1e68b1a65cdf7edc5636073c4f74478/687474703a2f2f692e696d6775722e636f6d2f386139506a6f432e706e67)](https://camo.githubusercontent.com/a22f66e3d1e68b1a65cdf7edc5636073c4f74478/687474703a2f2f692e696d6775722e636f6d2f386139506a6f432e706e67)

Click Apply và OK

### 2.3. Cấu hình DHCP

Các card mạng này có thể cấp DHCP cho các máy ảo sử dụng nó.

để làm việc này ta ấn vào DHCP Settings, sau đó chọn dải IP dùng để cấp DHCP

[![](https://camo.githubusercontent.com/12d6ecf547ea042eca943d478ee251b18f864622/687474703a2f2f692e696d6775722e636f6d2f526267484b50452e706e67)](https://camo.githubusercontent.com/12d6ecf547ea042eca943d478ee251b18f864622/687474703a2f2f692e696d6775722e636f6d2f526267484b50452e706e67)

### 2.4. Cách thêm một card mạng vào máy ảo

Ví dụ ở đây tôi có một máy ảo Ubuntu Server gắn sẵn một card bridge khi tạo máy ảo.

Show IP trên máy ảo:

[![](https://camo.githubusercontent.com/10545216908ab7b65329db9e760654a30069532d/687474703a2f2f692e696d6775722e636f6d2f61544d576955452e706e67)](https://camo.githubusercontent.com/10545216908ab7b65329db9e760654a30069532d/687474703a2f2f692e696d6775722e636f6d2f61544d576955452e706e67)

Thêm card mạng thứ 2 vào máy ảo bằng cách vào Edit Virtual Machine Settings, chọn Add => Network và làm theo hình dưới:

[![](https://camo.githubusercontent.com/3c1221bf4005c1ba642d6cd315994ace12c00192/687474703a2f2f692e696d6775722e636f6d2f547833436664322e706e67)](https://camo.githubusercontent.com/3c1221bf4005c1ba642d6cd315994ace12c00192/687474703a2f2f692e696d6775722e636f6d2f547833436664322e706e67)

Xin cấp IP cho card mạng mới trên máy ảo bằng lệnh _**dhclient eth1**_

IP của máy ảo sau khi thực hiện xong (đã có thêm card eth1):

[![](https://camo.githubusercontent.com/618580711bc4f1fdca4b78ea6dc9b206a6ea8e65/687474703a2f2f692e696d6775722e636f6d2f71664c454566632e706e67)](https://camo.githubusercontent.com/618580711bc4f1fdca4b78ea6dc9b206a6ea8e65/687474703a2f2f692e696d6775722e636f6d2f71664c454566632e706e67)

Đối với trường hợp muốn thay đổi từ card bridge (hoặc nat hoặc vmnet) sang card khác thì chỉ cần chọn vào card cần đổi và làm như bước 3 bên trên (không add thêm card mới)

## 3. Kinh nghiệm bản thân

### 3.1. Đặt thứ tự và cấu hình trước địa chỉ IP các vmnet trước khi lab

Trước đây khi làm một bài lab, tôi thường lao thẳng vào cài máy ảo luôn, sau đó mới xem địa chỉ IP cửa mỗi vmnet rồi đặt IP tĩnh hoặc xin cấp IP bằng cho máy ảo.

Nhưng với một bài lab lớn, sử dụng khoảng 3,4 máy ảo (ví dụ như bài lab firewall, định tuyến, cloud coputing,...) thì việc làm như trên là một sai lầm.

Các địa chỉ IP của tôi rối loạn hết lên, topo lằng nhằng, không thể thông nổi mạng chứ đừng nói đến chuyện cấu hình các thứ khác.

Sau một thời gian tôi đã tự quy hoạch lại các vmnet mình sử dụng, như add thêm các vmnet, đặt lại dải IP cho các vmnet cho dễ nhớ (vmnet1 dải 10.10.10.0/24, vmnet2 dải 10.10.20.0/24,...)

Việc làm này chỉ mất công có một lần, từ các lần sau khi tạo máy ảo bằng VMware tôi chỉ cần add các vmnet mong muốn theo đúng topo là xong

Việc cấu hình và sửa lỗi cũng trở nên dễ dàng hơn do tôi đã thuộc luôn các địa chỉ IP

Các bạn có thể tham khảo cấu hình các vmnet của tôi như hình dưới đây:

[![](https://camo.githubusercontent.com/64d3910905ea84365ebb7a33cdb36e0101c1e64a/687474703a2f2f692e696d6775722e636f6d2f73664a766f466b2e706e67)](https://camo.githubusercontent.com/64d3910905ea84365ebb7a33cdb36e0101c1e64a/687474703a2f2f692e696d6775722e636f6d2f73664a766f466b2e706e67)

Các card vmnet1, vmnet2, vmnet3 là các card tôi thêm vào.

Các card vmnet0, vmnet8 là các card mặc định đã trình bày ở trên.

### 3.2. Xây dựng mô hình lab hoàn chỉnh trên giấy rồi mới thực hiện trên VMware

Như ví dụ tôi đã trình bày ở phần 3.1, việc lập một topo lab là một việc cực quan trọng.

Trong topo cần chỉ rõ card vmnet nào nối với máy ảo nào, các IP của các interface máy ảo.

##### _Chú ý_: các máy ảo sử dụng chung một vmnet thì cần cùng dải IP với vmnet đó. Ví dụ hai máy ảo của tôi là Win XP và CentOS cùng sử dụng vmnet1 thì 2 máy ảo này phải có IP cùng dải 10.10.10.0. Nếu không đúng như thế thì mạng sẽ không thông.

Ví dụ mô hình Lab OpenStack All in one:

[![](https://camo.githubusercontent.com/a4fc88bf06f26acab72687b9aef973579806bcec/687474703a2f2f692e696d6775722e636f6d2f596378615268502e706e67)](https://camo.githubusercontent.com/a4fc88bf06f26acab72687b9aef973579806bcec/687474703a2f2f692e696d6775722e636f6d2f596378615268502e706e67)

### 3.3. Cách lab kết hợp giữa GNS3 và VMware Workstation

GNS3 thì chắc hẳn ai cũng biết. Một trong những cái hay của GNS3 mà tôi thấy đó là nó có thể kết nối với các card mạng có trong máy (vmnet, ethernet, wireless)

Thông qua các card mạng này ta có thể kết nối trức tiếp các máy ảo trong VMware Workstation hoặc chính máy thật với các thiết bị mạng (Router, SW,...) trong GNS3

Trong mục này tôi sẽ lấy một ví dụ sử dụng một Router trong GNS3 và kết nối tới một máy PC trong VMware Workstation 10.

Máy ảo XP sẽ kết nối tới Router bằng card mạng vmnet1.

Trên GNS3 ta kéo vào topo một PC và một Router (với giả thiết Router GNS3 đã có IOS).

[![](https://camo.githubusercontent.com/0ea1aa3abca15cc226b6a3e7f92c9324a88e5288/687474703a2f2f692e696d6775722e636f6d2f7a4176685153642e706e67)](https://camo.githubusercontent.com/0ea1aa3abca15cc226b6a3e7f92c9324a88e5288/687474703a2f2f692e696d6775722e636f6d2f7a4176685153642e706e67)

Click vào biểu tượng kết nối (hình RJ45 bên góc trái) và ấn vào PC. Sau đó chọn đến card VMnet1

[![](https://camo.githubusercontent.com/0b180e23088483f5bd3c7581396ef3ec86f4872a/687474703a2f2f692e696d6775722e636f6d2f5a73474a4d436f2e706e67)](https://camo.githubusercontent.com/0b180e23088483f5bd3c7581396ef3ec86f4872a/687474703a2f2f692e696d6775722e636f6d2f5a73474a4d436f2e706e67)

Đầu dây còn lại nối vào cổng f0/0 của Router.

[![](https://camo.githubusercontent.com/ab1f55245a0423bbdfba8b705775b00ec8895d8f/687474703a2f2f692e696d6775722e636f6d2f394872375156442e706e67)](https://camo.githubusercontent.com/ab1f55245a0423bbdfba8b705775b00ec8895d8f/687474703a2f2f692e696d6775722e636f6d2f394872375156442e706e67)

Trên VMware Workstation chọn máy ảo XP => Edit Virtual Machine Settings và chọn card mạng là vmnet1 như hình sau:

[![](https://camo.githubusercontent.com/ac59236af4eee5ef3ede602ee023dbd8dd1826cd/687474703a2f2f692e696d6775722e636f6d2f675368435051742e706e67)](https://camo.githubusercontent.com/ac59236af4eee5ef3ede602ee023dbd8dd1826cd/687474703a2f2f692e696d6775722e636f6d2f675368435051742e706e67)

Sau đó bật máy ảo và kiểm tra IP thấy máy ảo có IP thuộc dải IP của vmnet1.

[![](https://camo.githubusercontent.com/180e244c72d4a04aa76e54f23f171c12c62bac85/687474703a2f2f692e696d6775722e636f6d2f61546f466264312e706e67)](https://camo.githubusercontent.com/180e244c72d4a04aa76e54f23f171c12c62bac85/687474703a2f2f692e696d6775722e636f6d2f61546f466264312e706e67)

Trên GNS3 ta click vào Router, một cửa sổ console hiện lên và thực hiện các lệnh sau để cấu hình IP cho card mạng f0/0

```
configure terminal
interface f0/0
ip address 10.10.10.140 255.255.255.0
no shutdown

```

Trên máy ảo ta ping đến địa chỉ 10.10.10.140 của Router thì thấy thành công.

[![](https://camo.githubusercontent.com/ad0b3b67af435d53c5bd9bdb0644c8ead7e4edae/687474703a2f2f692e696d6775722e636f6d2f6679773761765a2e706e67)](https://camo.githubusercontent.com/ad0b3b67af435d53c5bd9bdb0644c8ead7e4edae/687474703a2f2f692e696d6775722e636f6d2f6679773761765a2e706e67)

Quá trình kết nối PC và Router thành công.

##### Lưu ý:

-   Nhiều trường hợp cần chạy GNS3 với quyền Admin thì nó mới nhận được các card vmnet.
-   Với GNS3 muốn sử dụng các router thì các router này cần IOS.
-   Đây chỉ là một ví dụ đơn giản, với các bài lab kết hợp phức tạp hơn cần phải xây dựng mô hình trước.

### 3.4. Cách thêm nhiều card mạng cho máy ảo

Trong nhiều trường hợp một máy ảo cần phải add nhiều card mạng vmnet.

Nếu các card vmnet này được add cùng một lúc khi khởi tạo máy ảo thì sau này khi đặt IP cho các interface của máy ảo có thể xảy ra hiện tượng ** đảo IP hai interface** rất khó chịu và khó khăn trong việc sửa lỗi.

#### _GIẢI PHÁP_: add từng card mạng cho máy ảo, ví dụ add xong card vmnet1 ta phải click "Finish" rồi "OK" để thoát hẳn ra ngoài. Sau đó "Edit Virtual Machine Settings" rồi add thêm card vmnet2 => Finish => OK. Lặp lại như vậy để add các card mạng tiếp theo.

### 3.5. Cách thay đổi địa chỉ Gateway cho card mạng NAT

Giả sử ta cần làm một bài lab mà sử dụng đến card bridge ở các môi trường khác nhau (ở nhà, cơ quan) có các dải IP dùng cho card bridge khác nhau mà máy ảo thì không thể thay đổi địa chỉ IP (ví dụ mạng ở nhà sử dụng dải 192.168.1.0/24, máy ảo có IP 192.168.1.10, lên công ty thì dải mạng là 10.10.10.0/24)

=> làm thế nào để lab được tại cơ quan?

Có hai cách:

-   Dùng card host only thay cho card bridge, cách này cần phải đặt lại địa chỉ IP cho card giống với IP của mạng ở nhà. để đặt lại ip xem mục 2.2
    
-   Dùng card NAT, cách này cũng cần chỉnh dải IP như cách trên.
    

Lưu ý:

-   Cách thứ 1 không kết nối ra được ngoài Internet
    
-   Cách thứ 2 cần cấu hình lại gateway của máy ảo do mặc định card NAT để gateway là .2, do đó ta cần cấu hình lại gateway cho giống với mạng bridge thật (giả sử gateway là .1). Cách làm như sau:
    

Vào Virtual Network Editor chọn card NAT và sửa dải IP như mục 2.2

Bỏ chọn connect a host virtual adapter to this network

[![](https://camo.githubusercontent.com/e111b5dee5a024bbc11f279672df90c6091b78bb/687474703a2f2f692e696d6775722e636f6d2f3773506f426c4a2e706e67)](https://camo.githubusercontent.com/e111b5dee5a024bbc11f279672df90c6091b78bb/687474703a2f2f692e696d6775722e636f6d2f3773506f426c4a2e706e67)

Ấn vào mục NAT Settings đặt lại gateway cho giống với gateway của mạng ở nhà (.1)

[![](https://camo.githubusercontent.com/d9a253690cca40131b758c40a80079ebbc760e8a/687474703a2f2f692e696d6775722e636f6d2f645449555172342e706e67)](https://camo.githubusercontent.com/d9a253690cca40131b758c40a80079ebbc760e8a/687474703a2f2f692e696d6775722e636f6d2f645449555172342e706e67)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwNDQzNDc0ODYsOTE2NjcxMjc0LC0xMD
E2NDI5MTE0LC0xMTI2MDUwOTUzLC0yNzExMjcwNTEsMjAzODU0
MDI2MiwyMDQ5OTE0OTg4LDI5OTcwOTU1NSwyMDQwMjk3NjIyXX
0=
-->