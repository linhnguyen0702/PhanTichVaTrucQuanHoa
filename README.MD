# 📊 PHÂN TÍCH VÀ TRỰC QUAN HÓA DỮ LIỆU BÁN HÀNG ĐIỆN TỬ

## 🎯 Tổng Quan Dự Án

### 1. Giới Thiệu

Dự án này thực hiện **phân tích toàn diện dữ liệu bán hàng điện tử** nhằm khám phá các xu hướng kinh doanh, hiểu rõ hành vi khách hàng, và đưa ra các khuyến nghị chiến lược dựa trên dữ liệu để tối ưu hóa doanh thu và hiệu quả hoạt động.

Thông qua việc áp dụng các kỹ thuật **phân tích dữ liệu (Data Analysis)** và **trực quan hóa dữ liệu (Data Visualization)**, dự án cung cấp cái nhìn sâu sắc về:

- Hiệu suất kinh doanh tổng thể
- Xu hướng bán hàng theo thời gian
- Phân khúc và hành vi khách hàng
- Hiệu quả của từng sản phẩm và vùng địa lý

---

## 🎓 Mục Tiêu Dự Án

### Mục tiêu chính:

1. **Phân tích Hiệu suất Kinh doanh**: Đánh giá tổng quan về doanh thu, đơn hàng, và khách hàng
2. **Phân tích Xu hướng**: Xác định các mô hình theo thời gian (tháng, quý, ngày trong tuần)
3. **Phân khúc Khách hàng**: Sử dụng RFM Analysis để phân loại khách hàng
4. **Tối ưu Sản phẩm**: Xác định sản phẩm bestseller và cơ hội tăng trưởng
5. **Insights Chiến lược**: Đưa ra khuyến nghị dựa trên dữ liệu để cải thiện doanh thu

### Mục tiêu học tập:

- Áp dụng kỹ thuật **EDA (Exploratory Data Analysis)** đầy đủ
- Thực hành **Data Cleaning** và **Data Preparation**
- Sử dụng đa dạng kỹ thuật **trực quan hóa dữ liệu**
- Thực hiện **Statistical Testing** để kiểm định giả thuyết
- Phân tích nâng cao: **RFM**, **Cohort Analysis**, **Correlation Analysis**

---

## 📚 Phạm Vi Phân Tích

### Dữ liệu phân tích bao gồm:

| Khía cạnh      | Nội dung                                                        |
| -------------- | --------------------------------------------------------------- |
| **Thời gian**  | Dữ liệu bán hàng trong năm 2025 (12 tháng)                      |
| **Sản phẩm**   | 10 danh mục sản phẩm điện tử (Laptop, Smartphone, Tablet, v.v.) |
| **Khách hàng** | ~1000 khách hàng với thông tin nhân khẩu học                    |
| **Địa lý**     | 3 vùng chính: Miền Bắc, Miền Trung, Miền Nam                    |
| **Giao dịch**  | ~5000 đơn hàng với thông tin chi tiết                           |

### Các biến phân tích:

- **order_id**: Mã đơn hàng
- **customer_id**: Mã khách hàng
- **order_date**: Ngày đặt hàng
- **product_name**: Tên sản phẩm
- **quantity**: Số lượng
- **price**: Đơn giá
- **total**: Tổng giá trị đơn hàng
- **customer_age**: Tuổi khách hàng
- **region**: Vùng địa lý

---

## 🔬 Phương Pháp Phân Tích

### 1. Phân tích Khám phá Dữ liệu (EDA)

- **Thống kê mô tả**: Mean, Median, Mode, Std, Min, Max
- **Phân tích phân phối**: Histogram, KDE, Box plot
- **Phát hiện Outliers**: IQR method
- **Xử lý Missing Values**: Imputation strategies

### 2. Phân tích Xu hướng Thời gian

- **Time Series Analysis**: Doanh thu theo tháng/quý/năm
- **Seasonality Detection**: Xác định mùa vụ
- **Trend Analysis**: Moving Average, Growth Rate
- **Pattern Recognition**: Ngày trong tuần, giờ cao điểm

### 3. Phân tích Khách hàng

- **RFM Analysis**: Recency - Frequency - Monetary
- **Customer Segmentation**: Champions, Loyal, At Risk, Lost
- **Cohort Analysis**: Retention Rate, Churn Rate
- **Demographic Analysis**: Phân tích theo tuổi, vùng

### 4. Phân tích Sản phẩm

- **Product Performance**: Doanh thu, số lượng bán, AOV
- **Pareto Analysis**: Quy tắc 80/20
- **Cross-selling Analysis**: Sản phẩm thường được mua cùng
- **Product Lifecycle**: Sản phẩm tăng/giảm trưởng

