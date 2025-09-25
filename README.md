

# 📊 Phân tích và Xử lý Dữ liệu với NumPy

[](https://www.python.org/downloads/)
[](https://numpy.org/)
[](https://jupyter.org/)
[](https://opensource.org/licenses/MIT)

## 📝 Giới thiệu

Dự án này là một quy trình hoàn chỉnh về thu thập và xử lý dữ liệu. Quy trình bao gồm hai giai đoạn chính:

1.  **Thu thập dữ liệu (Crawling)**: Sử dụng Python để tự động trích xuất dữ liệu thô từ một nguồn trên Internet.
2.  **Xử lý dữ liệu (Processing)**: Tận dụng sức mạnh của thư viện **NumPy** để làm sạch, tính toán, và phân tích dữ liệu đã thu thập được, chuẩn bị cho các bước phân tích sâu hơn hoặc trực quan hóa.

Mục tiêu là minh họa cách kết hợp kỹ thuật crawling và xử lý mảng hiệu suất cao để giải quyết các bài toán dữ liệu thực tế.

## ✨ Tính năng chính

  * **Thu thập dữ liệu tự động**: Script `Crawl.ipynb` được thiết kế để kết nối và lấy dữ liệu từ một nguồn trực tuyến.
  * **Xử lý hiệu suất cao**: `Process.ipynb` sử dụng mảng NumPy (ndarray) để thực hiện các phép toán số học, thống kê, và biến đổi dữ liệu một cách nhanh chóng.
  * **Làm sạch dữ liệu**: Loại bỏ các giá trị thiếu, chuẩn hóa định dạng, và chuyển đổi kiểu dữ liệu.
  * **Phân tích Thống kê**: Tính toán các chỉ số quan trọng như giá trị trung bình, trung vị, độ lệch chuẩn.
  * **Lưu trữ kết quả**: Dữ liệu thô và dữ liệu đã qua xử lý được lưu trữ có tổ chức để dễ dàng truy xuất.

## 📁 Cấu trúc Dự án

```
.
├── Crawl.ipynb         # Notebook thực hiện việc thu thập dữ liệu
├── Process.ipynb       # Notebook sử dụng NumPy để xử lý dữ liệu
├── data/               # Thư mục chứa dữ liệu
│   ├── raw_data.csv    # (Ví dụ) Dữ liệu thô sau khi crawl
│   └── processed_data.npy # (Ví dụ) Dữ liệu đã xử lý
└── requirements.txt    # Các thư viện cần thiết để chạy dự án
```

## ⚙️ Hướng dẫn Cài đặt và Sử dụng

### 1\. Yêu cầu

  * Python 3.8+
  * Jupyter Notebook hoặc Jupyter Lab

### 2\. Cài đặt môi trường

Đầu tiên, clone repository này về máy của bạn:

```bash
git clone https://github.com/VMSSON345/NumpyDataProcessing.git
cd NumpyDataProcessing
```

Tiếp theo, tạo file `requirements.txt` với nội dung bên dưới và cài đặt các thư viện cần thiết:

```bash
pip install -r requirements.txt
```

### 3\. Chạy dự án

Mở Jupyter Notebook hoặc Jupyter Lab:

```bash
jupyter notebook
```

Sau đó, thực hiện theo các bước sau:

1.  Mở và chạy file `Crawl.ipynb` để thu thập dữ liệu.
2.  Mở và chạy file `Process.ipynb` để xử lý dữ liệu đã thu thập.

-----

