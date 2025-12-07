# BTL_XSTK – Bài tập lớn Xác suất Thống kê

Repository này chứa notebook **BTL_XSTK.ipynb**, được viết bằng **R trong Jupyter Notebook**, thực hiện các phân tích thống kê cơ bản đến nâng cao.  
Nội dung được chia thành các phần rõ ràng theo từng loại kiểm định và mô hình phân tích.

## 📌 Nội dung chính

### 1. Import thư viện và dữ liệu
Notebook bắt đầu bằng việc:
- Nạp các thư viện R cần thiết: `readr`, `car`, `ggplot2`, ...  
- Đọc dữ liệu đầu vào phục vụ cho các bài kiểm định.

---

### 2. Kiểm định 1 mẫu
Thực hiện các phép kiểm định cơ bản với một mẫu:
- Kiểm định trung bình 1 mẫu (One-sample t-test)
- Các bước:
  - Kiểm tra điều kiện
  - Thiết lập giả thuyết `H0`, `H1`
  - Tính thống kê kiểm định
  - Kết luận theo p-value

---

### 3. Kiểm định 2 mẫu
Thực hiện kiểm định so sánh giữa hai mẫu độc lập hoặc ghép đôi:
- Independent 2-sample t-test
- Paired t-test
- Kiểm định phương sai nếu cần (`var.test`)
- Diễn giải kết quả và kết luận

---

### 4. Kiểm định ANOVA
Phần này tiến hành:
- Phân tích phương sai 1 yếu tố (One-way ANOVA)
- Kiểm tra:
  - Tính độc lập
  - Phân phối chuẩn
  - Đồng nhất phương sai (Levene test – từ `car`)
- Thực hiện post-hoc (TukeyHSD) nếu ANOVA có ý nghĩa

---

### 5. Hồi quy đa biến (Multiple Linear Regression)
Bao gồm:
- Xây dựng mô hình hồi quy tuyến tính nhiều biến
- Ước lượng hệ số và kiểm định ý nghĩa
- Kiểm tra giả định:
  - Phương sai không đổi
  - Phân phối chuẩn của residuals
  - Đa cộng tuyến (VIF)
- Đánh giá mô hình bằng R², Adjusted R²

---

## 🛠 Công nghệ sử dụng
- **R**
- **Jupyter Notebook (.ipynb)**
- Các thư viện thống kê:
  - `readr`
  - `car`
  - `ggplot2`
  - `stats`
  - Khác tuỳ theo từng đoạn mã

---

## 📂 Cách chạy notebook
1. Cài Jupyter Notebook có hỗ trợ R kernel  
2. Mở file `BTL_XSTK.ipynb`  
3. Chạy lần lượt từng cell theo thứ tự  
4. Đảm bảo dữ liệu đầu vào nằm đúng đường dẫn được dùng trong notebook

---

## 📄 Mục đích
Notebook được xây dựng để minh họa các kỹ thuật thống kê thường gặp trong môn  
**Xác suất – Thống kê**, bao gồm các kiểm định giả thuyết và mô hình hồi quy.  
Thích hợp cho:
- Sinh viên
- Người học thống kê cơ bản
- Tự học hoặc tham khảo khi làm bài tập lớn

---

## 👤 Tác giả
Bài làm thuộc bài tập lớn môn Xác suất Thống kê.  
Bạn có thể thêm tên nhóm, lớp, giảng viên nếu muốn.

---