### 5. Phân tích Tương quan

- **Correlation Matrix**: Hệ số tương quan Pearson
- **Feature Relationships**: Scatter plots, Pair plots
- **Heatmap Analysis**: Phát hiện mối quan hệ ẩn

### 6. Kiểm định Thống kê

- **ANOVA Test**: So sánh doanh thu giữa các vùng
- **Chi-Square Test**: Mối liên hệ giữa biến phân loại
- **T-Test**: So sánh trung bình giữa hai nhóm
- **Pearson Correlation**: Kiểm định tương quan

---

## 📊 Công Cụ và Thư Viện

### Ngôn ngữ lập trình:

- **Python 3.x**

### Thư viện chính:

#### Data Processing:

- `pandas` - Xử lý và phân tích dữ liệu
- `numpy` - Tính toán số học

#### Visualization:

- `matplotlib` - Trực quan hóa cơ bản
- `seaborn` - Statistical visualization
- `plotly` - Interactive dashboards

#### Statistical Analysis:

- `scipy` - Statistical testing
- `statsmodels` - Advanced statistics

---

## 🎨 Các Loại Trực Quan Hóa Sử Dụng

### 1. Biểu đồ Cơ bản

- **Bar Chart**: So sánh giá trị giữa các nhóm
- **Line Chart**: Xu hướng theo thời gian
- **Pie Chart**: Tỷ lệ phần trăm
- **Histogram**: Phân phối dữ liệu

### 2. Biểu đồ Thống kê

- **Box Plot**: Phát hiện outliers và phân phối
- **Violin Plot**: Kết hợp box plot và KDE
- **Scatter Plot**: Mối quan hệ giữa 2 biến
- **Heatmap**: Ma trận tương quan

### 3. Biểu đồ Nâng cao

- **Pareto Chart**: Phân tích 80/20
- **Sankey Diagram**: Customer journey flow
- **Sunburst Chart**: Dữ liệu phân cấp
- **Cohort Heatmap**: Retention analysis
- **Bubble Chart**: 3 chiều dữ liệu

### 4. Dashboard Tương tác

- **Plotly Interactive Charts**: Zoom, hover, filter
- **Multiple Subplots**: So sánh đa chiều
- **Dynamic Updates**: Real-time analysis

---

## 📈 Kết Quả Mong Đợi

### 1. Insights Kinh doanh

- Xác định sản phẩm và kênh bán hàng hiệu quả nhất
- Phát hiện xu hướng mùa vụ và cơ hội tăng trưởng
- Hiểu rõ hành vi và nhu cầu khách hàng

### 2. Khuyến nghị Chiến lược

- Tối ưu hóa danh mục sản phẩm
- Cải thiện chiến lược marketing theo phân khúc
- Tăng cường customer retention
- Mở rộng thị trường tiềm năng

### 3. Báo cáo Trực quan

- Dashboard tương tác đầy đủ
- Báo cáo phân tích chi tiết
- Export files CSV cho các stakeholders

---

## 🏆 Đóng Góp Học Thuật

### Kỹ năng được phát triển:

#### 1. Data Analysis

- ✅ Data cleaning và preprocessing
- ✅ Exploratory Data Analysis (EDA)
- ✅ Statistical analysis và hypothesis testing
- ✅ Time series analysis
- ✅ Customer segmentation (RFM, Cohort)

#### 2. Data Visualization

- ✅ Matplotlib, Seaborn mastery
- ✅ Interactive visualization với Plotly
- ✅ Dashboard design principles
- ✅ Storytelling with data
- ✅ Advanced chart types

#### 3. Business Intelligence

- ✅ KPI definition và tracking
- ✅ Business metrics analysis
- ✅ Strategic recommendations
- ✅ Data-driven decision making

#### 4. Technical Skills

- ✅ Python programming
- ✅ Jupyter Notebook workflow
- ✅ Git version control
- ✅ Documentation best practices

---

## 📁 Cấu Trúc Dự Án

