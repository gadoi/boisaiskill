# PROJECT — Freestyle Swimming Mastery

## 1. Thông tin dự án

| Thuộc tính | Giá trị |
| :--- | :--- |
| **Tên dự án** | Freestyle Swimming Mastery (`swim-book`) |
| **Chủ đề cốt lõi** | Kỹ năng bơi sải hiện đại: **Tốc độ – Tay nhẹ – Lực từ thân (Core + Hông)** |
| **Ngôn ngữ** | Tiếng Việt (kèm thuật ngữ chuyên ngành tiếng Anh chuẩn quốc tế) |
| **Quy mô mục tiêu** | 150–300 trang A4 tương đương (~150.000–250.000 từ Markdown) |
| **Kiến trúc** | Modular Markdown Knowledge Base (AI-Agent Ready) |
| **Chuẩn đầu ra** | Ebook (PDF/EPUB), GitBook, mdBook, MkDocs, Obsidian, Hugo, AI Knowledge Base |

---

## 2. Mục tiêu dự án

Xây dựng bộ tài liệu và cơ sở tri thức Markdown hoàn chỉnh, khoa học và thực chiến nhất bằng tiếng Việt về **bơi sải hiện đại (Modern Freestyle / Front Crawl)** — từ nền tảng vật lý, cơ sinh học, thủy động lực học cho tới hệ thống bài tập (Drills), giáo án 24 tuần hướng tới mốc `< 1:30/100m`, phân tích VĐV Olympic và quy trình phân tích video bằng AI.

### Triết lý kỹ thuật xuyên suốt
1. **Bơi bằng thân (Core + Hông), không bơi bằng tay**: Trục truyền lực chuẩn `Chân → Hông → Core → Vai → Tay → Nước`.
2. **Giảm lực cản trước khi tăng lực đẩy**: Vì lực cản tăng theo $v^2$ và công suất tiêu hao tăng theo $v^3$, tối ưu tư thế (Streamline, Balance, Alignment) luôn hiệu quả hơn cố kéo tay mạnh.
3. **Tay nhẹ, vai bền, hiệu suất cao**: Dựng cẳng tay sớm (EVF) huy động cơ xô (*Latissimus Dorsi*), pha rút tay trên không thả lỏng hoàn toàn, tối ưu DPS, Stroke Count, Tempo và SWOLF.

---

## 3. Đối tượng độc giả

- **Người mới (Beginner)**: Cần xây dựng cảm giác nước, tư thế nổi và nhịp thở đúng ngay từ đầu để tránh hình thành lỗi kỹ thuật cố hữu.
- **Người bơi phong trào (Fitness / Recreational Swimmer)**: Muốn bơi xa hơn, nhẹ hơn, không đau vai và bứt phá qua ngưỡng tốc độ cũ (`2:00 → 1:30/100m`).
- **Triathlete (3 môn phối hợp)**: Cần bơi tiết kiệm năng lượng (ưu tiên 2-beat kick, DPS cao, định hướng tốt) để giữ sức cho đạp xe và chạy bộ.
- **Open Water Swimmer**: Cần thích nghi với sóng, dòng chảy, kỹ thuật ngắm mục tiêu (Sighting) và Drafting.
- **Master Swimmer**: Cần tối ưu hóa hiệu suất cơ sinh học, bảo vệ khớp vai và duy trì tốc độ bền vững theo độ tuổi.
- **Huấn luyện viên (Coach)**: Cần khung đánh giá có cấu trúc, hệ thống Drill theo nguyên nhân lỗi, bảng KPI và quy trình phân tích video/AI.

---

## 4. Nguyên tắc vận hành với AI Agent

Dự án được thiết kế để nhiều AI Agent (Antigravity, Codex, Claude Code...) cùng biên soạn như **một nhóm kỹ sư và biên tập viên**, tuân thủ nghiêm ngặt bộ quy chuẩn gốc:

- [STYLE.md](STYLE.md) — Văn phong và yêu cầu trình bày chuẩn sách kỹ thuật MIT.
- [OUTPUT.md](OUTPUT.md) — Danh mục các phần bắt buộc trong mỗi tài liệu.
- [FILE_TEMPLATE.md](FILE_TEMPLATE.md) — Khung mẫu Markdown chuẩn hóa.
- [DIRECTORY.md](DIRECTORY.md) — Kiến trúc thư mục 24 chương + 8 kho tri thức.
- [TASKS.md](TASKS.md) — Lộ trình triển khai 12 Phase.
- [AGENT_RULES.md](AGENT_RULES.md) — Luật biên soạn, liên kết chéo và giới hạn độ dài file.
- [QUALITY.md](QUALITY.md) — Bộ 14 tiêu chí kiểm duyệt đầu ra.

