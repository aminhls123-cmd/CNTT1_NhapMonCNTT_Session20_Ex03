# Bài 3 : Quản lý rủi ro khi mất thiết bị xác thực

## 1. Báo cáo phân tích (IPO) khôi phục tài khoản AWS
- Input: Mã dự phòng (Backup Codes) lưu trữ ngoại tuyến (giấy/USB).
- Process: 
  1. Nhập một Backup Code dùng một lần để đăng nhập AWS thay mã Authenticator.
  2. Vô hiệu hóa/xóa bỏ thiết bị xác thực cũ đã mất.
  3. Quét mã QR liên kết ứng dụng trên thiết bị mới và tạo bộ Backup Codes mới.
- Output: Khôi phục thành công quyền truy cập hệ thống AWS an toàn.

## 2. Lý do không lưu Backup Codes dưới dạng ảnh trong điện thoại
- Mỗi Backup Code có quyền năng thay thế hoàn toàn OTP và không yêu cầu xác thực lần hai.
- Nếu điện thoại bị mất hoặc nhiễm mã độc trích xuất dữ liệu , kẻ xấu sẽ sở hữu ngay chìa khóa đăng nhập vào hệ thống.
