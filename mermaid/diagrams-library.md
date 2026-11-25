# Thư Viện Sơ Đồ Mermaid Chuẩn Hóa (`mermaid/diagrams-library.md`)

> **Thuộc phần:** `mermaid/` | **Mục đích:** Kho tập trung các sơ đồ luồng chuyển động, chuỗi truyền lực, cây quyết định sửa lỗi và kiến trúc giáo án có thể tái sử dụng trực tiếp trên GitHub, Obsidian, GitBook, MkDocs và Hugo.

---

## 1. Chuỗi Truyền Lực Cốt Lõi (*Master Kinetic Chain*)

```mermaid
flowchart LR
    A["1. Chân\n(Ổn định & Kích hoạt)"] --> B["2. Hông\n(Xoay 30–45°)"]
    B --> C["3. Core\n(Khóa trục 20–30%)"]
    C --> D["4. Vai & Cơ Xô\n(Latissimus Dorsi)"]
    D --> E["5. Cẳng Tay EVF\n(Góc khuỷu 100–120°)"]
    E --> F["6. Lực Đẩy Tiến\n(Tay nhẹ, tốc độ cao)"]
```

---

## 2. Chu Kỳ Sải Tay Đầy Đủ (*Full Freestyle Stroke Cycle*)

```mermaid
flowchart LR
    A["Hand Entry\n('Xỏ kim' 11h / 1h)"] --> B["Glide / Extension\n(Sâu 10–15 cm, Front-Quadrant)"]
    B --> C["Catch — EVF\n(Khuỷu cao, cẳng tay dựng 110°)"]
    C --> D["Mid-Pull\n(Cơ Xô + Xoay Hông 40°)"]
    D --> E["Push / Finish\n(Tăng tốc MAX tới mép đùi)"]
    E --> F["Relaxed Recovery\n(Khuỷu dẫn hướng, cổ tay thả lỏng)"]
    F --> A
```

---

## 3. Cây Quyết Định Chẩn Đoán & Sửa Lỗi 4 Tầng (*Root-Cause Diagnostic Tree*)

```mermaid
flowchart TD
    START["Bắt Đầu Phân Tích Kỹ Thuật"] --> L1{"Tầng 1: Đầu & Thở ổn chưa?\n(Nhìn đáy, thở bọt, 1 mắt kính)"}
    L1 -->|"Chưa"| F1["Sửa Tầng 1 Trước!\n(Sink-Downs + Side-Glide One-Goggle)"]
    L1 -->|"Đạt"| L2{"Tầng 2: Hông nổi < 5°\n& Không Scissor Kick?"}
    L2 -->|"Chưa"| F2["Sửa Tầng 2!\n(Press the T + Pull Buoy + Core)"]
    L2 -->|"Đạt"| L3{"Tầng 3: Entry 11h/1h\n& Xoay đều 35–45°?"}
    L3 -->|"Chưa"| F3["Sửa Tầng 3!\n(Wide Catch-Up + 6-Kick Switch)"]
    L3 -->|"Đạt"| L4{"Tầng 4: EVF 110°, Push tới đùi\n& Điểm Ngọt SPM?"}
    L4 -->|"Chưa"| F4["Sửa Tầng 4!\n(Sculling + Dog Paddle + Tempo Trainer)"]
    L4 -->|"Đạt"| PEAK["Sẵn Sàng Đẩy CSS, VO2max\n& Taper Phá Mốc < 1:30/100m!"]
```

---

## 4. Ma Trận Chọn Nhịp Chân Theo Cự Ly (*Kick Gear-Shift Matrix*)

```mermaid
flowchart LR
    A["Chọn Nhịp Chân Theo Mục Tiêu"] --> B["Đường Dài / Triathlon\n(800m – 3.8km)\n→ 2-Beat Kick (-30% O₂)"]
    A --> C["Trung Bình / Ngưỡng CSS\n(200m – 800m)\n→ 4-Beat Kick (3+1 / 2+2)"]
    A --> D["Tốc Độ Cao / Nước Rút\n(50m – 200m & 25m cuối)\n→ 6-Beat Kick (Hydroplaning)"]
```

---

## 5. Kiến Trúc Giáo Án 24 Tuần (`< 1:30/100m` Roadmap)

```mermaid
flowchart LR
    B1["Block 1 (W01–04)\nTư Thế & Cân Bằng\n(CSS Test #1)"] --> B2["Block 2 (W05–08)\nXoay Hông & EVF\n(CSS Test #2)"]
    B2 --> B3["Block 3 (W09–12)\nNền Hiếu Khí 2/4-Beat\n(Ramp Test SPM)"]
    B3 --> B4["Block 4 (W13–16)\nNgưỡng CSS MLSS\n(CSS Test #3 + Video)"]
    B4 --> B5["Block 5 (W17–20)\nVO2max & Sprint Z5\n(Test 100m Mô Phỏng)"]
    B5 --> B6["Block 6 (W21–24)\nTaper Siêu Bù Trừ\n(FINAL < 1:30/100m)"]
```

---

## 6. Pipeline Phân Tích Bơi Sải Bằng AI (*Computer Vision Architecture*)

```mermaid
flowchart LR
    V["4-Angle Video\n(1080p @ 60–120fps Linear)"] --> P["CLAHE Underwater\nPreprocessing"]
    P --> K["Pose Estimation\n(19–21 Keypoints)"]
    K --> S["Butterworth Filter\n& Bubble Interpolation"]
    S --> M["Kinematics & Events\n(EVF, IdC, SPM, DPS, Kick)"]
    M --> R["Error Classification\n& Drill Recommendation"]
```

---

*Quay lại: [SUMMARY.md](../SUMMARY.md) · [README.md](../README.md)*

