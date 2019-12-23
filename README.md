HƯỚNG DẪN CÀI ĐẶT
Dự án sẽ được làm phát triển trên Framework Laravel phiên bản 5.4. 
Các bước thiết lập môi trường phát triển ứng dụng:
1.	Bước 1: Cài đặt và cấu hình PHP, có thể tham khảo tại: https://www.sitepoint.com/how-to-install-php-on-windows/.
2.	Bước 2: Cài đặt và cấu hình máy chủ web Apache, có thể tham khảo tại: http://www.wikihow.com/Install-the-Apache-Web-Server-on-a-Windows-PC
3.	Bước 3: Cài đặt trình quản lý thư viên Composer.
4.	Bước 4: Cài đặt và cấu hình MySQL, có thể tham khảo tại: https://www.devside.net/guides/windows/phpmyadmin
5.	Bước 5: Cài đặt Laravel:
•	Mở cửa sổ lệnh CMD lên và di chuyển tới DocumentRoot của máy chủ web gõ lệnh: composer create-project laravel/laravel qlpth --prefer-dist, để tạo dự án Laravel.
•	Vào trình duyệt gõ đường dẫn http://localhost/money/public để chạy ứng dụng.
Về trình soạn thảo code được sử dụng là sublime text 3.
Quá trình cài đặt và sử dụng: 
-	Vào địa chỉ http://www.sublimetext.com/3 để tải bộ cài đặt về cho máy (Windows 64bit). Sau khi có được bộ cài tiến hành cài đặt để cài đặt trình soạn thảo code.
-	Tiếp tục cài thêm phần Package Control (PC) nhằm cài đặt thêm các plugin ỗ trợ lập trình. Để cài PC vào https://packagecontrol.io/installation#st3 để lấy phần code, sau đó nhấn View->Show Console rồi paste đoạn code vào khung. Sau khi cài đặt xong Package Control thì restart Sublime text.
-	Kế tiếp là cài các plugin, để cài nhấn tổ hợp phím Ctrl + Shift + P, rồi nhấn Install Package, rồi nhấn tên plugin xong Enter, chờ plugin cài đặt xong. Trong quá trình phát triển ứng dụng đã cài các plugin Bootstrap 3 Snippets, jQuery, Emmet, Laravel.
6.	Cài đặt phần mềm
-	Clone source code từ github về
-	Vào thư mục chứa source code update vendor laravel bằng lệnh composer update
-	Khi cài đặt xong: 
+ Vào mysql tạo csdl đăt tên qlpth và import file money.sql (tìm file money.sql trong thư mục Source)
-	Chạy thử phần mềm

