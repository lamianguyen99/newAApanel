# newAApanel

Content:

Bạn đặt câu hỏi rất hay. Trước khi sử dụng Laravel, bạn cần thiết lập môi trường phát triển phù hợp. Có 2 lựa chọn phổ biến là:

1. LAMP(Linux, Apache, MySQL, PHP):

- Đây là môi trường phát triện phổ biến cho các ứng dụng PHP, bao gồm cả Laravel.
- Trong môi trường LAMP, bạn cần cài đặt:
    - Linux(Hệ điều hành)
    - Apache(web server)
    - MySQL(Cơ sở dữ liệu)
    - PHP(ngôn ngữ lập trình)

2. LNMP(Linux, Nginx, MySQL, PHP):

- Đây là một biến thể của LAMP, sử dụng Nginx thay vì Apache.
- Nginx thường được coi là nhanh hơn và hiệu quả hơn Apache, đặc biệt là khi xử lý lưu lượng truy cập cao.

Ngoài ra, có một số công cụ giúp việc cài đặt và quản lý môi trường phát triền trở nên dễ dàng hơn, chẵng hạn như AAPanel.

AAPanel là một bảng điều khiển web giúp quản lý web server, cơ sở dữ liệu, ứng dụng web,v.v.v... Nó cung cấp một giao diện đồ họa thân thiện người dùng, giúp việc cài đặt và quản lý LAMP/LNMP trở nên dễ dàng hơn.

Vì vậy, để sử dụng Laravel, bạn cần thiết lập môi trường LAMP/LNMP trước, và có thể sử dụng AAPanel để quản lý môi trường nây mội cách thuận tiện hơn. Sau khi có môi trường phát triển sẵn sàng, bạn mới có thể bắt đầu sử dụng Laravel để xây dựng ứng dụng web.


# aaPanel là gì? Hướng dẫn cách cài đặt aaPanel cho VPS

Hưng Nguyễn

Nếu bạn đang có nhu cầu tìm kiếm một control panel gọn nhẹ, yêu cầu cấu hình vừa phải mà lại có thể đáp ứng tiêu chí về độ mượt mà, ổn định thì aaPanel là một gợi ý bạn có thể tham khảo. Hãy cùng Vietnix đến với bài viết dưới đây để cùng tìm hiểu aaPanel là gì và cách cài đặt aaPanel cho VPS đơn giản nhất.

Mục lục

aaPanel là gì?

aaPanel là một control panel miễn phí, cho phép người dùng quản lý server với giao diện GUI đơn giản. Đặt biệt, thông qua aaPanel, bạn có thể dễ dàng cài đặt một server web chạy mô hình LNMP/LAMP chỉ bằng một số thao tác đơn giản.

![](https://vietnix.vn/wp-content/uploads/2023/03/aapanel-la-gi.webp)

Nếu bạn đã từng nghe qua về BAOTA Panel - một hosting control miễn phí nổi tiếng được phát triển tại Trung Quốc. aaPanel là phiên bản quốc tế hóa của BAOTA Panel. Phiên bản này được ra đời với mục đích đơn giản hóa việc cài đặt, quản trị VPS và server web, giúp người dùng có thể dễ dàng tỉếp cận và sử dụng để phát triển ứng dụng mà không cần phải quan tâm quá nhiều đến hệ thống.

Mặc dù aaPanel còn khá mới (chỉ mới phát triển đến version 1.1.j)
và có ít tính năng hơn BAOTA Panel, nhưng aaPanel vẫn được khuyên dùng bởi control panel này liên tục được cập nhật với nhiều tính năng hữu ích.

## Chức năng của aaPanel là gì?

Vì aaPanel còn khá mới nên chỉ hỗ trợ cho người dùng một số chức năng cơ bản nhất như: quản lý web, Database, FTP và File.

Operating System - Hệ điều hành hỗ trợ (OS) của aaPanel cũng khá đầy đủ. Bao gồm : CentOS, Debian, Ubuntu, Fedora. **Tuy nhiên, bạn cần lưu ý rằng OS phải Pure and Clean(tức mới và sạch sẽ)** và chưa từng cài các phần mềm hay nền tảng như PHP/Apache/NGINX/MySQL. Ngoài ra, để chạy aaPanel, cấu hình tối thiểu cần


Nếu bạn đang tìm kiếm một giải pháp thay thể máy chủ ảo (VPS) tốc độ cao, bảo mật và toàn quyền quản trị, bạn có thể tham khảo dịch vụ VPS giá rẻ , VPS Phổ thông, VPS Cao cấp, VPS NVMe của Vietnix.

## Lời kết

Bên trên là một số thồng tin cơ bản về aaPanel và cách sử dụng aaPanel. Nhìn chung, aaPanel sẽ là một gợi ý dành cho những ai đang tìm kiếm control panel để làm web hosting cá nhân bởi độ gọn nhẹ, mượt mà và hiệu năng ổn định. Ngoài ra, đừng quên chia sẻ bài viết này để mọi người cùng tham khảo nhé.

Hưng Nguyễn
Co-Founder tại Vietnix






sau đó ta cài OpenLite speed

Đầu tiên cần gỡ bỏ webserver cũ đang sử dụng ra nhé

hiện mình đang sử dụng Nginx làm webserver

`openlite3 1024x742 1`

Nên bây giờ mình sẽ tiến hành gỡ cài đặt Nginx như sau(Nếu sử dụng Apache thì bạn cũng làm tương tự là được)

Tại giao diện aaPanel, bạn truy cập App Store (1) => Installed (2) => Tại phần Nginx bạn chọn Uninstall (3) để gỡ cài đặt.

![image](https://github.com/user-attachments/assets/d1e13ae5-a677-4a2f-8b46-50b72e522d8a)

Tiếp tục nhấn **confirm** để gỡ xác nhận cài đặt.

![image](https://github.com/user-attachments/assets/f5c595d7-eff7-4e4d-b60c-489497380e13)

Quá trình gỡ cài đặt sẽ được thực hiện, và các bạn chỉ cần chờ cho chạy xong

## Bước 2: Cài đặt OpenLiteSpeed

Để cài đật OpenLiteSpeed, tại giao diện App Store (1) => Deployment (2) => tại phần OpenLiteSpeed bạn chọn Install (3) để cài đặt.

![image](https://github.com/user-attachments/assets/7592c5e4-a2a5-450a-96f9-c6483fd472a0)

Tiếp tục chọn **confirm** để xác nhận cài đặt.

![image](https://github.com/user-attachments/assets/10bce921-2030-4456-99f3-c027e33f7567)


![image](https://github.com/user-attachments/assets/dfdb3c7c-f8ae-4a87-83b2-322a67d303f5)

Quá trình cài đật sẽ diễn ra khoảng 5-10 phút tùy từng [VPS](https://azdigi.com/blog/kien-thuc-vps/vps-may-chu-ao-la-gi-cac-loai-vps-can-biet/), như hình bên  dưới là mình đã cài đặt thành công OpenLiteSpeed.

![image](https://github.com/user-attachments/assets/64e474b6-5535-42c5-9756-25b2f3ea5c84)

## Bước 4: Kiểm tra Web admin OpenliteSpeed.

Sau khi cài đặt thành công, đường dẫn truy cập Web admin OpenLiteSpeed mặc định sẽ là: [http](https://IPVPS:7080/)

Tuy nhiên để có thể truy cập được thì bạn cần phải thực hiện 2 bước sau:

- Mở port firewalld

Mặc định port 7080

