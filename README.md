# DDoS Attack Detection using Machine Learning

## 📌 Giới thiệu

Đây là project thực nghiệm phát hiện tấn công từ chối dịch vụ phân tán (**DDoS**) trên dữ liệu mạng bằng các thuật toán học máy: **Decision Tree, Random Forest, KMeans Clustering**.

Project thực hiện cho bài tập lớn môn học, với mục tiêu:
- Nâng cao kỹ năng phân tích, xử lý dữ liệu mạng
- Ứng dụng, so sánh các thuật toán Machine Learning trong thực tế an ninh mạng

## 🗂 Cấu trúc thư mục

ML/
├── Decision Tree.ipynb
├── RandomForest.ipynb
├── Kmeans.ipynb
├── LSTM.ipynb
├── Train.csv
├── Test.csv
└── README.md


- `Decision Tree.ipynb`, `RandomForest.ipynb`, `Kmeans.ipynb`: Notebook triển khai và đánh giá các mô hình ML
- `LSTM.ipynb`: Notebook thử nghiệm với mô hình học sâu (nếu có)
- `Train.csv`, `Test.csv`: Dữ liệu huấn luyện và kiểm thử (dữ liệu mẫu/minh họa, không phải dữ liệu thật đầy đủ)
- `README.md`: File giới thiệu này

## ⚡️ Yêu cầu môi trường

- Python 3.8+
- Các thư viện: pandas, numpy, scikit-learn, matplotlib, seaborn

Cài nhanh qua pip:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn

🚀 Hướng dẫn chạy thử

1/ Clone repository về máy:
git clone https://github.com/ten-user/ten-repo.git
cd ten-repo
2/ Mở các file notebook (.ipynb) bằng Jupyter Notebook hoặc Visual Studio Code

Thực hiện từng cell theo hướng dẫn trong notebook

3/Kết quả đầu ra:

Đánh giá mô hình qua các chỉ số: Accuracy, Precision, Recall, F1-score

Trực quan hóa kết quả bằng confusion matrix

Thành viên thực hiện
Đặng Hiển Danh

Trần Văn Nhật
