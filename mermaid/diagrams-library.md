# Thư Viện Sơ Đồ Mermaid Chuẩn Hóa (`mermaid/diagrams-library.md`)

> **Thuộc phần:** `mermaid/` | **Mục đích:** Kho tập trung các sơ đồ luồng chuyển động, chuỗi truyền lực, cây quyết định sửa lỗi và kiến trúc giáo án có thể tái sử dụng trực tiếp trên GitHub, Obsidian, GitBook, MkDocs và Hugo.

---

## 1. Chuỗi Truyền Lực Cốt Lõi (*Master Kinetic Chain*)

```mermaid
flowchart LR
    A["1. Chân<br/>(Ổn định & Kích hoạt)"] --> B["2. Hông<br/>(Xoay 30–45°)"]
    B --> C["3. Core<br/>(Khóa trục 20–30%)"]
    C --> D["4. Vai & Cơ Xô<br/>(Latissimus Dorsi)"]
    D --> E["5. Cẳng Tay EVF<br/>(Góc khuỷu 100–120°)"]
    E --> F["6. Lực Đẩy Tiến<br/>(Tay nhẹ, tốc độ cao)"]
```

---

## 2. Chu Kỳ Sải Tay Đầy Đủ (*Full Freestyle Stroke Cycle*)

```mermaid
flowchart LR
    A["Hand Entry<br/>('Xỏ kim' 11h / 1h)"] --> B["Glide / Extension<br/>(Sâu 10–15 cm, Front-Quadrant)"]
    B --> C["Catch — EVF<br/>(Khuỷu cao, cẳng tay dựng 110°)"]
    C --> D["Mid-Pull<br/>(Cơ Xô + Xoay Hông 40°)"]
    D --> E["Push / Finish<br/>(Tăng tốc MAX tới mép đùi)"]
    E --> F["Relaxed Recovery<br/>(Khuỷu dẫn hướng, cổ tay thả lỏng)"]
    F --> A
```

---

## 3. Cây Quyết Định Chẩn Đoán & Sửa Lỗi 4 Tầng (*Root-Cause Diagnostic Tree*)

```mermaid
flowchart TD
    START["Bắt Đầu Phân Tích Kỹ Thuật"] --> L1{"Tầng 1: Đầu & Thở ổn chưa?<br/>(Nhìn đáy, thở bọt, 1 mắt kính)"}
    L1 -->|"Chưa"| F1["Sửa Tầng 1 Trước!<br/>(Sink-Downs + Side-Glide One-Goggle)"]
    L1 -->|"Đạt"| L2{"Tầng 2: Hông nổi < 5°<br/>& Không Scissor Kick?"}
    L2 -->|"Chưa"| F2["Sửa Tầng 2!<br/>(Press the T + Pull Buoy + Core)"]
    L2 -->|"Đạt"| L3{"Tầng 3: Entry 11h/1h<br/>& Xoay đều 35–45°?"}
    L3 -->|"Chưa"| F3["Sửa Tầng 3!<br/>(Wide Catch-Up + 6-Kick Switch)"]
    L3 -->|"Đạt"| L4{"Tầng 4: EVF 110°, Push tới đùi<br/>& Điểm Ngọt SPM?"}
    L4 -->|"Chưa"| F4["Sửa Tầng 4!<br/>(Sculling + Dog Paddle + Tempo Trainer)"]
    L4 -->|"Đạt"| PEAK["Sẵn Sàng Đẩy CSS, VO2max<br/>& Taper Phá Mốc < 1:30/100m!"]
```

---

## 4. Ma Trận Chọn Nhịp Chân Theo Cự Ly (*Kick Gear-Shift Matrix*)

```mermaid
flowchart LR
    A["Chọn Nhịp Chân Theo Mục Tiêu"] --> B["Đường Dài / Triathlon<br/>(800m – 3.8km)<br/>→ 2-Beat Kick (-30% O₂)"]
    A --> C["Trung Bình / Ngưỡng CSS<br/>(200m – 800m)<br/>→ 4-Beat Kick (3+1 / 2+2)"]
    A --> D["Tốc Độ Cao / Nước Rút<br/>(50m – 200m & 25m cuối)<br/>→ 6-Beat Kick (Hydroplaning)"]
```

---

## 5. Kiến Trúc Giáo Án 24 Tuần (`< 1:30/100m` Roadmap)

```mermaid
flowchart LR
    B1["Block 1 (W01–04)<br/>Tư Thế & Cân Bằng<br/>(CSS Test #1)"] --> B2["Block 2 (W05–08)<br/>Xoay Hông & EVF<br/>(CSS Test #2)"]
    B2 --> B3["Block 3 (W09–12)<br/>Nền Hiếu Khí 2/4-Beat<br/>(Ramp Test SPM)"]
    B3 --> B4["Block 4 (W13–16)<br/>Ngưỡng CSS MLSS<br/>(CSS Test #3 + Video)"]
    B4 --> B5["Block 5 (W17–20)<br/>VO2max & Sprint Z5<br/>(Test 100m Mô Phỏng)"]
    B5 --> B6["Block 6 (W21–24)<br/>Taper Siêu Bù Trừ<br/>(FINAL < 1:30/100m)"]
```

---

## 6. Pipeline Phân Tích Bơi Sải Bằng AI (*Computer Vision Architecture*)

```mermaid
flowchart LR
    V["4-Angle Video<br/>(1080p @ 60–120fps Linear)"] --> P["CLAHE Underwater<br/>Preprocessing"]
    P --> K["Pose Estimation<br/>(19–21 Keypoints)"]
    K --> S["Butterworth Filter<br/>& Bubble Interpolation"]
    S --> M["Kinematics & Events<br/>(EVF, IdC, SPM, DPS, Kick)"]
    M --> R["Error Classification<br/>& Drill Recommendation"]
```

---

*Quay lại: [SUMMARY.md](../SUMMARY.md) · [README.md](../README.md)*

