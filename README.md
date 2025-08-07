Language: 🇻🇳 \
Dataset : [fetch_california_housing](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html)

## California Housing - Data Analysis & Modeling

###  Mô tả

Notebook này thực hiện phân tích dữ liệu và xây dựng mô hình dự đoán giá nhà (biến `PRICE`) dựa trên tập dữ liệu California Housing. Tập dữ liệu này chứa thông tin về các đặc điểm khu dân cư ở California như:

* Median Income (`MedInc`)
* House Age (`HouseAge`)
* Average Rooms (`AveRooms`)
* Average Bedrooms (`AveBedrms`)
* Population, Households, Latitude, Longitude, v.v.

### Các bước thực hiện

1. **Tiền xử lý dữ liệu**

   * Kiểm tra null, kiểu dữ liệu
   * Tạo biến mới (ví dụ: tỷ lệ phòng ngủ / số phòng)
   * Sắp xếp lại thứ tự cột

2. **Phân tích tương quan**

   * Tính ma trận tương quan với `PRICE`
   * Chọn ra 5 biến có tương quan mạnh nhất để mô hình hóa

3. **Trực quan hóa**

   * Vẽ biểu đồ histogram cho các biến liên quan
   * Trực quan tương quan bằng heatmap

4. **Xây dựng mô hình học máy**

   * Chia tập train/test
   * Huấn luyện và đánh giá các mô hình:

     * Linear Regression
     * Lasso/Ridge Regression

5. **Đánh giá mô hình**

   * So sánh các mô hình theo các chỉ số:

     * RMSE
     * MAE
     * R² score
   * Trình bày kết quả dưới dạng bảng

###  Mục tiêu
> Ứng dụng các kỹ thuật thống kê, để tìm được biến nào quan trọng nhất trong việc chi phối giá nhà tại cali.
> Ứng dụng học máy cơ bản để hiểu được phần trăm (%) có thể giải thích được của mô hình hồi quy tuyến tính tại giá nhà.

 
