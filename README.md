# BTL_XSTK – Bài tập lớn Xác suất Thống kê

Repository này chứa notebook **BTL_XSTK.ipynb**, được viết bằng **R trong Jupyter Notebook**, thực hiện các phân tích thống kê cơ bản đến nâng cao.  
Nội dung được chia thành các phần rõ ràng theo từng loại kiểm định và mô hình phân tích.

---

## 📦 Dataset

Toàn bộ phân tích trong notebook sử dụng dữ liệu từ:  

👉 [Transactional Retail Dataset of Electronics Store (dirty_data.csv) — Kaggle]  
[dirty_data.csv – Kaggle](https://www.kaggle.com/datasets/muhammadshahrayar/transactional-retail-dataset-of-electronics-store?select=dirty_data.csv)

Dataset được dùng trong:
- Thống kê mô tả  
- Kiểm định 1 mẫu  
- Kiểm định 2 mẫu  
- ANOVA  
- Hồi quy đa biến  

Hãy đảm bảo file `dirty_data.csv` được tải xuống và đặt đúng đường dẫn mà notebook sử dụng.

---

## 📌 Nội dung chính

### 1. Import thư viện và dữ liệu
Notebook bắt đầu bằng:
- Nạp các thư viện R: `readr`, `car`, `ggplot2`, …
- Đọc dữ liệu từ file CSV

---

### 2. Thống kê mô tả (Descriptive Statistics)
Phần thống kê mô tả được thực hiện đầu tiên nhằm hiểu tổng quan dữ liệu:

Bao gồm:
- Tính các thống kê cơ bản:  
  - Mean  
  - Median  
  - Min – Max  
  - Variance, Std. Deviation  
- Tần suất (frequency) cho các biến phân loại  
- Quan sát dữ liệu thiếu, dữ liệu lỗi  
- Vẽ biểu đồ mô tả:  
  - Histogram  
  - Boxplot  
  - Bar chart  

Mục tiêu: nhận diện phân phối dữ liệu và phát hiện outliers hoặc bất thường trước khi tiến hành kiểm định.

---

### 3. Kiểm định 1 mẫu
Bao gồm:
- One-sample t-test  
- Thiết lập giả thuyết  
- Tính thống kê kiểm định  
- Kết luận theo p-value  

---

### 4. Kiểm định 2 mẫu
Bao gồm:
- Independent 2-sample t-test  
- Paired t-test  
- Kiểm định phương sai (var.test)  
- Diễn giải và kết luận  

---

### 5. Kiểm định ANOVA
Thực hiện:
- One-way ANOVA  
- Kiểm tra giả định:
  - Phân phối chuẩn  
  - Đồng nhất phương sai (Levene test – `car`)  
- Post-hoc (TukeyHSD)

---

### 6. Hồi quy đa biến
Phân tích:
- Xây dựng mô hình hồi quy tuyến tính nhiều biến  
- Kiểm định ý nghĩa hệ số  
- Kiểm tra giả định:
  - Residuals  
  - Homoscedasticity  
  - Đa cộng tuyến (VIF)  
- Đánh giá bằng R² / Adjusted R²  

---

## 🛠 Công nghệ sử dụng
- **R**
- **Jupyter Notebook**
- Thư viện:
  - `readr`
  - `car`
  - `ggplot2`
  - `stats`

---
