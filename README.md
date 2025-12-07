# BTL_XSTK – Bài tập lớn Xác suất Thống kê

Repository này chứa notebook **BTL_XSTK.ipynb**, được viết bằng **R trong Jupyter Notebook**, thực hiện các phân tích thống kê cơ bản đến nâng cao.  
Nội dung được chia thành các phần rõ ràng theo từng loại kiểm định và mô hình phân tích.

---

## 📦 Dataset

Toàn bộ phân tích trong notebook sử dụng dữ liệu từ:  

👉 [Transactional Retail Dataset of Electronics Store (dirty_data.csv) — Kaggle]  
(https://www.kaggle.com/datasets/muhammadshahrayar/transactional-retail-dataset-of-electronics-store?select=dirty_data.csv)  

Dataset được sử dụng trong:
- Kiểm định 1 mẫu  
- Kiểm định 2 mẫu  
- ANOVA  
- Hồi quy đa biến  

Bạn hãy đảm bảo rằng file `dirty_data.csv` được tải xuống và đặt đúng đường dẫn mà notebook sử dụng — hoặc sửa lại đường dẫn trong lệnh `read_csv()` / `read.table()` cho đúng.

---

## 📌 Nội dung chính

### 1. Import thư viện và dữ liệu
Notebook bắt đầu bằng việc:
- Nạp các thư viện R: `readr`, `car`, `ggplot2`, …
- Đọc dữ liệu đầu vào từ file CSV  

---

### 2. Kiểm định 1 mẫu
Thực hiện các phép kiểm định 1 mẫu:
- One-sample t-test  
- Thiết lập giả thuyết  
- Tính thống kê kiểm định  
- Kết luận theo p-value  

---

### 3. Kiểm định 2 mẫu
Bao gồm:
- Independent 2-sample t-test  
- Paired t-test (nếu dữ liệu phù hợp)  
- Kiểm định phương sai (var.test) khi cần  
- Diễn giải kết quả  

---

### 4. Kiểm định ANOVA
Thực hiện:
- One-way ANOVA  
- Kiểm tra các giả định:
  - Phân phối chuẩn
  - Đồng nhất phương sai (Levene test – từ thư viện `car`)
- Nếu ANOVA có ý nghĩa → tiến hành Post-hoc (TukeyHSD)  

---

### 5. Hồi quy đa biến
Phân tích:
- Xây dựng mô hình hồi quy tuyến tính nhiều biến  
- Ước lượng hệ số, kiểm định ý nghĩa  
- Kiểm tra giả định mô hình:
  - Residuals (phân phối chuẩn, homoscedasticity)
  - Đa cộng tuyến (VIF)  
- Đánh giá mô hình bằng R² / Adjusted R²  

---

## 🛠 Công nghệ sử dụng
- **R**  
- **Jupyter Notebook**  
- Các thư viện:
  - `readr`
  - `car`
  - `ggplot2`
  - `stats`  

---

## 📂 Cách chạy notebook
1. Tải file `dirty_data.csv` từ Kaggle link ở trên.  
2. Đặt file đúng trong thư mục mà notebook trông tới hoặc adjust lại đường dẫn trong lệnh đọc dữ liệu.  
3. Cài đặt R kernel cho Jupyter (nếu chưa có).  
4. Mở file `BTL_XSTK.ipynb` và chạy tuần tự các cell.  

---
