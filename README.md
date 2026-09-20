# Đồ án môn Khai phá dữ liệu

## 1. Giới thiệu
Đồ án tiếp tục đi sâu trên một trong ba bộ dữ liệu đã sử dụng ở phần bài tập thực hành. Mục tiêu là kết hợp nhiều kỹ thuật khai phá dữ liệu để trả lời các câu hỏi thực tế, diễn giải kết quả, rút ra phát hiện và đề xuất khuyến nghị.

## 2. Bộ dữ liệu
Bộ dữ liệu được chọn: **Diabetes 130-US Hospitals**.

Dữ liệu đã được khảo sát và tiền xử lý ở phần bài tập thực hành trước đó. Đồ án sử dụng lại dữ liệu đã xử lý để tập trung vào phân tích tổng hợp, không lặp lại toàn bộ quy trình tiền xử lý.

## 3. Hướng phân tích
Đồ án tập trung vào các câu hỏi liên quan đến tình trạng tái nhập viện của bệnh nhân đái tháo đường và kết hợp các kết quả từ nhiều kỹ thuật khai phá dữ liệu.

Các kỹ thuật chính:
- Phân lớp (Classification)
- Luật kết hợp (Association Rules)
- Kỹ thuật nâng cao được lựa chọn dựa trên hạn chế phát hiện trong quá trình phân tích

## 4. Cấu trúc thư mục
```text
ten-nhom-do-an/
├── README.md
├── requirements.txt
├── data/
├── phan-tich-tong-hop.ipynb
└── report/
    └── bao-cao.pdf
```

- `README.md`: hướng dẫn môi trường và cách chạy lại đồ án.
- `requirements.txt`: danh sách thư viện Python cần thiết.
- `data/`: dữ liệu dùng cho đồ án hoặc script/đường dẫn để tái tạo dữ liệu.
- `phan-tich-tong-hop.ipynb`: notebook tổng hợp liên kỹ thuật và tạo các hình/bảng sử dụng trong báo cáo.
- `report/bao-cao.pdf`: báo cáo đồ án hoàn chỉnh.

## 5. Cài đặt môi trường
Khuyến nghị sử dụng Python 3.11 hoặc phiên bản tương thích với các thư viện trong `requirements.txt`.

Tạo môi trường ảo (khuyến nghị):

```bash
python -m venv .venv
```

Kích hoạt trên Windows:

```bash
.venv\Scripts\activate
```

Cài đặt thư viện:

```bash
pip install -r requirements.txt
```

## 6. Cách chạy
1. Đảm bảo dữ liệu cần thiết nằm trong thư mục `data/` và đường dẫn trong notebook là đường dẫn tương đối.
2. Mở `phan-tich-tong-hop.ipynb` bằng Jupyter Notebook, JupyterLab hoặc VS Code/Antigravity có hỗ trợ notebook.
3. Chọn đúng Python environment đã cài các thư viện trong `requirements.txt`.
4. Restart kernel và chạy toàn bộ notebook từ đầu đến cuối.
5. Kiểm tra các bảng, biểu đồ và kết quả được tạo ra đầy đủ.

## 7. Khả năng tái lập
Notebook được tổ chức để có thể chạy lại từ đầu. Không sử dụng đường dẫn tuyệt đối phụ thuộc vào máy cá nhân. Các kết quả kỹ thuật cũ chỉ được sử dụng làm nền tảng; notebook đồ án tập trung vào phân tích liên kỹ thuật, phát hiện, diễn giải và kỹ thuật nâng cao.

## 8. Báo cáo
Báo cáo chính nằm tại:

```text
report/bao-cao.pdf
```

Báo cáo trình bày câu hỏi dẫn dắt, tổng hợp liên kỹ thuật, kỹ thuật nâng cao tự tìm hiểu, các phát hiện, bàn luận, giới hạn, khuyến nghị và kết luận.
