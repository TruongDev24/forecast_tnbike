# 90-Day Revenue Forecasting - Data Explorers 2026

Dự án này là giải pháp dự báo doanh thu 90 ngày tới cho Công ty Xe đạp Thống Nhất, sử dụng mô hình ARIMA. Dự án được thực hiện trong khuôn khổ cuộc thi Data Explorers 2026 với mục tiêu tối ưu hóa chuỗi cung ứng và lập kế hoạch kinh doanh dựa trên dữ liệu.

## 🚀 Mục tiêu dự án
* **Dự báo:** Cung cấp số liệu dự báo doanh thu 90 ngày cho 5 nhóm sản phẩm chiến lược.
* **Tối ưu hóa:** Hỗ trợ bộ phận kinh doanh lập kế hoạch tồn kho (Inventory Planning) và chiến lược marketing (Marketing Campaign).
* **Trực quan hóa:** Xây dựng quy trình xử lý dữ liệu tự động, sẵn sàng tích hợp với các Dashboard (Power BI/Tableau/Shiny).

## 🛠 Công nghệ & Công cụ
- **Ngôn ngữ:** Python
- **Xử lý dữ liệu:** Pandas, NumPy
- **Mô hình dự báo:** Statsmodels (ARIMA), pmdarima
- **Trực quan hóa:** Matplotlib, Seaborn
- **Môi trường:** Jupyter Notebook, Google Colab

## 📋 Quy trình thực hiện (8 Bước chuẩn mực)
Chúng tôi tuân thủ quy trình khoa học dữ liệu chặt chẽ để đảm bảo độ tin cậy của mô hình:
1. **ETL:** Làm sạch và xử lý dữ liệu thô.
2. **EDA:** Khám phá xu hướng và biến động.
3. **Phân rã (Decomposition):** Tách biệt xu hướng, mùa vụ và nhiễu.
4. **Kiểm định (ADF Test):** Kiểm tra tính dừng của dữ liệu.
5. **ACF/PACF:** Chọn tham số tối ưu cho mô hình.
6. **Validation:** Đánh giá hiệu suất trên tập Test (RMSE, MAPE).
7. **Forecasting:** Dự báo Quý 2/2026 kèm dải tin cậy 95%.
8. **Deployment:** Xuất dữ liệu sạch sang CSV phục vụ Dashboard.

## 📥 Cài đặt & Sử dụng
1. Clone repository này về máy:
   ```bash
   git clone https://github.com/TruongDev24/forecast_tnbike.git

2. Cài đặt các thư viện phụ thuộc:
   ```bash
   pip install pmdarima scikit-learn statsmodels pandas matplotlib seaborn

3. Mở file revenue_forecast.ipynb trên Jupyter Notebook hoặc Google Colab và chọn "Run All".

📊 Kết quả đạt được
Mô hình ARIMA đạt độ chính xác cao với MAPE trung bình dưới [điền số %]%.

File dự báo chuẩn hóa Q2_2026_Revenue_Forecast.csv được tự động xuất ra sau khi chạy mô hình.

Các biểu đồ Heatmap mùa vụ giúp xác định đúng thời điểm "vàng" để đẩy mạnh doanh thu.

💡 Nhận định kinh doanh (Business Insights)
Dựa trên kết quả dự báo, chúng tôi khuyến nghị:

Chiến lược tồn kho: Tăng tồn kho cho các nhóm hàng có xu hướng tăng trưởng ổn định (dựa trên dải tin cậy Upper Bound).

Chiến lược Marketing: Tận dụng dữ liệu mùa vụ để triển khai chiến dịch trước 30 ngày so với thời điểm tăng trưởng dự báo.

Dự án thuộc cuộc thi Data Explorers 2026 - Công ty Xe đạp Thống Nhất.
