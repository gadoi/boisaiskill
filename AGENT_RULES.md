# AGENT_RULES — Quy Tắc Vận Hành Cho AI Agents

Tài liệu này là bộ luật bắt buộc cho mọi AI Agent (Antigravity, Codex, Claude Code...) khi biên soạn, mở rộng hoặc biên tập bất kỳ file nào trong `swim-book/`.

---

## 1. Quy tắc nội dung & cấu trúc

1. **Không lặp nội dung (DRY — Don't Repeat Yourself)**:
   - Mỗi khái niệm có đúng 1 file "nguồn sự thật" (*Single Source of Truth*).
   - Khi chương khác nhắc tới khái niệm đó (ví dụ EVF, 2-beat kick, SWOLF), chỉ tóm tắt 1–2 câu trong ngữ cảnh hiện tại và **đặt liên kết chéo Markdown** sang file gốc.
2. **Mỗi file độc lập (Standalone Readability)**:
   - Người đọc mở bất kỳ file nào trực tiếp (trên GitHub, Obsidian hoặc RAG) vẫn hiểu trọn vẹn mục tiêu, nguyên lý, cách tập và cách đo KPI của file đó.
3. **Bắt buộc có liên kết chéo (Cross-Links)**:
   - Mỗi file phải liên kết tới chương trước, chương sau, các drill liên quan trong `17-drills/` và bảng thuật ngữ `24-appendix/glossary.md`.
4. **Không viết ngắn, không viết sơ sài**:
   - Không tạo file kiểu dàn ý cụt (stub) ở các Phase đã triển khai. Mỗi file chuyên môn phải giải thích đủ sâu từ nguyên lý, cơ sinh học, thực hành tới sửa lỗi và KPI.
5. **Quy tắc chia nhỏ file (`> 1500` dòng)**:
   - Nếu bất kỳ file Markdown nào vượt quá **1.500 dòng**, bắt buộc tách thành các file chuyên đề nhỏ hơn trong cùng thư mục và cập nhật lại `SUMMARY.md`.

---

## 2. Quy tắc thành phần bắt buộc

Mỗi file chuyên môn phải có đầy đủ:
- [ ] Sơ đồ **Mermaid** hợp lệ (tránh thẻ HTML trong nhãn node; đặt dấu ngoặc kép cho nhãn chứa ký tự đặc biệt `()` hoặc `[]`).
- [ ] **Bảng Markdown** (so sánh kỹ thuật, bảng lỗi – cách sửa, bảng KPI).
- [ ] **Checklist** tự đánh giá (`- [ ]`).
- [ ] **KPI** định lượng rõ ràng.
- [ ] **Bài tập (Drills)** có định lượng cự ly/hiệp và cảm giác đúng.
- [ ] **FAQ** giải đáp thắc mắc thực tế.
- [ ] **Thuật ngữ** đồng bộ với `24-appendix/glossary.md`.
- [ ] **Tài liệu tham khảo (References)** có nguồn uy tín.

---

## 3. Quy tắc kỹ thuật & định dạng

- **Luôn dùng Markdown chuẩn (CommonMark / GFM)** để đảm bảo hiển thị tốt trên GitHub, GitBook, mdBook, MkDocs, Obsidian và Hugo.
- **Không sinh mã lập trình (code) khi không cần thiết**: Chỉ viết pseudocode hoặc schema JSON/YAML trong các chương phân tích AI (`20-ai-analysis/`, `datasets/`).
- **Cập nhật trạng thái sau mỗi Phase**: Sau khi hoàn thành một file hoặc một Phase, đánh dấu `[x]` tương ứng trong [TASKS.md](TASKS.md) và kiểm tra lại đường dẫn trong [SUMMARY.md](SUMMARY.md).
- **Kiểm duyệt bắt buộc**: Đối chiếu file vừa viết với 14 tiêu chí của [QUALITY.md](QUALITY.md) trước khi bàn giao.

