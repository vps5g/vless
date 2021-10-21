VLESS Heroku
Tổng quat
Dự án này được sử dụng để triển khai V2Ray WebSocket trên Heroku, trong phạm vi sử dụng hợp lý, hình ảnh này sẽ không bị chặn do lượng tài nguyên lớn.

Sau khi triển khai, mỗi khi bạn khởi động ứng dụng, V2Ray đang chạy sẽ luôn là phiên bản mới nhất.

triển khai
bươc chân
Chuyển dự án này vào tài khoản GitHub của bạn (lấy ví dụ làm ví dụ)
Sửa đổi tên dự án và cẩn thận không bao gồm các từ khóa v2ray và heroku (tên dự án đã sửa đổi sử dụng bản trình diễn làm ví dụ)
Sửa đổi README.md và thay thế bclswl0827 / v2ray-heroku bằng nội dung của riêng bạn (chẳng hạn như ví dụ / bản trình diễn)
Triển khai

Quay lại trang chủ dự án, nhấp vào liên kết ở trên để triển khai V2Ray
Biến đổi
Các tên biến cần được đặt trong quá trình triển khai được giải thích như sau.

Mô tả giá trị mặc định của biến
ID ad806487-2d26-4636-98b6-ab85cc8521f7 ID người dùng VLESS, được sử dụng để xác thực, ở định dạng UUID
Đường dẫn giao thức WSPATH / HTTP được WebSocket sử dụng
Kết nối với CloudFlare
Hai phương pháp sau có thể kết nối ứng dụng với CloudFlare, từ đó tăng tốc độ ở một mức độ nhất định.

Liên kết tên miền với ứng dụng và kết nối tên miền với CloudFlare
Reverse proxy qua CloudFlare worker
Lưu ý
Vui lòng không lạm dụng dự án này, các dịch vụ miễn phí như Heroku rất hiếm, hãy sử dụng và trân trọng
Nếu bạn sử dụng tên miền để kết nối với CloudFlare, vui lòng xem xét bật TLS 1.3
Hầu hết các địa chỉ AWS IPv4 đã bị Twitter chặn
