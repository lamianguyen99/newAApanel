# newAApanel


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

