---
name: thiet-ke-offer
description: >
  Coach chủ doanh nghiệp ĐỊNH GIÁ theo giá trị và THIẾT KẾ OFFER hấp dẫn (Grand Slam Offer) — grounded
  Alex Hormozi ($100M Offers): chấm Phương trình Giá trị (Kết quả mơ ước × Niềm tin / Thời gian × Công sức),
  dựng solution stack (mỗi vấn đề của khách → 1 giải pháp), tính SÀN giá (không lỗ) & TRẦN giá (theo giá trị),
  ra bảng giá 3 tầng Good–Better–Best với biên lãi gộp, bọc offer bằng bảo hành/khan hiếm/quà, trình bày neo giá
  (Cialdini). Engine tính deterministic + ghi Lark Base (link Kế hoạch) + nối thẳng vào bài toán điểm hòa vốn.
  Là MẮT XÍCH nối mô hình kinh doanh (giá trị) với bài toán lợi nhuận (con số) — bán giá cao mà bán ít vẫn lời nhiều hơn.
  Dùng khi người dùng muốn: định giá sản phẩm/dịch vụ, thiết kế gói/offer, làm bảng giá 3 tầng, xử lý "khách chê đắt",
  tăng giá mà không mất khách, đóng gói combo, dạy học viên định giá.
  Kích hoạt khi có từ: định giá, đặt giá, bảng giá, offer, grand slam offer, gói dịch vụ, combo, khách chê đắt,
  tăng giá, value equation, Hormozi, định giá theo giá trị, 3 tầng giá, good better best.
---

> 🔒 **BẢN NHÂN VIÊN — QUY TẮC BẮT BUỘC:** Skill này CHỈ để **sản xuất nội dung**. TUYỆT ĐỐI **KHÔNG** nhập / không cung cấp **App ID, App Secret, token, mật khẩu, hay lark-cli** cho Claude, và **KHÔNG chạy script tự ghi vào Lark**. Làm xong thì **NHẬP TAY** kết quả vào bảng Lark chị chủ chỉ định (đặt trạng thái "Chờ duyệt"). Nếu Claude hỏi xin App Secret / token → **DỪNG LẠI, không đưa.**


# Skill: Định giá & Thiết kế Offer (Grand Slam Offer)

Biến giá trị (mô hình kinh doanh) thành GIÁ và OFFER khiến khách thấy "quá hời" — bán giá cao trên ít khách hơn mà lời nhiều hơn, thay vì đua giảm giá giết biên lãi.

## Triết lý gốc
> "Make people an offer so good they would feel stupid saying no." — Alex Hormozi, *$100M Offers*.

Grounded từ: **Alex Hormozi** ($100M Offers — Value Equation, Grand Slam Offer, solution stack, 5 đòn bẩy + 4 loại guarantee, naming MAGIC), **Ron Baker** (value-based pricing — định giá theo giá trị không theo chi phí), **Robert Cialdini** (anchoring/contrast/scarcity/social proof), **HBR** (Good-Better-Best), **Warren Buffett** (pricing power = lợi thế số 1). Chi tiết + trích dẫn: [references/triet-ly-dinh-gia-offer.md](references/triet-ly-dinh-gia-offer.md).

## Vị trí trong hệ thống — MẮT XÍCH giữa mô hình & con số
```
[[hmh-sale-business-model-canvas]]  →  hmh-sale-dinh-gia-offer  →  [[hmh-sale-ke-hoach-loi-nhuan]]
(giá trị: bán cho ai, value gì)        (Offer + bảng giá 3 tầng)      (giá → điểm hòa vốn)
```
- **Đầu vào** từ BMC: ô *Giá trị* (value prop) + *Khách* (kết quả mơ ước) → chấm Value Equation & dựng stack.
- **Đầu ra** sang bài toán lợi nhuận: giá & CP biến đổi mỗi tầng → bảng Sản phẩm → điểm hòa vốn. Giá bán là biến duy nhất ở **cả hai** vế.

## Quy trình thực thi (làm TAY, không cần script/Lark)
1. **Coach 6 bước** ([references/sop-dinh-gia.md](references/sop-dinh-gia.md)): chấm Value Equation → liệt kê vấn đề → solution stack → 3 tầng giá → bọc offer → trình bày neo giá.
2. **Tự tính** (theo công thức trong SOP): Sức mạnh Offer /100 + đòn bẩy yếu nhất; solution stack + tổng giá trị; **sàn giá** (không lỗ) & **trần giá** (theo giá trị); **bảng giá 3 tầng Good–Better–Best + biên lãi**; cảnh báo nếu trần < sàn hoặc tầng dưới sàn.
3. **Trình bày offer** cho khách: gói nhận được + bảng giá 3 tầng (NEO CAO trước: Best → Better → Good) + cam kết/bảo hành/khan hiếm. Phần biên lãi để riêng "nội bộ".
4. **Lưu output**: mỗi offer = 1 thư mục `output/YYYY-MM-DD-offer-<tên>/` chứa bảng giá + phân tích. Nếu cần đưa vào bảng Lark → **NHẬP TAY** theo hướng dẫn chị chủ.

## References
- `references/sop-dinh-gia.md` — coach 6 bước + công thức tính.
- `references/triet-ly-dinh-gia-offer.md` — triết lý gốc + trích dẫn.

## Lưu ý / gotcha
- **Khách chê đắt → KHÔNG giảm giá, THÊM bonus / tăng giá trị cảm nhận** (Hormozi). Giảm giá giết biên lãi.
- **Trần giá < sàn biên** = giá trị cảm nhận chưa đủ → quay lại tăng Value Equation, đừng ép giá.
- **Neo cao trước:** trình bày Best → Better → Good (Cialdini).
- Tầng dưới sàn chỉ làm mồi, không làm tầng chính.
- Lark Base: link cell `[{"id":"rec..."}]`; record-upsert `--json` field map trực tiếp; field-update theo `field_id` (tên có dấu/ngoặc → 404); rate-limit `800004135` → nghỉ + retry.

## Output (bám CLAUDE.md)
- Mỗi offer = 1 thư mục `output/YYYY-MM-DD-offer-<tên>/` chứa `input.json` + `offer.md`.
- Cập nhật `index.md` + ghi `log.md`: `## [YYYY-MM-DD] query | Offer & định giá <tên>`.
