# Bộ kỹ năng nội dung — SANOTEL / Nội Thất Cho Con (bản cho nhân viên)

Bộ skill này giúp bạn (nhân viên nội dung) dùng **Claude Code** để **sản xuất nội dung đạt chuẩn** cho
Nội Thất Cho Con / SANOTEL trên 4 kênh (Website, Facebook, YouTube, TikTok), rồi **đưa nội dung vào bảng Lark
"Chờ đăng"**. Hệ thống máy chủ của công ty sẽ **tự động đăng** lên nền tảng. Bạn chỉ tập trung **viết cho hay**.

## ⭐ Nguyên tắc vàng
> **Bạn CHỈ VIẾT → BỎ VÀO BẢNG LARK. KHÔNG tự đăng lên website / Facebook / TikTok / YouTube.**
> Bộ skill này **không chứa và không cần** mật khẩu website hay token nào. Nếu ai đưa bạn mật khẩu/token,
> **đừng dùng, đừng lưu vào bài** — mọi việc đăng do máy chủ tự lo.

## 🚀 Cách dùng
1. Cài **Claude Code** và đăng nhập tài khoản công ty cấp.
2. Mở thư mục này bằng Claude Code.
3. Gõ yêu cầu, ví dụ: *"Viết bài blog về giường tầng trẻ em chuẩn SEO"* → skill **noi-dung-wordpress** chạy.
4. Viết xong, làm theo mục "Bỏ vào bảng Lark" trong skill → đặt trạng thái **"Chờ đăng"** (hoặc theo quy định của chị chủ).

## 📚 Danh sách kỹ năng (18 skill)

### 🎯 A. Nội dung theo nền tảng (viết → Lark)
- **noi-dung-wordpress** — bài blog chuẩn SEO + AEO + AIO + GEO cho website (bài chủ lực: research đối thủ →
  viết >1500 từ đúng luật định dạng + 4 backlink → Lark).
- **noi-dung-facebook** — caption Facebook Hook-Story-Offer kéo traffic + hook cho Reel.
- **noi-dung-youtube** — tiêu đề + mô tả + tag + chữ thumbnail + hook cho video/Shorts YouTube.
- **noi-dung-tiktok** — hook + caption + hashtag + on-screen text cho video TikTok.

### 🔍 B. Nghiên cứu từ khoá (làm brief trước khi viết)
- **hmh-mkt-research-seo-web** — nghiên cứu từ khoá + chủ đề cho blog.
- **hmh-mkt-research-youtube** — research video YouTube theo chủ đề.

### 💰 C. Thiết kế offer
- **thiet-ke-offer** — định giá theo giá trị + thiết kế offer hấp dẫn.

### 🧰 D. Hỗ trợ (dùng khi cần)
- **hmh-mkt-chan-dung-dau-suong** — chân dung khách hàng mục tiêu.
- **hmh-mkt-phan-tich-doi-thu** — phân tích đối thủ cạnh tranh.
- **hmh-mkt-research-thi-truong** — nghiên cứu thị trường 360°.
- **hmh-mkt-lead-magnet** — tạo mồi câu (lead magnet).
- **hmh-mkt-content-da-kenh** — hệ thống nội dung đa nền tảng (lịch + tái sử dụng).
- **hmh-mkt-content-30-ngay** — xây chuỗi nội dung 30 ngày.
- **hmh-mkt-ebook-sach-lat** — biến 1 chủ đề thành ebook có thương hiệu.
- **hmh-mkt-infographic-html** — thiết kế infographic bằng HTML/CSS rồi xuất ảnh.
- **hmh-mkt-leadpage** / **hmh-mkt-ladipage** / **hmh-mkt-web-dich-vu** — nội dung landing page / trang bán hàng / web dịch vụ.

## 🔗 Đưa nội dung vào bảng Lark
Hiện tại: **nhập tay** — mở bảng Lark chị chủ cấp, tạo dòng mới, dán nội dung, đặt trạng thái "Chờ đăng".
*(Tuỳ chọn nâng cao: nếu chị chủ cấp "chìa khoá Lark" riêng cho nhân viên, có thể bật chế độ Claude tự đẩy bài
vào bảng — chìa khoá điền vào file `.env` riêng ở máy, KHÔNG commit lên đây.)*

## 🔒 Bảo mật
- Repo này **cố ý không chứa** file `.env`, `.secrets/`, token, hay `config.local.json`.
- Nếu bạn tự tạo file cấu hình có mật khẩu/khóa Lark, **KHÔNG commit** (đã chặn trong `.gitignore`).
