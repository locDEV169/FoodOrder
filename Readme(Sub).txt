TÊN SẢN PHẨM LÀ : WEB Order Food Online


NHÓM TÁC GIẢ: CCMTPTPM 18-0103_NHÓM 06:
NGUYỄN VĂN LỘC
TRẦN CÔNG LAI
LÊ THỊ THANH HUYỀN 
TRƯƠNG VĂN QUỐC NHÂN
PHẠM QUỐC AN
VÕ THÀNH LONG

#Mô Tả website:
Đây là một ứng dụng web được xây dựng bằng Python Django framework. Ứng dụng này sử dụng Django phiên bản 3.2.4 trong backend và postgres sql ở phía Admin. Ứng dụng này có giao diện người dùng cơ bản được phát triển bằng cách sử dụng bootstrap css và js. Ứng dụng này được xây dựng và thử nghiệm cho phiên bản python 3.9 Hệ thống đặt hàng thực phẩm trực tuyến sử dụng Tính năng Django cho Admin site

#Có 2 Chức Năng Chính là:
1/Back-End:
+ Trang tổng quan(Dashboard in admin site) - Đối với trang tổng quan quản trị, bạn sẽ có thể truy cập tất cả các quyền cơ bản trong toàn bộ hệ thống. Chẳng hạn như đơn đặt hàng mặt hàng giỏ hàng, mặt hàng, người dùng và danh mục.
+ Quản lý mặt hàng(Manage Items)– Quản trị viên có quyền truy cập vào hệ thống thông tin quản lý mặt hàng. Anh ta có thể thêm, cập nhật và xóa các mục.
+ Quản lý đơn đặt hàng(Manage Orders) - Là chức năng chính của quản trị viên, quản trị viên có thể từ chối hoặc chấp nhận từ khách hàng trong từng trường hợp cụ thể.
+ Quản lý danh mục(Manage Categories) - Đối với danh mục, quản trị viên có các tính năng quản lý danh mục. Danh mục ví dụ được sử dụng trong hệ thống này là thực phẩm bán chạy nhất, thực phẩm cay và thực phẩm mới.
+ Quản lý người dùng(Manage Users) - Quản trị viên có thể quản lý tài khoản của người dùng. Admin có thể thêm, cập nhật và xóa người dùng trong hệ thống.
+ Đăng nhập và Đăng xuất(Login and Logout) - Theo mặc định, một trong những tính năng bảo mật của hệ thống này là hệ thống đăng nhập và đăng xuất an toàn.
2/Front-End:
+ Trang chủ(Home Page) - Trên trang chủ, bạn có thể xem trực tiếp danh sách các loại thực phẩm cần bán, đăng nhập, đăng xuất.
+ Xem Sản phẩm(Viewing Products) - theo mặc định trên giao diện người dùng, khách hàng có thể tự động xem tất cả các loại thực phẩm, giá cả và mô tả của các loại thực phẩm.
+ Đơn hàng thanh toán(Checkout Orders) - Khách hàng có thể thanh toán đơn hàng trong giao diện người dùng mà quản trị viên có thể xác nhận trong phần phụ trợ.
+ Đăng nhập và Đăng xuất(Login vs Logout) - Khách hàng cần đăng nhập vào hệ thống trước khi có thể thêm vào giỏ hàng và họ cũng có thể đăng xuất sau khi hoàn thành đơn đặt hàng.
+ Đăng ký(Sign up) - khách hàng cần đăng ký hoặc đăng ký trước khi có thể đăng nhập vào hệ thống.
+ Thêm vào giỏ hàng(Add to Cart)– Một trong những tính năng của hệ thống này là, trong đó khách hàng có thể tạm thời thêm đơn hàng của họ trong phần thêm vào giỏ hàng.


#CHỈ DẪN ĐỂ TRIỂN KHAI:
(Link github của team leader)
https://github.com/locDEV169/FoodOrder

Installation Steps(Các bước cài đặt)
1/Cài đặt python 3.9 nếu chưa hoàn tất
2/Tải xuống và giải nén ứng dụng Pycharm pro
3/Nhập dự án vào một IDE mà bạn chọn (tôi sử dụng PyCharm)
4/Thiết lập trình thông dịch dự án (thiết lập python venv) và cấu trúc dự án
+Trong PyCharm, hãy làm theo các bước dưới đây
	+PyCharm -> Preferences -> Project -> Project Interpreter
	 
	+PyCharm -> Preferences -> Project -> Project Structure
	 

5/Định cấu hình chi tiết cơ sở dữ liệu của bạn trong tệp settings.py.
6/Thực hiện các lệnh sau để thiết lập cơ sở dữ liệu của bạn với các bảng cần thiết
	<venv>/python manage.py makemigrations Foods_Ordering
	<venv>/python manage.py migrate
7/Tạo người dùng quản trị cho ứng dụng của bạn
	<venv>/python manage.py createsuperuser
	tạo thông tin đăng nhập quản trị viên khi được nhắc
8/Bây giờ hãy chạy ứng dụng
	<venv>/python manage.py runserver

9/Trong PyCharm, bạn cũng có thể thiết lập môi trường gỡ lỗi cho dự án bằng cách đặt cấu hình thời gian chạy cho manage.py

chọn Django server > chọn python 3.9

 
