# DIRECTORY — Kiến Trúc Thư Mục Dự Án `swim-book`

Dự án kết hợp **24 chương sách chuyên khảo** (đánh số tuyến tính từ nền tảng đến thi đấu & phụ lục) với **8 thư mục Knowledge Base** hỗ trợ nghiên cứu, trực quan hóa và phân tích AI.

```text
swim-book/
│
├── README.md                 # Trang chủ dự án, hướng dẫn đọc và build sách
├── SUMMARY.md                # Mục lục tổng (tương thích GitBook / mdBook / MkDocs)
├── skill.md                  # Bản tóm tắt thực chiến kỹ năng bơi sải nâng cao
│
├── PROJECT.md                # Tuyên ngôn và phạm vi dự án
├── STYLE.md                  # Chuẩn văn phong sách kỹ thuật MIT
├── OUTPUT.md                 # Chuẩn các mục đầu ra bắt buộc
├── DIRECTORY.md              # Kiến trúc thư mục (file hiện tại)
├── TASKS.md                  # Lộ trình triển khai 12 Phase
├── FILE_TEMPLATE.md          # Mẫu chuẩn tạo file Markdown mới
├── AGENT_RULES.md            # Quy tắc làm việc cho AI Agents
├── QUALITY.md                # Cổng kiểm duyệt 14 tiêu chí chất lượng
│
├── 01-foundation/            # Vật lý bơi, nguyên lý nền tảng, trọng tâm & tâm nổi
├── 02-biomechanics/          # Cơ sinh học khớp vai, chuỗi truyền lực, nhóm cơ chủ đạo
├── 03-hydrodynamics/         # Lực cản hình học/ma sát/sóng, lực đẩy & hiệu ứng Bernoulli
├── 04-body-position/         # Tư thế thân ngang, Streamline, Balance, Head-Hip Alignment
├── 05-core/                  # Ổn định lõi, chống võng lưng, liên kết hông-ngực
├── 06-rotation/              # Xoay trục dọc 30–45°, đồng bộ hông-vai, tạo mô-men xoắn
├── 07-breathing/             # Thở song phương/đơn phương, thở ra dưới nước, nhịp thở theo pace
├── 08-kicking/               # 2-beat, 4-beat, 6-beat kick, độ dẻo cổ chân, Dolphin & Timing
├── 09-catch/                 # Hand Entry, Glide, Early Vertical Forearm (EVF), ôm nước
├── 10-pull/                  # Pha kéo (Insweep/Mid-pull), pha đẩy (Push/Finish), dùng cơ xô
├── 11-recovery/              # Rút tay thả lỏng, High-Elbow Recovery, Straight-Arm Recovery
├── 12-rhythm/                # Nhịp điệu, Front-Quadrant Timing, phối hợp tay-chân-thở
├── 13-dps/                   # Distance Per Stroke — tối đa hóa quãng đường mỗi sải
├── 14-stroke-count/          # Giảm Stroke Count, tối ưu Tempo (SPM), SWOLF & năng lượng
├── 15-open-water/            # Bơi nước mở: Sighting, Drafting, sóng, dòng chảy, định hướng
├── 16-sprint/                # Chiến thuật tốc độ cao, xuất phát (Starts), lộn vòng (Turns)
├── 17-drills/                # Kho bài tập: TI, SwimSmooth, Olympic + 9+ Drill kinh điển
├── 18-strength/              # Tập cạn (Dryland): Core, Lat, Resistance Band, Medicine Ball
├── 19-mobility/              # Độ linh hoạt khớp vai, cột sống ngực (T-Spine), cổ chân
├── 20-ai-analysis/           # Phân tích AI: Pose Detection, Joint Angle, Stroke/Kick/Breath
├── 21-video-analysis/        # Quy trình quay video đa góc, gắn nhãn và đọc lỗi khung hình
├── 22-training-plan/         # Giáo án 24 tuần đầy đủ cho 3, 4, 5, 6 buổi/tuần (< 1:30/100m)
├── 23-checklists/            # Bảng kiểm tự đánh giá, đánh giá của HLV và đánh giá qua video
├── 24-appendix/              # Thuật ngữ song ngữ, tài liệu tham khảo, tổ chức chuẩn quốc tế
│
├── papers/                   # Tóm tắt nghiên cứu khoa học (PubMed, Sports Biomechanics...)
├── images/                   # Hình minh họa, sơ đồ giải phẫu & ảnh placeholder
├── mermaid/                  # Kho sơ đồ Mermaid độc lập tái sử dụng nhiều chương
├── videos/                   # Danh mục video tham khảo, góc quay mẫu & phân tích
├── datasets/                 # Schema dữ liệu mẫu cho bài toán CV/AI phân tích động tác bơi
├── coach-notes/              # Ghi chú thực chiến và kinh nghiệm sửa lỗi từ HLV
├── athletes/                 # Hồ sơ phân tích kỹ thuật VĐV Olympic (Dressel, Popovici...)
└── benchmarks/               # Bảng chuẩn SWOLF, CSS, DPS, 100m/400m/1500m theo trình độ
```

---

## Quy ước đặt tên file

- Toàn bộ tên file và thư mục dùng **chữ thường, gạch nối (`kebab-case`)**, không dấu tiếng Việt, ví dụ: `early-vertical-forearm.md`, `two-beat-kick.md`, `week-01-04.md`.
- Mỗi thư mục chương lớn có thể có file `README.md` (hoặc `index.md`) đóng vai trò bản đồ chương khi thư mục có từ 4 file trở lên.
- Ngoại lệ duy nhất cho chữ HOA: các file gốc chuẩn hóa (`README.md`, `SUMMARY.md`, `PROJECT.md`, `STYLE.md`, `OUTPUT.md`, `DIRECTORY.md`, `TASKS.md`, `FILE_TEMPLATE.md`, `AGENT_RULES.md`, `QUALITY.md`).

