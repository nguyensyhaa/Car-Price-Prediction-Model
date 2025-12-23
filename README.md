# Car Price Prediction Model 🚗

## 📌 Tổng quan (Overview)
Xây dựng mô hình Machine Learning (Hồi quy) để dự đoán giá xe ô tô dựa trên các thông số kỹ thuật. Dự án giúp định hình chiến lược giá cho hãng Geely Auto khi thâm nhập thị trường Mỹ và Châu Âu.

## 📂 Dữ liệu (Dataset)
* **Biến mục tiêu (Target):** Price (Giá xe).
* **Biến đặc trưng (Features):** Kích thước xe, trọng lượng, mã lực, hãng xe, loại nhiên liệu, v.v.

## 🛠 Công nghệ sử dụng (Tech Stack)
* **Python:** Scikit-Learn, Pandas, NumPy.
* **Model:** Linear Regression, Random Forest Regressor.
* **Technique:** Feature Selection (RFE), Hyperparameter Tuning (GridSearchCV).

## 🔍 Quy trình thực hiện (Process)
1. **Tiền xử lý:** Xử lý biến phân loại (Dummy encoding), chuẩn hóa dữ liệu số (Scaling).
2. **Feature Engineering:** Chọn lọc các biến quan trọng ảnh hưởng nhất đến giá.
3. **Modeling:** Huấn luyện và so sánh nhiều thuật toán hồi quy khác nhau.
4. **Evaluation:** Đánh giá mô hình bằng $R^2$ Score và RMSE.

