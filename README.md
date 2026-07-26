# Speech Emotion Recognition

Dự án nhận diện cảm xúc từ giọng nói (Speech Emotion Recognition) sử dụng dataset **RAVDESS**.

Đây là đồ án môn **Data Mining**, được thực hiện trên **Kaggle** với notebook bao gồm phân tích dữ liệu (EDA), tiền xử lý và xây dựng mô hình phân loại cảm xúc.

---

## 📌 Tổng quan

- **Dataset:** RAVDESS Emotional Speech Audio
- **Số mẫu:** 1,440 file audio (`.wav`)
- **Số diễn viên:** 24 (12 nam, 12 nữ)
- **Số lớp cảm xúc:** 8
- **Mục tiêu:** Phân tích dữ liệu và xây dựng mô hình phân loại cảm xúc từ tín hiệu giọng nói.

### Các cảm xúc

| ID | Emotion |
|----|---------|
| 01 | Neutral |
| 02 | Calm |
| 03 | Happy |
| 04 | Sad |
| 05 | Angry |
| 06 | Fearful |
| 07 | Disgust |
| 08 | Surprised |

> Phân bố dữ liệu gần như cân bằng (mỗi cảm xúc khoảng **192 mẫu**, riêng **Neutral** có **96 mẫu**).

---

## 📂 Cấu trúc dự án

```text
Speech-Emotion-Recognition/
│
├── notebooks/
│   └── speech_emotion_recognition.ipynb   # Notebook chính (EDA + Modeling)
│
├── docs/
│   └── DataMining.pdf                     # Báo cáo môn Data Mining
│
├── requirements.txt
└── README.md
```

---

## 📊 Dataset

Dự án sử dụng **RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)**.

Thông tin dataset:

- 24 diễn viên (12 nam, 12 nữ)
- 1,440 file âm thanh định dạng `.wav`
- 8 cảm xúc
- Chất lượng ghi âm đồng nhất
- Dataset được sử dụng rộng rãi trong các bài toán Speech Emotion Recognition (SER)

---

## 🚀 Cách chạy

### 1. Clone repository

```bash
git clone https://github.com/TBang1911/Speech-Emotion-Recognition.git
cd Speech-Emotion-Recognition
```

### 2. Cài đặt thư viện

```bash
pip install -r requirements.txt
```

### 3. Mở notebook

```bash
jupyter notebook notebooks/speech_emotion_recognition.ipynb
```



---

## 👤 Tác giả

**Thái Minh Khang**

- Email: **tkol.3975@gmail.com**
- GitHub: **https://github.com/TBang1911**
