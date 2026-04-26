# FOOTBALL PLAYER POSITION CLASSIFIER AND O3 SOFT SENSOR
Ứng dụng kiến thức được học trong môn Máy học để xây dựng 2 mô hình máy học: Phân loại cầu thủ bóng đá theo vị trí trên sân và mô phỏng cảm biến dự đoán nồng độ khí Ozone (O3).

## Cấu trúc thư mục
├── data/                # Chứa file csv dữ liệu thô và đã xử lý<br>
├── models/             # Chứa file .joblib đã xuất<br>
├── notebooks/          # Chứa các file .ipynb để huấn luyện và phân tích<br>
└── README.md           # File hướng dẫn này

## Trình bày bài toán và các hướng giải quyết
- Bài toán 1: Dựa vào các con số thống kê thi đấu trên sân của một cầu thủ (số lần sút, chuyền, xoạc bóng...), hãy xây dựng mô hình để máy tính tự động đoán xem cầu thủ đó đá ở vị trí nào (Hậu vệ - DF, Tiền vệ - MF, hay Tiền đạo - FW).
- Bài toán 2: Xây dựng và huấn luyện các mô hình Máy học để dự đoán nồng độ O₃.
- Thư viện được sử dụng: Pandas, Seaborn, Matplotlib, Scikit-learn, Joblib.
- Thuật toán học máy sử dụng: Linear Regression, Logistic Regresstion, Random Forest.
- Chi tiết quá trình thực hiện có trong file báo cáo nộp cùng thư mục này.

## Thành viên nhóm làm bài
- Trần Hoàn Đượm, MSSV: 3124580012
- Dương Phúc, MSSV: 3124580056

## Giấy phép dataset
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)