# 📊 Báo cáo nghiên cứu mô hình dự báo chuỗi thời gian trong ngành lưu trú

## 📌 Giới thiệu
Nghiên cứu đã tiến hành xây dựng và so sánh hai mô hình dự báo chuỗi thời gian phổ biến là **ARIMA** và **Prophet**, nhằm dự báo **tổng số khách hàng trong ngành kinh doanh lưu trú** dựa trên dữ liệu giai đoạn **2015 – 2017**.  

---

## 📖 Chương 1: Cơ sở lý thuyết
- Trình bày **tổng quan về thị trường kinh doanh lưu trú**.  
- Cung cấp các kiến thức toán học cơ bản trong **phân tích chuỗi thời gian**.  
- Làm nền tảng cho việc **xây dựng mô hình dự báo**.  

---

## ⚙️ Chương 2: Mô hình ARIMA và Prophet
### 🔹 ARIMA
- Khai thác cấu trúc **tự hồi quy** và **tính dừng** của dữ liệu.  
- Mạnh trong xử lý **tính tự tương quan**.  

### 🔹 Prophet
- Linh hoạt với **yếu tố mùa vụ** và **biến ngoại sinh** (ví dụ: ngày lễ).  
- Ưu điểm: **đơn giản, dễ sử dụng, hiệu quả** với dữ liệu có tính mùa vụ phức tạp.  

---

## 📊 Chương 3: Dữ liệu & Kết quả thực nghiệm
### 🧪 Kết quả mô hình
- **ARIMA(6,1,6)**  
  - MAE = **30.671**  
  - MAPE = **0.141**  

- **Prophet**  
  - MAE = **33.096**  
  - MAPE = **0.148**  

📌 **So sánh:**  
- Cả hai mô hình đều cho kết quả **tương đối chính xác**.  
- **ARIMA** phù hợp hơn khi dữ liệu có tính **tự tương quan mạnh**.  
- **Prophet** vượt trội hơn khi dữ liệu có **mùa vụ phức tạp** và **ngoại lai**.  

---

## ✅ Tổng kết & Hướng phát triển
- Nghiên cứu đã làm rõ:  
  - Các bước **xây dựng mô hình**  
  - Phương pháp **đánh giá kết quả**  
  - **So sánh ưu – nhược điểm** giữa ARIMA và Prophet  

- **Ứng dụng thực tế:**  
  - ARIMA → dữ liệu có tính tự tương quan.  
  - Prophet → dữ liệu có mùa vụ phức tạp & chịu ảnh hưởng từ yếu tố ngoại sinh.  

- **Hướng nghiên cứu tiếp theo:**  
  - Kết hợp mô hình (**Hybrid models**)  
  - Xử lý dữ liệu **phi tuyến**  
  - Bổ sung thêm **biến ngoại sinh** để tăng độ chính xác.  

---

✍️ *Nghiên cứu này là tiền đề cho việc áp dụng các mô hình dự báo nâng cao trong ngành lưu trú, hỗ trợ quản lý và hoạch định chiến lược hiệu quả hơn.*  
