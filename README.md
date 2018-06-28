# Ứng Dụng Machine Learning
## Dự đoán khả năng trả nợ của người vay

## Vấn đề
Dựa vào thông tin chung và lịch sử tín dụng của khách hàng để dự đoán khả năng trả nợ của một khoản vay trong tương lai.

## Data
Dữ liệu được tải từ [Lending Club Public Data](https://www.lendingclub.com/info/download-data.action). Mình sẽ sử dụng dữ liệu LOAN data từ 2007-2011 vì đa phần các khoản cho vay trong thời gian này đã có kết quả (thu hồi được hay bị mất), để sử dụng cho mô hình machine learning. Mình để dữ liệu trong thư mục /data/.

## Thực hiện
Dùng mô hình CRISP-DM (Data Science Project Life Cycle) làm framework giải quyết bài toán này. Mô hình này gồm các bước sau:

1. Business Understanding
    - dùng kiến thức về tài chính xác định xem yếu tố nào có thể ảnh hưởng đến khả năng trả nợ.
2. Data Understanding
    - có đủ data để train mô hình machine learning hay chưa?
    - 
3. Data Preparation
    - xác định feature (column) nào cần loại bỏ và giữ lại
    - chuyển tất cả các features thành số (integer hoặc float)
4. Modeling
    - dùng supervised machine learning algorithms để mo hình hóa dữ liệu đã xử lý.
5. Evaluation
    - đánh giá xem kết quả dự đoán của machine learning model có đạt được những metrics (thước đo) mong muốn hay không.
6. Deployment
    - cần kết hợp kết quả dự đoán của machine learning model vào quy trình kinh doanh như thế nào?
    -
7. Monitoring
    - theo dõi kết quả dự đoán thực tiễn của mô hình để có thể retrain kip thời trong trường hợp có những khoản vay mới làm giảm thước đo chuẩn của mô hình.


