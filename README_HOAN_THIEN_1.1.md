# Tử Vi Lạc Hồng 1.1 – Hoàn thiện luận giải và mở khóa thủ công

## 1. Luận giải chuyên sâu theo từng cung
- Nội dung được tạo theo dữ liệu của lá số đang mở: tên cung, địa chi, chính tinh, trạng thái sao, cát tinh, sát/hao tinh, Tứ Hóa, Trường Sinh, Thái Tuế, Tuần/Triệt và các cung tam hợp/xung chiếu/giáp.
- Mỗi cung đã mở khóa có 26 chuyên đề luận giải, gồm tổng quan toàn diện, chính tinh, tổ hợp sao, phụ tinh, tam phương tứ chính, ngũ hành, Tứ Hóa, Tuần/Triệt, Vô Chính Diệu, tâm lý, ứng dụng đời sống, công việc, nguồn lực, quan hệ, vận hạn, các giai đoạn, cơ hội, rủi ro, chiến lược phát triển và kết luận.
- Dung lượng được hiển thị ngay trên màn hình theo số ký tự nội dung được sinh ra. Mục tiêu nội dung là khoảng 50.000–80.000 ký tự/cung; số thực tế có thể thay đổi theo dữ liệu lá số.
- Các phần về lưu nguyệt/lưu hạn chỉ đưa ra giới hạn khi ứng dụng chưa an đủ sao lưu; không tự gán tháng tốt/xấu. Tử Vi được ghi rõ là nội dung tham khảo văn hóa, không phải dự báo chắc chắn hay tư vấn y tế/pháp lý/tài chính.

## 2. Mở khóa trả phí – phương án thủ công tạm thời
- Giữ QR MSB và mức giá cũ: 5.000đ mở một cung; 10.000đ mở toàn bộ 12 cung.
- Người dùng nhấn “Tôi đã chuyển khoản – nhận mã mở khóa”, ứng dụng sinh mã yêu cầu ngẫu nhiên.
- Hiển thị số liên hệ 089.666.4467; email yêu cầu gửi tới mikuthanh2305@gmail.com.
- Người dùng phải tự nhấn gửi email. Chủ ứng dụng kiểm tra giao dịch ngân hàng thủ công, sau đó dùng `ADMIN_CAP_MA_KICH_HOAT.html` để tạo mã.
- Mã kích hoạt ràng buộc với mã yêu cầu, gói mua và mã cung; mã nhập sai không mở khóa.
- Mã yêu cầu đang chờ được lưu cục bộ để người dùng không mất khi đóng/mở lại ứng dụng. Sau kích hoạt thành công, yêu cầu chờ được xóa và quyền mở khóa được lưu cục bộ.

## 3. Giới hạn bảo mật
Đây là cơ chế offline tạm thời. Khóa kiểm tra mã được nhúng trong APK nên người có kỹ năng phân tích APK có thể trích xuất và tự tạo mã. Không coi đây là chống gian lận ở mức máy chủ. Khi triển khai kinh doanh rộng, nên chuyển việc xác thực mã và lưu quyền mua lên backend có chữ ký số, đồng thời không nhúng bí mật vào APK.

## 4. Tệp quản trị
Mở `ADMIN_CAP_MA_KICH_HOAT.html` bằng trình duyệt trên máy tính để cấp mã. Nhập chính xác mã yêu cầu và mã cung trong email; với gói 10.000đ chọn gói toàn bộ 12 cung. Kiểm tra đã nhận đủ tiền trước khi cấp mã.

## 5. Kiểm tra kỹ thuật đã thực hiện
- Kiểm tra cú pháp JavaScript bằng `node --check`.
- Kiểm tra sự trùng khớp thuật toán cấp mã giữa công cụ quản trị và ứng dụng.
- Kiểm tra các thông tin liên hệ và cơ chế lưu mã yêu cầu.
- Đây là mã nguồn đã cập nhật; chưa xác nhận đã tải lên GitHub hoặc build APK mới.
