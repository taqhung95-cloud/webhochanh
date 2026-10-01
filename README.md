# Mimo — Đại dương học vui

Web app song ngữ Việt–Anh dành cho trẻ từ 3 tuổi, lấy cảm hứng từ Montessori. Chủ đề đại dương, nhân vật và tranh SVG riêng.

- Chữ cái: 29 chữ Việt, 26 chữ Anh, từ minh họa và bảng vẽ nét bằng ngón tay.
- Đếm số: chạm từng chú cá theo tương ứng một–một; số lượng 1–5 hoặc 1–10.
- Ghép tranh: cá mập, gấu trúc, bướm, voi; 4/6/9/12 mảnh có khớp nối. Kéo thả hoặc chạm mảnh rồi chạm ô; hình gợi ý có thể tắt.
- Phân loại màu: đưa các hình vào giỏ cùng màu, phản hồi nhẹ nhàng để tự thử lại.
- Sáng tạo: vẽ, tẩy, in hình, lưu PNG và khôi phục sau khi xóa giấy.
- Cài đặt dành cho phụ huynh; chỉ lưu tùy chọn trên thiết bị, không thu thập dữ liệu của bé.

## Chạy

Không cần npm install hoặc build. Phục vụ thư mục bằng một HTTP server, ví dụ `python -m http.server 4173`, rồi mở `http://localhost:4173`. Giọng dự phòng dùng Web Speech API của trình duyệt; hỗ trợ và vùng giọng phụ thuộc thiết bị. `audio.js` đóng gói 93 lời đọc MP3 (48 Việt, 45 Anh) dưới dạng data URL, giúp triển khai không cần dịch vụ giọng nói hay API key khi bé chơi.

## GitHub Pages

Trong Settings → Pages chọn **Deploy from a branch**, nhánh **main**, thư mục **/(root)**, Save. Đường dẫn tài nguyên tương đối hỗ trợ `https://taqhung95-cloud.github.io/webhochanh/`.

## Âm thanh

Bộ lời đọc được tạo trước bằng Microsoft Nam Minh (tiếng Việt) và Aria (tiếng Anh). Không có API key trong mã giao diện. Hãy nghe kiểm duyệt phát âm miền Bắc trên bộ âm thanh cuối trước khi dùng như nội dung giáo dục. Khi âm thanh không phát được, app chuyển sang giọng đọc thiết bị; giọng dự phòng không bảo đảm vùng miền.

## Giáo dục & tham khảo

App bổ trợ hoạt động cùng đồ vật thật, không thay thế trải nghiệm Montessori thực hành. Không điểm, đồng hồ đếm ngược hay phần thưởng ép chơi tiếp. Bé và ba mẹ chủ động chọn mức khó.

- [American Montessori Society](https://amshq.org/about-us/inside-the-montessori-classroom/early-childhood/): tự chọn hoạt động, vật liệu tự sửa sai, vận động tinh.
- [Pinkfong — kênh người dùng cung cấp](https://www.youtube.com/channel/UCcdwLMPsaU2ezNSJU1nFoBQ): tham khảo chủ đề, màu sắc và không khí. Không dùng tài sản/âm nhạc tải từ kênh và không có liên kết thương hiệu.
- Mẫu đồ chơi ghép tranh người dùng cung cấp: tham khảo tương tác và tăng dần số mảnh. Các bức tranh trong app là SVG vẽ riêng.

Font Baloo 2 và Nunito tải qua Google Fonts (có font hệ thống dự phòng). Các liên kết tham khảo chỉ nằm trong góc phụ huynh.
