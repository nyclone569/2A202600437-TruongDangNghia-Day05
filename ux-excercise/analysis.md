# Bài tập UX: phân tích sản phẩm AI thật

**Thời gian:** 40 phút | **Cá nhân** | **Output:** sketch giấy, nộp cuối bài

---

## Chọn 1 sản phẩm

| Sản phẩm | AI feature | Truy cập |
|----------|-----------|---------|
| MoMo — Trợ thủ AI Moni | Phân loại chi tiêu, chatbot tài chính | App MoMo |
| Vietnam Airlines — Chatbot NEO | Chatbot hỗ trợ khách hàng, tra cứu chuyến bay | vietnamairlines.com hoặc Zalo VNA |
| V-App — Trợ lý ảo V-AI | Trợ lý voice/text, gợi ý theo context | App V-App |

---

-> Chọn sản phẩm MoMo - Trợ thủ AI Moni

## Phần 1 — Khám phá (15 phút)

**Trước khi dùng:** theo marketing:

- Tự động hóa hoàn toàn
- Thông minh và thấu cảm
- Cá nhân hóa cao
- An toàn và tin cậy

**Rồi dùng thử** - thực tế:

- Có tự động nhận loại chi tiêu khi số lượng giao dịch đủ nhiều
Không chắc chắn, yêu cầu thường lặp lại
- Có thống kê chung chung và đưa ra lời khuyên chung
- Có an toàn khi không còn truy cập giao dịch của người khác, nhưng không liên lợi ích cá nhân, trả lời quá chung

## Phần 2 — Phân tích 4 paths (10 phút)

Dùng framework 4 paths để mổ xẻ sản phẩm:

| Path | Câu hỏi | Quan sát thực tế |
|------|---------|----------------|
| 1. Khi AI **đúng** | User thấy gì? Hệ thống confirm thế nào? | Khi AI nhận diện đúng (thanh toán với CGV) → hệ thống gán tag giao dịch → Trả lời, dữ tốn thói quen thống kê → Tin tưởng vào app |
| 2. Khi AI **không chắc** | Hệ thống xử lý thế nào? Im lặng? Hỏi lại? Show alternatives? | AI chưa nhận đủ thông tin sẽ cho ra thống kê chung và yêu cầu thêm chi tiết để thống kê → Yêu cầu thêm thông tin làm gợi ý |
| 3. Khi AI **sai** | User biết bằng cách nào? Sửa bằng cách nào? Bao nhiêu bước? | User phát hiện ra lỗi sai → (a) Can tag bị sai hoàn thống kê → tự sửa thủ công → Giảm trust; (b) Ảnh hưởng lớn → Giảm trust + tốn thời gian |
| 4. Khi user **mất tin** | Có exit không? Có fallback (con người, manual)? Dễ tìm không? | App báo trì im lặng, giao dịch chậm, bị xếp vào "chờ xử lý", user hoang mang → Mất hoàn toàn niềm tin |

**Tự phân tích:**
- Path xử lý tốt nhất: Path 1 (khi AI đúng) — hệ thống gán tag tự động và xây dựng thói quen thống kê tốt, tạo trust.
- Path yếu nhất: Path 3 (khi AI sai phân loại) — không có nút sửa trực tiếp, phải vào settings để sửa, thống kê sai → mất trust.
- Gap marketing vs thực tế: Kỳ vọng "cá nhân hóa cao" nhưng thực tế trả lời quá chung khi thiếu dữ liệu; "tự động hóa hoàn toàn" nhưng vẫn cần user lặp lại xác nhận.

## Phần 3 — Sketch "làm tốt hơn" (10 phút)

**Path yêu thích nhất**: AI bị sai phân loại

- **As-is** (bên trái): Giao dịch gán tag sai -> Không có nút sửa trực tiếp, phải vào settings để sửa -> Thống kê sai -> Mất trust
- **To-be** (bên phải): Thêm nút sửa trực tiếp dạng pop-up lựa chọn -> Cho Moni học mapping giao dịch đó cho những lần sau -> User chủ động dạy AI

---

*Bài tập UX — Ngày 5 — VinUni A20 — AI Thực Chiến · 2026*
