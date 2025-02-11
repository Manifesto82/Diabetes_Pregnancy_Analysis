# Diabetes_Pregnancy_Analysis
# Mục tiêu
Mục tiêu của project là xây dựng một mô hình dự đoán tỉ lệ bị tiểu đường ở phụ sản dựa trên các thông tin lâm sàng và các yếu tố liên quan. Project sử dụng bộ dataset chứa thông tin của các phụ sản gồm nhiều thuộc tính độc lập và 1 thuộc tính phụ thuộc là Outcome(kết quả có bị tiểu đường hay không - 0 hoặc 1).
# Dữ liệu
Bộ dataset chứa các thông tin về Pregnancies (số lần mang thai), Glucose (Nồng độ glucose huyết tương sau 2 giờ trong xét nghiệm dung nạp glucose đường uống), BloodPressure (Huyết áp tâm trương (mm Hg)), SkinThickness (Độ dày nếp gấp da cơ tam đầu (mm)), Insulin (Insulin huyết thanh 2 giờ (mu U/ml)), BMI, DiabetesPedigree (Chức năng phả hệ bệnh tiểu đường), Age, Outcome (Kết quả bị tiểu đường, 1 - có, 0 - không)
# Tiền xử lý dữ liệu

Dữ liệu được đọc từ file CSV và kiểm tra các giá trị đặc biệt, trùng lặp.

Các bước tiền xử lý bao gồm:

Kiểm tra và xóa các giá trị trùng lặp.

Đếm số lượng giá trị riêng biệt trong từng cột.

Dữ liệu đã ở dạng số hóa nên không cần thêm bước chuyển đổi.
# Các thuật toán sử dụng

Logistic Regression:

Chia dữ liệu thành tập huấn luyện (70%) và tập kiểm tra (30%).

Huấn luyện mô hình và tính toán độ chính xác (accuracy).

Sử dụng Confusion Matrix và Classification Report để đánh giá hiệu suất mô hình.

K-Near Neighbors (KNN):

Sử dụng K-Neighbors và các tham số k ban đầu mặc định = 3 và thêm một k tối ưu (lấy k mang lại giá trị accuracy cũng như các chỉ số khác tối ưu nhất).

Huấn luyện mô hình và tính toán độ chính xác.

Đánh giá mô hình thông qua Confusion Matrix và Classification Report.
