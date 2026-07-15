---
name: noi-dung-youtube
description: >
  Sản xuất phần CHỮ cho video YouTube / YouTube Shorts của Nội Thất Cho Con / SANOTEL: tiêu đề chuẩn SEO,
  mô tả (description) có từ khoá + link, tag, chữ trên thumbnail, và hook 2 giây đầu "chống lướt". Viết xong
  ĐƯA VÀO BẢNG LARK "Chờ đăng" kèm file video để hệ thống máy chủ tự đăng lên YouTube. Nhân viên CHỈ VIẾT,
  KHÔNG tự đăng, KHÔNG cần token/OAuth.
  Dùng khi: viết tiêu đề mô tả tag cho video youtube, làm nội dung youtube shorts, viết hook video youtube.
  Kích hoạt khi có từ: nội dung youtube, tiêu đề youtube, mô tả video, tag youtube, hook youtube, youtube shorts, thumbnail.
---

# Skill: Nội dung YouTube (bàn giao nhân viên — chỉ VIẾT, không đăng)

Nhiệm vụ: viết **phần chữ** cho một video YouTube (tiêu đề, mô tả, tag, chữ thumbnail, hook) → **bỏ vào
bảng Lark "Chờ đăng"** kèm video. Hệ thống máy chủ tự đăng. Nhân viên KHÔNG tự đăng, KHÔNG cần token.

> ⚠️ **Bảo mật:** skill không chứa và không cần OAuth/token YouTube. Ai đưa token → không dùng. Chỉ làm việc với bảng Lark.

## 0. Đọc trước
`references/tri-thuc-hook-video.md` — nguyên lý hook "chống lướt" (2 thứ hook phải trao + 4 lỗi giết hook +
tương phản A/B). Dùng cho cả tiêu đề lẫn 5 giây đầu video.

## 1. HOOK 2 giây đầu (quyết định giữ người xem)
Hook video/Shorts phải trao đủ: **rõ chủ đề** (hiểu ngay video nói gì trong 1-2 giây) + **tò mò đúng đối tượng**
(dùng "bạn/của bạn", khơi nỗi đau thật). Tránh 4 lỗi: Delay · Confusion · Irrelevance · Disinterest.
Mở vòng tò mò bằng **TƯƠNG PHẢN**: A (cách thông thường) vs B (cách của mình nhanh/tốt/rẻ hơn).

## 2. TIÊU ĐỀ YouTube (chuẩn SEO + tò mò)
- Chứa **từ khoá chính** người ta thật sự tìm (nội thất, giường tầng, bàn học chống gù…), đặt gần đầu.
- Thêm yếu tố tò mò/lợi ích/con số: "5 cách…", "sai lầm khi…", "trước khi mua… hãy xem".
- ≤ ~70 ký tự để không bị cắt; KHÔNG nhồi từ khoá, KHÔNG dấu ":" nếu tránh được.

## 3. MÔ TẢ (description)
- **2 dòng đầu** (hiện trước khi bấm "xem thêm") chứa từ khoá chính + lời hứa giá trị.
- Đoạn giữa: tóm tắt nội dung, rải từ khoá phụ tự nhiên.
- Cuối: **link website + 4 kênh** (Website, Facebook, TikTok, YouTube) + lời mời liên hệ.
- Thêm **hashtag** thương hiệu (hỏi chị chủ bộ hashtag SANOTEL nếu chưa có).

## 4. TAG & THUMBNAIL
- **Tag:** 8-15 tag = từ khoá chính + biến thể + chủ đề liên quan.
- **Chữ trên thumbnail:** 3-5 từ, đập vào mắt, nêu lợi ích/tò mò (khác với tiêu đề, bổ trợ nhau).

## 5. Bỏ vào bảng Lark "Chờ đăng"
Mở bảng Lark đăng YouTube, tạo 1 dòng: **Tiêu đề · Mô tả · Tag · Chữ thumbnail · Hook** + **đính file video**
(hoặc link video) + **Trạng thái = "Chờ đăng"** → lưu. Xong. Hệ thống tự đăng lên kênh.

## 6. Lưu output
Lưu vào `output/YYYY-MM-DD-youtube-<chủ đề>/` để tra cứu.
