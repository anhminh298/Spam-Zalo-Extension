# Mytool — gửi tin cá nhân trên Zalo Web

**Đây là sản phẩm thuần vibe code, làm cho vui, phục vụ nhu cầu cá nhân và thử nghiệm ý tưởng.** Tool có thể còn lỗi và cần được kiểm tra lại trước mỗi lần sử dụng.

Bản **0.1.4** · Chrome / Brave trên Windows.

## Đối tượng sử dụng

- **Sinh viên:** gửi link khảo sát cho bạn bè, chia sẻ thông báo học tập, hoạt động hoặc gửi lời hỏi thăm.
- **Giáo viên, trợ giảng:** báo cáo tình hình học tập của học sinh, sinh viên; nhắc bài, gửi thông báo cho phụ huynh hoặc người học. Có thể dùng Excel để cá nhân hóa tên học sinh trong từng tin.

## Lưu ý trước khi sử dụng

- **Không có cam kết** tool luôn hoạt động ổn định, gửi thành công cho mọi người nhận hoặc tránh được việc tài khoản Zalo bị hạn chế hay khóa. Khoảng nghỉ giữa các tin cũng không bảo đảm tránh các rủi ro này.
- **Bạn tự chịu trách nhiệm khi sử dụng**, bao gồm nội dung gửi, danh sách người nhận và những ảnh hưởng tới tài khoản của mình.
- Kiểm tra kỹ người nhận và bản xem trước. Chỉ gửi nội dung phù hợp, tôn trọng quyền riêng tư và mong muốn nhận tin của người khác.
- Danh sách, danh bạ đã lưu và tiến trình được lưu trong hồ sơ trình duyệt của bạn. Gỡ tiện ích hoặc xóa dữ liệu trình duyệt có thể làm mất dữ liệu chưa xuất.

## Tải và cài

1. Bấm **Code → Download ZIP** trên trang repo này, rồi giải nén.
2. Mở `chrome://extensions` hoặc `brave://extensions`.
3. Bật **Developer mode / Chế độ dành cho nhà phát triển**.
4. Bấm **Load unpacked / Tải tiện ích đã giải nén**.
5. Chọn thư mục **Mytool** trong phần vừa giải nén, nơi có `manifest.json`.
6. Mở [Zalo Web](https://chat.zalo.me/), đăng nhập và đặt giao diện tiếng Việt.
7. Bấm biểu tượng Mytool, chọn tab Zalo rồi bấm **Kết nối**.

Không cần cài Node.js hoặc chạy server. Giữ thư mục Mytool ở một vị trí cố định sau khi cài.

## Sử dụng

1. **Chọn người nhận:** bấm **Bạn bè Zalo**, tìm tên, tích chọn rồi thêm vào danh sách. Bạn cũng có thể nhập SĐT hoặc nhập Excel `.xlsx` / CSV / TSV và chọn sheet, cột tương ứng.
2. **Soạn tin:** vào **Nội dung**, nhập tin nhắn và dán link khảo sát nếu cần. Tin chung không cần điền tên học sinh. Nếu báo cáo học tập, chèn `[Tên học sinh]` để thay tên theo từng dòng Excel.
3. **Kiểm tra và gửi:** chọn khoảng nghỉ, xem lại nội dung và người nhận, rồi sang **Gửi & kết quả** để chạy. Có thể tạm dừng, lọc các dòng cần xử lý và xuất Excel kết quả.

Danh bạ được đồng bộ đầy đủ ở lần đầu, những lần mở sau dùng bản đã lưu. Bấm **Cập nhật danh bạ** khi cần lấy lại bạn bè mới nhất. Người chưa xác định được tài khoản từ danh bạ được liệt kê riêng; có thể thêm bằng SĐT hoặc xử lý trực tiếp trên Zalo.

Giữ tab Zalo và Mytool mở khi gửi. Tạm dừng trước khi tự chuyển hội thoại trên tab Zalo đang được điều khiển.

Giấy phép thư viện đi kèm trong `Mytool/THIRD-PARTY-LICENSES.txt`.
