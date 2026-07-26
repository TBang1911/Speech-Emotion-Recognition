# Speech Emotion Recognition

Dự án nhận diện cảm xúc từ giọng nói (Speech Emotion Recognition) sử dụng dataset **RAVDESS**.

Đây là đồ án môn **Data Mining**, thực hiện trên Kaggle với notebook phân tích dữ liệu, tiền xử lý và xây dựng mô hình phân loại cảm xúc.

## Tổng quan

- **Dataset**: RAVDESS Emotional Speech Audio (24 diễn viên, 8 cảm xúc)
- **Số mẫu**: 1.440 file audio `.wav`
- **Các cảm xúc**: neutral, calm, happy, sad, angry, fearful, disgust, surprised
- **Mục tiêu**: Phân tích dữ liệu + xây dựng mô hình phân loại cảm xúc từ tín hiệu giọng nói

## Cấu trúc dự án
Speech-Emotion-Recognition/
├── notebooks/
│   └── speech_emotion_recognition.ipynb   # Notebook chính (EDA + modeling)
├── docs/
│   └── DataMining.pdf                     # Báo cáo môn Data Mining
├── requirements.txt
└── README.md

## Dataset

**RAVDESS** (Ryerson Audio-Visual Database of Emotional Speech and Song)

- 24 diễn viên (12 nam, 12 nữ)
- 8 loại cảm xúc:
  - `01` → neutral
  - `02` → calm
  - `03` → happy
  - `04` → sad
  - `05` → angry
  - `06` → fearful
  - `07` → disgust
  - `08` → surprised

Phân bố cảm xúc gần như cân bằng (mỗi cảm xúc ~192 mẫu, trừ neutral = 96).

## Cách chạy

1. Clone repository:
```bash
git clone https://github.com/TBang1911/Speech-Emotion-Recognition.git
cd Speech-Emotion-Recognition
```
2. Cài đặt thư viện:
```bash
pip install -r requirements.txt
```
3.Mở notebook:
```bash
jupyter notebook notebooks/speech_emotion_recognition.ipynb
```
Lưu ý: Notebook được phát triển trên Kaggle. Nếu chạy local, cần tải dataset RAVDESS và điều chỉnh đường dẫn data_dir

Tác giả:
Thái Minh Khang
Email: tkol.3975@gmail.com
GitHub: TBang1911
