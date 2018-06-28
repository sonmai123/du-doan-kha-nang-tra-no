# Ứng Dụng Machine Learning
## Dự đoán khả năng trả nợ của người vay

## Vấn đề
Dựa vào thông tin chung và lịch sử tín dụng của khách hàng để dự đoán khả năng trả nợ của một khoản vay trong tương lai.

## Thực hiện
Dùng mô hình CRISP-DM (Data Science Project Life Cycle) làm framework giải quyết bài toán này. Mô hình này gồm các bước sau:

1. Business Understanding
    - 
2. Data Understanding
    - có đủ data để train mô hình machine learning hay chưa?
    - 
3. Data Preparation
    - xác định feature (column) nào cần loại bỏ và giữ lại
    - chuyển tất cả các features thành số (integer hoặc float)
4. Modeling
    - 
5. Evaluation
    - 
6. Deployment
7. Monitoring

Dữ liệu được tải từ [Lending Club Public Data](https://www.lendingclub.com/info/download-data.action). Mình sẽ sử dụng dữ liệu LOAN data từ 2007-2011 vì đa phần các khoản cho vay trong thời gian này đã có kết quả (thu hồi được hay bị mất), để sử dụng cho mô hình machine learning. Mình để dữ liệu trong thư mục /data/.

### 1.Business Understanding
Đây là giai đoạn hiểu về vấn đề kinh doanh.

Câu hỏi chính: Có thể dự đoán được khả năng trả nợ của khoản vay từ những dữ liệu đã có hay không?

### 2.Data Understanding
Đây là giai đoạn hiểu về dữ liệu.

## 3.Data Preparation
Đây là giai đoạn xử lý dữ liệu để chuẩn bị cho mô hình machine learning.

Đa phần các mô hình machine learning yêu cầu dữ liệu đầu vào phải là số (integer hoặc float).

### 4.Modeling
Đây là bước lựa mô hình machine learning thích hợp để mô hình hóa (modeling) dữ liệu.

### 5.Evaluation

### 6.Deployment
Đây là giai đoạn đưa mô hình machine learning vào sử dụng thật. 

Tức là, dùng những dự đoán của mô hình để đưa ra những quyết định cho vay.

Câu hỏi:
Kết quả dự đoán của mô hình cần được kết hợp với các quy trình ra quyết định trong doanh nghiệp như thế nào?

### 7.Monitoring
Đây là giai đoạn theo dõi khả năng dự đoán của mô hình.

Bạn sẽ theo dõi xem accuracy của mô hình có giảm xuống hay không. Nếu có, nghĩa là có những loại khoản vay mới mà mô hình chưa được học nên có những dự đoán không chính xác. Bạn cần có một tính chính xác tối thiểu mà qua đó bạn sẽ quyết định retrain model. 
Ví dụ, mô hình của bạn có accuracy trên test set là 70%, qua quá trình sử dụng 6 tháng mức accuracy giảm xuống còn 59% và mức tối thiểu chấp nhận được là 60%, thì đây là lúc quyết định retrain model với những khoản vay mới để nâng mức accuracy lên lại.

