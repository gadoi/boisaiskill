# QUALITY — Cổng Kiểm Duyệt 14 Tiêu Chí

Mọi file nội dung trong `swim-book/` phải vượt qua toàn bộ **14 tiêu chí** sau trước khi được đánh dấu hoàn thành trong [TASKS.md](TASKS.md).

---

## Bảng kiểm chất lượng (Quality Gate)

| # | Tiêu chí | Mô tả kiểm tra | Đạt |
| :-: | :--- | :--- | :-: |
| 1 | **Chính xác (Accuracy)** | Đúng nguyên lý vật lý, giải phẫu cơ sinh học và khuyến nghị an toàn khớp vai/cột sống | ✓ |
| 2 | **Có nguồn (References)** | Trích dẫn tài liệu khoa học, sách chuyên khảo hoặc tổ chức bơi uy tín | ✓ |
| 3 | **Có sơ đồ (Diagram / Placeholder)** | Có sơ đồ trực quan và/hoặc image placeholder kèm mô tả góc nhìn | ✓ |
| 4 | **Có ví dụ (Examples)** | Có tình huống thực tế cụ thể (bể 25m/50m, nước mở, cự ly/tốc độ cụ thể) | ✓ |
| 5 | **Có Drill** | Có bài tập nước/cạn cụ thể kèm số hiệp, cự ly và cảm giác nước (Cue) | ✓ |
| 6 | **Có Lỗi (Common Mistakes)** | Chỉ ra rõ triệu chứng và nguyên nhân gốc cơ sinh học/thủy động | ✓ |
| 7 | **Có Sửa (Corrections)** | Mỗi lỗi đều có phương án sửa trực tiếp tương ứng | ✓ |
| 8 | **Có KPI** | Có chỉ số định lượng (DPS, SWOLF, SPM, góc khớp, pace) theo trình độ | ✓ |
| 9 | **Có Checklist** | Có danh sách tự kiểm tra dạng `- [ ]` áp dụng được ngay tại hồ | ✓ |
| 10 | **Có Summary** | Tóm lược ngắn gọn 3–5 ý cốt lõi + liên kết chéo sang chương liên quan | ✓ |
| 11 | **Có FAQ** | Giải đáp 3–5 câu hỏi thực tế hay gặp của người bơi | ✓ |
| 12 | **Có Mermaid** | Có tối thiểu 1 khối ` ```mermaid ` đúng cú pháp, không lỗi render | ✓ |
| 13 | **Có Bảng (Tables)** | Có bảng so sánh/lỗi/KPI định dạng chuẩn GFM | ✓ |
| 14 | **Có Glossary Link** | Thuật ngữ song ngữ nhất quán và liên kết tới `24-appendix/glossary.md` | ✓ |

---

## Quy trình Audit cuối mỗi Phase

1. Kiểm tra 100% file trong Phase khớp với cấu trúc [FILE_TEMPLATE.md](FILE_TEMPLATE.md).
2. Kiểm tra không có file nào vượt quá 1.500 dòng (nếu vượt, tách nhỏ theo [AGENT_RULES.md](AGENT_RULES.md)).
3. Kiểm tra không có liên kết nội bộ bị gãy (broken links) giữa `SUMMARY.md` và các file con.
4. Kiểm tra cú pháp toàn bộ sơ đồ Mermaid.
5. Cập nhật trạng thái `[x]` vào [TASKS.md](TASKS.md).

