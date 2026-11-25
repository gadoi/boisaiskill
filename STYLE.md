# STYLE — Chuẩn Văn Phong & Trình Bày

## 1. Phong cách viết (MIT Technical Textbook Style)

Mọi tài liệu trong `swim-book` phải tuân thủ văn phong **sách kỹ thuật chuẩn MIT**:

- **Đi từ nguyên lý gốc (First Principles)**: Luôn giải thích *tại sao* trước khi hướng dẫn *làm như thế nào* (dựa trên vật lý chất lưu, cơ sinh học khớp và sinh lý năng lượng).
- **Chính xác, cô đọng, không lan man**: Mỗi đoạn văn phải mang thông tin hành động được hoặc giá trị khoa học rõ ràng; tránh văn phong quảng cáo, hô khẩu hiệu hoặc cảm tính.
- **Định lượng hóa tối đa**: Ưu tiên con số cụ thể (góc xoay hông `30–45°`, độ sâu trượt `10–15 cm`, góc khuỷu EVF `100–120°`, nhịp SPM `65–80`, tốc độ `< 1:30/100m`, SWOLF mục tiêu...).
- **Thuật ngữ song ngữ nhất quán**: Dùng thuật ngữ tiếng Việt tự nhiên kèm thuật ngữ tiếng Anh chuẩn quốc tế ở lần xuất hiện đầu tiên, ví dụ: *dựng cẳng tay sớm (Early Vertical Forearm — EVF)*, đồng bộ với [24-appendix/glossary.md](24-appendix/glossary.md).

---

## 2. Thành phần trực quan & thực hành bắt buộc

Mỗi chương chuyên môn phải tích hợp đầy đủ:

- **Ví dụ thực tế**: Tình huống bơi cụ thể (bể 25m/50m, nước mở, cự ly 100m vs 1500m).
- **Sơ đồ Mermaid**: Biểu diễn chuỗi truyền lực, chu kỳ pha động tác, hoặc cây quyết định chọn kỹ thuật/drill.
- **Hình minh họa placeholder**: Chèn chú thích rõ ràng để họa sĩ hoặc AI tạo ảnh sau này, theo định dạng:
  `![Mô tả góc nhìn và điểm nhấn cơ sinh học](../images/<chapter>-<slug>.png)`
  `<!-- IMAGE_PROMPT: Mô tả chi tiết góc quay dưới nước/trên mặt nước, đường vector lực, góc khớp cần thể hiện -->`
- **Bảng biểu so sánh**: Dùng bảng Markdown cho lỗi – nguyên nhân – cách sửa, bảng KPI theo trình độ, hoặc so sánh biến thể kỹ thuật.
- **Drills (Bài tập)**: Mô tả rõ mục đích, tư thế bắt đầu, bước thực hiện, cự ly/số hiệp và cảm giác đúng (*Proprioception Cues*).
- **Lỗi thường gặp & Cách sửa**: Chỉ ra nguyên nhân gốc (Root Cause), không chỉ mô tả triệu chứng bề mặt.
- **KPI & Checklist**: Cho phép người bơi tự đo lường tiến bộ sau mỗi buổi tập.

---

## 3. Các phần bắt buộc trong mỗi chương

Theo quy chuẩn kết hợp với [OUTPUT.md](OUTPUT.md) và [FILE_TEMPLATE.md](FILE_TEMPLATE.md), mỗi chương phải bảo đảm có đầy đủ các nội dung:

1. **Giới thiệu (Overview)**
2. **Lý thuyết & Nguyên lý vật lý (Theory / Physics)**
3. **Cơ sinh học & Thủy động lực học (Biomechanics & Hydrodynamics)**
4. **Thực hành & Mẹo nâng cao (Practical & Advanced Tips)**
5. **Hệ thống bài tập (Drills)**
6. **Phân tích AI & Video (AI Analysis)**
7. **Lỗi thường gặp & Cách sửa (Common Mistakes & Corrections)**
8. **Tự đánh giá (Self Assessment Checklist)**
9. **Chỉ số đo lường (KPI)**
10. **Câu hỏi thường gặp (FAQ)**
11. **Tóm tắt (Summary)**
12. **Tài liệu tham khảo (References)**

---

## 4. Quy ước định dạng Markdown

- Sử dụng 1 tiêu đề cấp 1 (`#`) duy nhất ở đầu file.
- Công thức toán/vật lý dùng LaTeX chuẩn (`$F_d = \frac{1}{2} \rho v^2 C_d A$`).
- Dùng khối trích dẫn cảnh báo (`> **Lưu ý kỹ thuật:** ...` hoặc `> **Cảnh báo chấn thương:** ...`) cho các điểm an toàn khớp vai/lưng dưới.
- Không dùng HTML thô nếu Markdown thuần đáp ứng được, nhằm bảo đảm tương thích 100% giữa GitBook, mdBook, MkDocs, Obsidian và Hugo.

