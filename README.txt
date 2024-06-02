- Các bạn đang học tới sử dụng flexbox để chia bố cục cho trang
- Mục tiêu cuối khoá là làm một trang cá nhân
- Mục tiêu buổi học là:
	+ Sử dụng flexbox để tạo bố cục cho navigation bar
	+ Sử dụng ép một tấm hình vừa in vào div bằng object-fit-cover
	
- Tài nguyên: 
	+ day6 folder: bài cũ
	+ demo: là file bài output ngày hôm nay

1. Giới thiệu về bài day6
- Sử dụng flexbox để chia bố cục cho từng phần trang web
- Cách sử dụng các tấm hình các . # tag trong css để thay đổi màu, độ dài độ cao...
- Hỏi mấy bạn xem đã chọn được bố cục nào ưng ý cho trang cá nhân chưa

2. Giới thiệu về navigation-bar (cái thanh điều hướng trên trang web)
- Thường có icon, nút chuyển các trang khác, nút login, sign up
- Có bố cục tuỳ ý
-> Áp dụng flexbox để thiết kế navigation bar

3. Phần trang chính, chèn hình vào div nào cũng được
- Thêm hình vào div đó
- Resize tấm hình 100% width 100% height so với div mẹ
- Nhưng hình sẽ bị méo mó
-> dùng object-fit: cover thì sẽ hết méo
- Hướng dẫn bạn cách dùng position: absolute -> top left
	để gắn hình nhỏ như biểu tượng vào trong hình lớn, canh giữa cho xinh đẹp