```
PhanTichVaTrucQuanHoa/
│
├── README.MD                          # Tài liệu tổng quan (this file)
├── data/                              # Dữ liệu đầu vào (raw CSVs)
│   └── sales_data.csv                 # Dữ liệu mẫu / nguồn
├── src/                               # Notebook chính, mã nguồn và thư mục sinh ra trong quá trình chạy
│   ├── TrucQuanHoaDuLieuBanHangDienTu.ipynb  # Jupyter Notebook chính (chạy từ đây)
│   ├── outputs/                        # Generated reports (CSV/XLSX) - tạo khi export
│   │   ├── summary_report.csv
│   │   ├── product_analysis.csv
│   │   ├── rfm_analysis.csv
│   │   ├── customer_segments.csv
│   │   └── monthly_revenue.csv
│   │
│   └── visualizations/                # Generated figures & interactive HTML exports
│       ├── time_trends.png
│       ├── customer_segments.png
│       ├── product_analysis.png
│       └── dashboard.html
│
├── .gitignore                         # Recommended
---

## 🚀 Hướng Dẫn Sử Dụng

### Bước 1: Cài đặt thư viện

```bash
pip install pandas numpy matplotlib seaborn plotly scipy
```

### Bước 2: Chuẩn bị dữ liệu

- Đặt file CSV vào thư mục dự án
- Hoặc để code tự động tạo dữ liệu mẫu

### Bước 3: Chạy Notebook

```bash
# Mở notebook chính (trong thư mục `src`)
jupyter notebook src/TrucQuanHoaDuLieuBanHangDienTu.ipynb
```

### Bước 4: Chạy từng cell theo thứ tự

- Cell 1-2: Import và load data
- Cell 3: Data cleaning
- Cell 4-5: EDA
- Cell 6-9: Advanced analysis
- Cell 10-12: Visualization
- Cell 13-15: Insights và export

---

## 📊 Highlights - Những Điểm Nổi Bật

### 🎯 Phân tích Đa chiều

- Kết hợp 6+ phương pháp phân tích khác nhau
- Từ cơ bản đến nâng cao (EDA → RFM → Cohort)

### 📈 Trực quan hóa Phong phú

- 40+ biểu đồ với 10+ loại khác nhau
- Cả static (Matplotlib/Seaborn) và interactive (Plotly)

### 🔬 Statistical Rigor

- Không chỉ mô tả mà còn kiểm định thống kê
- ANOVA, Chi-Square, Correlation tests

### 💼 Business-Oriented

- Không chỉ phân tích mà còn đưa ra insights
- Khuyến nghị cụ thể, có thể hành động được

### 📚 Educational Value

- Code được comment chi tiết
- Giải thích từng bước phân tích
- Phù hợp cho học tập và tham khảo

---

## 🎓 Ứng Dụng Thực Tế

Dự án này có thể được áp dụng cho:

1. **E-commerce platforms**: Shopee, Lazada, Tiki
2. **Retail businesses**: Cửa hàng điện tử, siêu thị
3. **Marketing agencies**: Phân tích hiệu quả chiến dịch
4. **Product teams**: Tối ưu hóa product mix
5. **Business analysts**: Báo cáo định kỳ cho management

---

## 📝 Tài Liệu Tham Khảo

### Sách:

- "Python for Data Analysis" - Wes McKinney
- "Storytelling with Data" - Cole Nussbaumer Knaflic
- "Data Science for Business" - Foster Provost & Tom Fawcett

### Online Resources:

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Plotly Documentation](https://plotly.com/python/)
- [Seaborn Tutorial](https://seaborn.pydata.org/tutorial.html)

### Papers:

- Customer Segmentation using RFM Analysis
- Cohort Analysis for Retention Metrics
- Time Series Analysis in Retail

---

## 👨‍💻 Tác Giả & Đóng Góp

**Tên dự án**: Phân Tích và Trực Quan Hóa Dữ Liệu Bán Hàng  
**Môn học**: Phân Tích và Trực Quan Hóa Dữ Liệu  
**Năm học**: 2024-2025

### Đóng góp:

Mọi đóng góp, góp ý để cải thiện dự án đều được hoan nghênh!

---

## 📄 License

Dự án này được phát hành dưới MIT License - xem file LICENSE để biết thêm chi tiết.

---

## 🌟 Kết Luận

Dự án **Phân Tích và Trực Quan Hóa Dữ Liệu Bán Hàng** là một ví dụ điển hình về việc áp dụng khoa học dữ liệu vào giải quyết các vấn đề kinh doanh thực tế. Thông qua việc kết hợp:

- ✅ **Phân tích dữ liệu chuyên sâu** (EDA, RFM, Cohort, Statistical Testing)
- ✅ **Trực quan hóa đa dạng và chuyên nghiệp** (40+ biểu đồ, Interactive dashboards)
- ✅ **Business insights có giá trị** (Khuyến nghị chiến lược cụ thể)

Dự án không chỉ đáp ứng yêu cầu môn học mà còn có thể áp dụng trực tiếp vào thực tế kinh doanh, giúp doanh nghiệp đưa ra quyết định dựa trên dữ liệu (data-driven decisions).

---

**📧 Liên hệ**: linhyang0702@gmail.com
**🔗 GitHub**: [Link repository của bạn]  
**📅 Ngày cập nhật**: Tháng 11, 2025
