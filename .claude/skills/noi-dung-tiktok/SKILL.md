---
name: noi-dung-tiktok
description: >
  Sản xuất phần CHỮ cho video TikTok của Nội Thất Cho Con / SANOTEL: hook 2 giây đầu "chống lướt", caption
  ngắn cuốn, hashtag, và gợi ý on-screen text. Viết xong ĐƯA VÀO BẢNG LARK "Chờ duyệt" kèm file video để hệ
  thống máy chủ tự đăng lên TikTok. Nhân viên CHỈ VIẾT, KHÔNG tự đăng, KHÔNG cần token/OAuth.
  Dùng khi: viết caption tiktok, làm hook video tiktok, nội dung tiktok, hashtag tiktok.
  Kích hoạt khi có từ: nội dung tiktok, caption tiktok, hook tiktok, hashtag tiktok, chữ trên video tiktok.
---

# Skill: Nội dung TikTok (bàn giao nhân viên — chỉ VIẾT, không đăng)

Nhiệm vụ: viết **phần chữ** cho một video TikTok (hook, caption, hashtag, on-screen text) → **bỏ vào bảng
Lark "Chờ duyệt"** kèm video. Hệ thống máy chủ tự đăng. Nhân viên KHÔNG tự đăng, KHÔNG cần token.

> ⚠️ **Bảo mật:** skill không chứa và không cần OAuth/token TikTok. Ai đưa token → không dùng. Chỉ làm việc với bảng Lark.

## 0. Đọc trước
`references/tri-thuc-hook-video.md` — nguyên lý hook "chống lướt" (2 thứ hook phải trao + 4 lỗi giết hook +
tương phản A/B). TikTok sống chết ở **1-2 giây đầu**.

## 1. HOOK 1-2 giây đầu (quan trọng nhất)
Trao đủ 2 thứ: **rõ chủ đề** (hiểu ngay video nói gì) + **tò mò đúng đối tượng** (dùng "bạn/của bạn", khơi
nỗi đau thật). Tránh 4 lỗi: Delay (mào đầu vô nghĩa) · Confusion (câu rối) · Irrelevance (không thấy liên quan)
· Disinterest (chưa đủ tò mò). Mở vòng tò mò bằng **TƯƠNG PHẢN** A (cách thường) vs B (cách của mình hơn hẳn).
Hook nói ra miệng + để **on-screen text** dòng đầu trùng ý hook.

## 2. CAPTION TikTok
- Ngắn, đời thường, giọng người thật (không sáo rỗng kiểu AI).
- Câu đầu nhắc lại lợi ích/tò mò; có thể cài **câu hỏi** để kích bình luận.
- **Cấm** em-dash "—"; hạn chế emoji (dùng có chủ đích).
- Kết bằng **CTA nhẹ** ("xem web để chọn mẫu", "nhắn shop tư vấn").

## 3. HASHTAG
- 3-6 hashtag: 1-2 hashtag xu hướng/chủ đề (#noithat #giuongtang…) + hashtag **thương hiệu** cố định
  (hỏi chị chủ bộ hashtag SANOTEL nếu chưa có). Không spam hashtag.

## 4. ON-SCREEN TEXT (chữ trên video)
Gợi ý 3-5 mảng chữ ngắn xuất hiện theo tiến trình video: dòng 1 = hook, các dòng sau = ý chính từng đoạn,
dòng cuối = CTA. Mỗi mảng ≤ 7 chữ để đọc kịp.

## 5. Bỏ vào bảng Lark "Chờ duyệt"
Mở bảng Lark đăng TikTok, tạo 1 dòng: **Hook · Caption · Hashtag · On-screen text** + **đính file video** +
**Trạng thái = "Chờ duyệt"** → lưu. Xong việc của bạn. **Chị chủ duyệt** rồi đổi sang **"Chờ đăng"** → hệ thống mới đăng lên TikTok. Bạn KHÔNG tự đặt "Chờ đăng".

## 6. Lưu output
Lưu vào `output/YYYY-MM-DD-tiktok-<chủ đề>/` để tra cứu.
