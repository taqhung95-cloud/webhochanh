# Mimo — Đại dương học vui

Web app song ngữ Việt–Anh dành cho trẻ từ 3 tuổi, lấy cảm hứng từ Montessori. Chủ đề đại dương, tranh Mimo riêng và thư viện nhân vật Pinkfong.

- Chữ cái: 29 chữ Việt, 26 chữ Anh, từ minh họa và bảng vẽ nét bằng ngón tay.
- Đếm số: chạm từng chú cá theo tương ứng một–một; số lượng 1–5 hoặc 1–10.
- Ghép tranh: 20 tranh (16 nhân vật Pinkfong và 4 tranh Mimo/động vật); 4/9/16/25 thẻ hình vuông. Kéo thả hoặc chạm mảnh rồi chạm ô; hình gợi ý có thể tắt.
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
- [Pinkfong — kênh người dùng cung cấp](https://www.youtube.com/channel/UCcdwLMPsaU2ezNSJU1nFoBQ): tham khảo chủ đề, màu sắc và không khí. Không tải âm nhạc từ kênh; ứng dụng độc lập, không có liên kết thương hiệu.
- Mẫu đồ chơi ghép tranh người dùng cung cấp: tham khảo tương tác và tăng dần số mảnh. Bốn tranh Mimo/động vật là SVG vẽ riêng.

Font Baloo 2 và Nunito tải qua Google Fonts (có font hệ thống dự phòng). Các liên kết tham khảo chỉ nằm trong góc phụ huynh.

## Nguồn hình nhân vật

16 hình nhân vật dùng trong ghép hình được lấy từ [Pinkfong Characters](https://www.pinkfong.com/en/characters?filter=pinkfong) và [Baby Shark Characters](https://www.pinkfong.com/en/characters?filter=baby_shark). Nhân vật/hình ảnh © The Pinkfong Company. Đây là app học tập độc lập; không phải sản phẩm chính thức của Pinkfong. Việc công khai tài nguyên không đồng nghĩa cấp giấy phép thương mại.

- Pinkfong: [ảnh gốc](https://www-cf.pinkfong.com/ip/ip_image/20260331/a1393f20b66acdbc553dc82080c13815.webp) → `pf-pinkfong.webp`
- Baby Shark: [ảnh gốc](https://www-cf.pinkfong.com/ip/ip_image/20260527/fe821b6dd3471835048643e2d46ca8c4.webp) → `pf-baby-shark.webp`
- Mommy Shark: [ảnh gốc](https://www-cf.pinkfong.com/ip/character_main_image/20260831/97fe499dfc40d4d16aa2f3d5ed8ca2fc.webp) → `pf-mommy-shark.webp`
- Daddy Shark: [ảnh gốc](https://www-cf.pinkfong.com/ip/character_main_image/20260831/86bd7ea290ccd37e476070c40ea98c3b.webp) → `pf-daddy-shark.webp`
- Grandma Shark: [ảnh gốc](https://www-cf.pinkfong.com/ip/character_main_image/20260831/9f04b3618c3558ba4d9d7fb980056e78.webp) → `pf-grandma-shark.webp`
- Grandpa Shark: [ảnh gốc](https://www-cf.pinkfong.com/ip/character_main_image/20260831/92a7899efe6cf45e4ad0597b9fb4c666.webp) → `pf-grandpa-shark.webp`
- William: [ảnh gốc](https://www-cf.pinkfong.com/ip/character_main_image/20260831/751fb04a3a346b08a7e6cd6802d6edf7.webp) → `pf-william.webp`
- Chichi: [ảnh gốc](https://www-cf.pinkfong.com/ip/character_main_image/20260831/4e9e057e0872ec42adc5f84a2ed0a597.webp) → `pf-chichi.webp`
- Ray: [ảnh gốc](https://www-cf.pinkfong.com/ip/character_main_image/20260831/681833e01ab62774acb14d9d44c22d1f.webp) → `pf-ray.webp`
- Hogi: [ảnh gốc](https://www-cf.pinkfong.com/ip/character_main_image/20260309/a49358d30f2285f52af89b95f1018ca5.webp) → `pf-hogi.webp`
- Poki: [ảnh gốc](https://www-cf.pinkfong.com/ip/character_main_image/20260309/6aa53196697341e803018f3cd935831e.webp) → `pf-poki.webp`
- Jeni: [ảnh gốc](https://www-cf.pinkfong.com/ip/character_main_image/20260309/9dc51dd4332b5be33b372a0ef96e24e7.webp) → `pf-jeni.webp`
- Nina: [ảnh gốc](https://www-cf.pinkfong.com/ip/character_main_image/20260309/d79cf0a3cf5314f04758977ff79ea1ca.webp) → `pf-nina.webp`
- Jordi: [ảnh gốc](https://www-cf.pinkfong.com/ip/character_main_image/20260309/788077d69fe3a20df35bf61dd6390b18.png) → `pf-jordi.png`
- Coco: [ảnh gốc](https://www-cf.pinkfong.com/ip/character_main_image/20260309/7f53f2f9bbec1780b36d1ba44014c1a2.webp) → `pf-coco.webp`
- Tani: [ảnh gốc](https://www-cf.pinkfong.com/ip/character_main_image/20260309/f7e548408795574c5f6ab9e645b9f4e2.webp) → `pf-tani.webp`
