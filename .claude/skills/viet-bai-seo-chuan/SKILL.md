---
name: viet-bai-seo-chuan
description: >
  Viết bài blog chuẩn SEO để lên top Google: từ một brief (từ khoá chính/phụ, outline, meta, internal/external link)
  ra một bài HTML hoàn chỉnh đúng Checklist SEO (headline có số + lợi ích, sapo chứa từ khoá trong 100 từ đầu,
  heading rải từ khoá, alt ảnh chứa từ khoá, mật độ ~1.5-2%, kết luận + 2 CTA gắn UTM). Viết xong thì
  ĐƯA BÀI VÀO BẢNG LARK "Chờ đăng" để hệ thống tự đăng — nhân viên KHÔNG cần đụng tới website.
  Dùng khi người dùng muốn viết bài chuẩn SEO cho website, lên bài blog đúng từ khoá, viết content trụ.
  Kích hoạt khi có từ: viết bài seo, bài blog chuẩn seo, seo web writer, viết content chuẩn seo, từ khoá lên top, checklist viết bài blog.
---

# Skill: Viết bài blog chuẩn SEO (bàn giao nhân viên — chỉ VIẾT, không đăng)

Biến một **brief từ khoá** thành **bài blog chuẩn SEO** đủ sức lên top Google, đúng giọng chuyên gia,
đủ ảnh và đúng vị trí từ khoá. **Viết xong đưa vào bảng Lark "Chờ đăng" — hệ thống máy chủ tự đăng lên web.**

> ⚠️ **Nhân viên KHÔNG đăng thẳng lên website.** Việc đăng (tài khoản WordPress, mật khẩu, token) do
> **máy chủ / hệ thống tự động** lo. Nhiệm vụ của bạn: viết bài đạt chuẩn → bỏ vào bảng Lark. Xong.

## 0. Quy tắc bảo mật
- Skill này **không chứa** và **không cần** mật khẩu website hay token nào.
- Nếu ai đưa bạn mật khẩu WordPress/token → **không dùng, không lưu vào bài**. Chỉ làm việc với bảng Lark.

## 1. Tri thức nền (đọc TRƯỚC khi viết)
**Đọc [references/seo-blog-checklist.md](references/seo-blog-checklist.md) trước.** Đó là checklist 9 khối + bảng
vị trí từ khoá + gate xanh Yoast. Grounded từ Yoast SEO, Brian Dean/Backlinko, nguyên lý headline của Ogilvy.

## 2. Đầu vào — Brief bài viết
Lấy brief từ `phieu-bai-viet.md` người dùng điền (hoặc người dùng dán trực tiếp). Các trường:

| Trường | Vai trò |
|---|---|
| Tiêu đề / Từ khoá chính | H1 + focus keyword |
| Từ khoá phụ | H2/H3 + FAQ |
| Outline | Cấu trúc H1/H2/H3 |
| Meta Title / Meta Description | thẻ SEO (Title ≤60, Desc 120-156 ký tự) |
| URL Slug | đường dẫn sạch chứa từ khoá |
| Internal links / External (web mạnh) | link nội bộ + 1 link ngoài uy tín |
| Alt text ảnh | alt chứa từ khoá chính |
| Số từ mục tiêu | độ dài (mặc định ~1500-2000) |
| Danh mục / Tag | phân loại WordPress |

## 3. QUY TRÌNH VIẾT (Claude làm theo)

### Bước 1 — (khuyến nghị) Nghiên cứu đối thủ
Xem top 10 Google cho từ khoá chính (WebSearch) → ghi nhận cấu trúc, độ dài, góc tiếp cận → đặt mục tiêu viết tốt hơn.

