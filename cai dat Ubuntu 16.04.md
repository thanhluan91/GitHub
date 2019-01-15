# Hướng dẫn cài đặt hệ điều hành Ubuntu 16.04


### 2. Install

- **2.1**   Chọn Install Ubuntu Server => Enter

![](https://camo.githubusercontent.com/1c7225a93be5ee3cb3fcdfe384dea7f17ec7f3f0/68747470733a2f2f692e696d6775722e636f6d2f7739387a37574f2e706e67)

- **2.2** tới phần **select a Language** chọn ngôn ngữ sử dụng trong hệ điều hành **Ubuntu Server 16.04** chọn **English** ==> Enter 

![](https://camo.githubusercontent.com/b2aa1b8b4c5da050eab40f08f50aaddfc91410e8/68747470733a2f2f692e696d6775722e636f6d2f49664f7353586f2e706e67)

  - **2.3** lựa chọn khu vực **

![](https://camo.githubusercontent.com/56f11cbc637d8ad42c33b98398afcb17b46c17c5/68747470733a2f2f692e696d6775722e636f6d2f4173504345446d2e706e67)

-  **2.4**  Chọn **No** nếu không cấu hình bàn phím mặc định sẽ là kiểu bàn phím **English**

![](https://camo.githubusercontent.com/2d8085d3a70dc97eb89e86aab3f72b4ed20f4c16/68747470733a2f2f692e696d6775722e636f6d2f3148505576756e2e706e67)

- **2.5** Chọn chuẩn cú pháp gõ bàn phím dành cho  **Keyboad** của bạn . Thông thường chúng ta sủa dụng chuẩn tiếng anh. nên chọ **English**

![](https://camo.githubusercontent.com/29f4926fecbf721d10b881ff7cc1f9fd481e88c4/68747470733a2f2f692e696d6775722e636f6d2f344c79685865752e706e67)

-  **2.6** Quá trình cấu hình mạng tự động

![](https://camo.githubusercontent.com/ec207f83ac1d4508d9245216337c9f858d43abb0/68747470733a2f2f692e696d6775722e636f6d2f463334663857642e706e67)

-  **2.7** Cấu hình tên máy **hostname** cho server Ubuntu 

![](https://camo.githubusercontent.com/b18dfc224f7f631208e978a2052717b457f1009a/68747470733a2f2f692e696d6775722e636f6d2f414676314a4d732e706e67)

-   **2.8** Tạo User khác để đăng nhập từ đầu . Thay vì sử dụng User **root** vì lý do bảo mật. 

![](https://camo.githubusercontent.com/ab8287ff80126554d551b0f59a72c6f9253556d9/68747470733a2f2f692e696d6775722e636f6d2f5331385a6d616f2e706e67)

-  **2.9** Đặt mật khẩu cho **User** vừa tạo 

![](https://camo.githubusercontent.com/50c5bd9e4de25bf17e8cc78144a087c05c443437/68747470733a2f2f692e696d6775722e636f6d2f48336c6d476e672e706e67)

-   **2.10** mã hóa thư mục /home để bảo mật . chọn **No** nếu không mã hóa 

![](https://camo.githubusercontent.com/f1415cedeb80cc557c1f3518775cc36b78bd0f15/68747470733a2f2f692e696d6775722e636f6d2f71564e504c506d2e706e67)


-   **2.11** Chọn **timezone** cho server. chọn **timezone** và múi giờ phù hợp với vị trí địa lý của mình  
![](https://camo.githubusercontent.com/5177e6b7ce4969ee00887d178583d2b4c63ba6dd/68747470733a2f2f692e696d6775722e636f6d2f76596c4e6838712e706e67)

-   **2.12** Lựa chọn hình thức cấu hình chia Parition ổ cứng. có thể chọn **Guided - use entire disk** để máy tự động phân chia dung lượng và phần vùng ổ cứng
		- hoặc chon ** Manual** để cài đặt theo ý muốn 

![](https://camo.githubusercontent.com/65ba5e03e7c0a634ca05143cb7d55e848635e8ca/68747470733a2f2f692e696d6775722e636f6d2f747468586e4c742e706e67)

- **2.13** lựa chọn ổ cứng sẽ cài đặt hệ điều hành **OS Ubuntu Server** lên máy chủ  

![](https://camo.githubusercontent.com/564a90a169b38fc1fdd8bbe98d6837e2ffa75a88/68747470733a2f2f692e696d6775722e636f6d2f704534754365512e706e67)

-  **2.14** xác nhận chép đè thông tin **partition** lên ổ cứng đã lựa chọn trước đó . Chọn **Yes** 

![](https://camo.githubusercontent.com/4d57b8c0386d007c879a6bf20eb0b52e3c59d9a0/68747470733a2f2f692e696d6775722e636f6d2f4f74706c68685a2e706e67)

-   **2.15** Cấu hình http proxy nếu cần thiết để update luôn các phiên bản phần m **select a Language** 
[![](https://camo.githubusercontent.com/9e55e35931a0ba709322dd285bfc41c93ae56b44/68747470733a2f2f692e696d6775722e636f6d2f657a597161447a2e706e67)](https://camo.githubusercontent.com/9e55e35931a0ba709322dd285bfc41c93ae56b44/68747470733a2f2f692e696d6775722e636f6d2f657a597161447a2e706e67)

-   Chọn cài đặt các chương trình chuẩn bị sẵn cho Server, Chọn OpenSSH và standard system utilities => Enter

[![](https://camo.githubusercontent.com/3dac841f44aada330c65291741e03ded90c4485f/68747470733a2f2f692e696d6775722e636f6d2f4647694a48656f2e706e67)](https://camo.githubusercontent.com/3dac841f44aada330c65291741e03ded90c4485f/68747470733a2f2f692e696d6775722e636f6d2f4647694a48656f2e706e67)

-   Chọn "Yes" để cài đặt GRUB Boot loader

[![](https://camo.githubusercontent.com/dccb0036d24752649a2dc6f24aacdb650840ea3e/68747470733a2f2f692e696d6775722e636f6d2f7331536d704e502e706e67)](https://camo.githubusercontent.com/dccb0036d24752649a2dc6f24aacdb650840ea3e/68747470733a2f2f692e696d6775722e636f6d2f7331536d704e502e706e67)

-   Chọn "Continue" để bắt đầu cài đặt

[![](https://camo.githubusercontent.com/d5cbfb9b86cef31289e18eb7f33faee5bb249aa3/68747470733a2f2f692e696d6775722e636f6d2f35325448694c4a2e706e67)](https://camo.githubusercontent.com/d5cbfb9b86cef31289e18eb7f33faee5bb249aa3/68747470733a2f2f692e696d6775722e636f6d2f35325448694c4a2e706e67)

> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwODI5ODEwMyw4ODY2NDU4MDEsLTUwMj
U1NDA5LDE5NTY0NzM2NDNdfQ==
-->