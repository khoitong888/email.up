Temp Mail Pro

Temp Mail Pro là một ứng dụng web cung cấp địa chỉ email tạm thời để nhận thư mà không cần sử dụng email cá nhân. Ứng dụng hỗ trợ tạo email tạm thời từ ba dịch vụ: Mail.tm, 1secmail, và GuerrillaMail, với giao diện hiện đại, hiệu ứng mượt mà, và tối ưu hóa cho cả desktop lẫn mobile.
Tính năng

Tạo email tạm thời: Tạo nhanh địa chỉ email ngẫu nhiên với thời hạn 10 phút.
Nhận và hiển thị email: Xem danh sách email đến với thông tin người gửi, tiêu đề, và nội dung.
Sao chép email: Copy địa chỉ email chỉ với một cú nhấp chuột.
Làm mới inbox: Tự động làm mới inbox mỗi 10 giây để kiểm tra email mới.
Xóa email: Hỗ trợ xóa email (chỉ với Mail.tm).
Giao diện đẹp mắt: Thiết kế hiện đại với gradient, hiệu ứng mờ nền, và animation mượt mà.
Responsive: Tối ưu hóa cho mọi thiết bị, từ mobile đến desktop.

Công nghệ sử dụng

HTML5/CSS3: Cấu trúc và giao diện web.
Tailwind CSS: Framework CSS để tạo giao diện responsive và hiện đại.
JavaScript (Vanilla): Xử lý logic và tương tác với API.
Inter Font: Font chữ hiện đại từ Google Fonts.
APIs:
Mail.tm API
1secmail API
GuerrillaMail API



Cài đặt
Yêu cầu

Trình duyệt web hiện đại (Chrome, Firefox, Safari, Edge, v.v.).
Kết nối internet để gọi API.

Hướng dẫn cài đặt

Clone repository:git clone https://github.com/your-username/temp-mail-pro.git


Mở tệp index.html:
Di chuyển vào thư mục dự án:cd temp-mail-pro


Mở tệp index.html trong trình duyệt hoặc sử dụng server cục bộ (khuyến nghị).


Sử dụng server cục bộ (tùy chọn):
Cài đặt Live Server trên VS Code hoặc chạy server đơn giản bằng Python:python -m http.server 8000


Truy cập tại http://localhost:8000.



Cách sử dụng

Tạo email tạm thời:
Khi mở ứng dụng, một địa chỉ email tạm thời sẽ tự động được tạo.
Địa chỉ email được hiển thị trong ô input ở đầu trang.


Sao chép email:
Nhấn nút Copy để sao chép địa chỉ email vào clipboard.


Kiểm tra inbox:
Inbox sẽ tự động làm mới mỗi 10 giây để hiển thị email mới.
Nhấn Refresh để làm mới thủ công.


Xem nội dung email:
Nhấn vào một email trong inbox để xem nội dung (hiển thị trong iframe).
Với Mail.tm, bạn có thể xóa email bằng nút Delete.


Tạo email mới:
Nhấn New Email để tạo một địa chỉ email mới (email cũ sẽ bị xóa).


Hết hạn email:
Email tạm thời có thời hạn 10 phút. Sau khi hết hạn, bạn cần tạo email mới.



Giao diện
Giao diện được thiết kế với:

Màu sắc: Gradient tối (xanh đậm đến đen) với điểm nhấn cyan và tím.
Hiệu ứng: Fade-in, slide-down, ripple, và pulse cho các tương tác.
Responsive: Tối ưu cho mọi kích thước màn hình.
Backdrop blur: Hiệu ứng kính mờ cho header và card.
Icons: Sử dụng SVG icons từ Tailwind để tăng tính thẩm mỹ.

Cấu trúc dự án
temp-mail-pro/
├── index.html       # Tệp chính chứa HTML, CSS, và JavaScript
├── README.md        # Tệp hướng dẫn này

Hạn chế

Hết hạn email: Email tạm thời chỉ tồn tại trong 10 phút.
Xóa email: Chỉ hỗ trợ xóa email với Mail.tm, không hỗ trợ với 1secmail và GuerrillaMail.
Bảo mật HTML: Hàm sanitizeHTML loại bỏ các thẻ nguy hiểm, nhưng nên sử dụng thư viện như DOMPurify để tăng cường bảo mật.
API phụ thuộc: Ứng dụng phụ thuộc vào các API bên thứ ba, có thể gặp lỗi nếu API không hoạt động.

Đóng góp

Fork repository.
Tạo nhánh mới:git checkout -b feature/your-feature


Commit thay đổi:git commit -m "Add your feature"


Push lên nhánh:git push origin feature/your-feature


Tạo Pull Request trên GitHub.

Giấy phép
Dự án được phát hành dưới MIT License.
Liên hệ
Nếu bạn có câu hỏi hoặc đề xuất, vui lòng mở một issue trên GitHub hoặc liên hệ qua email: khoitong0000@gmail.com].

Temp Mail Pro - Nhanh chóng, an toàn, và tiện lợi để nhận email tạm thời!