### Bước 2 — Viết bài HTML chuẩn SEO
Tạo `output/YYYY-MM-DD-bai-seo/<slug>.html` — **chỉ phần thân bài** (không cần `<html>`/`<head>`), tuân thủ checklist:
- **H1**: từ khoá chính ở đầu, có số + lợi ích + lời hứa.
- **Sapo**: từ khoá chính trong **100 từ đầu** (tốt nhất câu 1), có neo móc (câu hỏi sốc / kết quả / câu chuyện).
- **Heading H2/H3** theo Outline; rải từ khoá chính/phụ; mỗi heading hấp dẫn/tò mò.
- **Mật độ từ khoá ~1.5-2%**, độ dài **≥ số từ mục tiêu**, đoạn 3-5 dòng.
- **Ảnh thân bài**: placeholder `__IMG1__`, `__IMG2__`… trong `src`, bọc `<figure><img src="__IMG1__" alt="<từ khoá chính ...>"><figcaption>…</figcaption></figure>`. **Alt BẮT BUỘC chứa từ khoá chính.** (Khi đăng, thay placeholder bằng URL ảnh thật; ảnh #1 = featured.)
- **Internal links**: 2-3 link nội bộ (anchor chứa từ khoá). **External**: 1 link "web mạnh" cùng chủ đề.
- **Kết luận** < 200 từ, không ý mới, truyền cảm hứng + câu cuối dễ nhớ.
- **2 CTA** (giữa + cuối) gắn UTM: `?utm_source=blog&utm_medium=post&utm_campaign=<slug>&utm_content=cta-giua-bai|cta-cuoi-bai`.
- **CẤM**: ký tự em dash "—", emoji, viết kiểu tin báo/trích báo.
- Rà mục "RÀ CUỐI TRƯỚC KHI PUBLISH" trong checklist trước khi đăng.

### Bước 3 — Đưa bài vào bảng Lark "Chờ đăng" (KHÔNG tự đăng web)
Viết xong, bạn **KHÔNG đăng lên website**. Thay vào đó bỏ bài vào **bảng Lark nội dung** với trạng thái
**"Chờ đăng"**. Hệ thống máy chủ sẽ tự lấy bài "Chờ đăng" và đăng lên web (chị chủ đã cài sẵn).
Điền đủ các ô cho 1 dòng bài:
1. **Tiêu đề** (chứa từ khoá chính).
2. **Nội dung** (dán HTML thân bài đã viết ở Bước 2).
3. **Từ khoá SEO** (chính) + **Meta description** (≤160 ký tự, chứa từ khoá).
4. **Slug** (không dấu, chứa từ khoá).
5. **Ảnh** đính kèm theo ô ảnh của bảng (nếu bảng có).
6. **Trạng thái = "Chờ đăng"** → lưu dòng. Xong việc của bạn.
> Ảnh trong bài để ở dạng placeholder `__IMG1__`, `__IMG2__`… kèm ô ảnh; hệ thống sẽ ghép khi đăng.

### Bước 4 — Lưu output
Tạo `output/YYYY-MM-DD-bai-seo/YYYY-MM-DD-bai-seo.md`: brief đã dùng, nội dung, ảnh, trạng thái ("đã bỏ vào Lark Chờ đăng").

## 4. Lấy brief từ lịch nội dung Lark
Nếu chị chủ giao brief qua **bảng Lark** (cột "Chờ viết" + hạn): mở bảng, lấy các bài đến hạn → đọc brief +
tải ảnh → viết theo Bước 1-2 → bỏ lại vào bảng với trạng thái "Chờ đăng" (Bước 3). Không có bảng thì viết
từ brief dán tay cũng được.

## 5. Gotcha thực chiến
- **Nhân viên chỉ làm tới bảng Lark** — mọi thao tác đăng/mật khẩu/token do máy chủ lo, đừng tự làm.
- **Alt ảnh BẮT BUỘC chứa từ khoá chính**; ảnh #1 sẽ thành ảnh bìa khi hệ thống đăng.
- **Mật độ từ khoá 1.5-2%**, đủ số từ mục tiêu, đoạn 3-5 dòng — đây là thứ quyết định ranking.
- **CẤM** ký tự em dash "—", emoji, giọng tin báo/trích báo.

## 6. Liên quan
Ghép cặp với một skill **research từ khoá** (giai đoạn trước: tạo brief) nếu có. Mọi output theo quy tắc **1 thư mục / 1 kết quả**.

---
*Bản skill bàn giao — sạch bí mật. Checklist SEO lõi ở `references/seo-blog-checklist.md`.*
