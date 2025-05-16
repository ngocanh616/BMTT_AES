🚀 BMTT_AES - Bộ Công Cụ Mã Hóa AES Đa Năng

📋 Tổng quan

Web AES Crypto là một ứng dụng web cho phép người dùng mã hóa và giải mã dữ liệu bằng cách sử dụng thuật toán AES. Được xây dựng với Python, Flask và Bootstrap, ứng dụng cung cấp giao diện trực quan, dễ sử dụng, và thực hiện các thao tác mã hóa an toàn.

✨ Tính năng

🔒 Mã hóa văn bản bằng thuật toán AES-128, AES-192, hoặc AES-256
🔓 Giải mã văn bản đã được mã hóa
🔄 Hỗ trợ nhiều chế độ mã hóa khác nhau (CBC, CFB, OFB, CTR)
🔑 Cho phép người dùng tự nhập khóa bảo mật
🧩 Tùy chọn sử dụng vector khởi tạo (IV) tùy chỉnh
💻 Giao diện thân thiện với người dùng
🛡️ Xử lý bảo mật dữ liệu người dùng

🚀 Cài đặt

Clone repository:
git clone https://github.com/ngocanh616/BMTT_AES.git
Di chuyển vào thư mục dự án:
cd BMTT_AES
Cài đặt các dependencies:
pip install -r requirements.txt
Chạy ứng dụng:
flask run
hoặc
python app.py

📝 Cách sử dụng

🌐 Truy cập ứng dụng thông qua trình duyệt web (mặc định:http://127.0.0.1:5000)

🔄 Chọn chế độ mã hóa hoặc giải mã

✏️ Nhập văn bản cần xử lý

🔑 Nhập khóa bảo mật (secret key)

⚙️ Tùy chọn: Cấu hình thêm các tham số khác như chế độ mã hóa, vector khởi tạo

🖱️ Nhấn nút "Mã hóa" hoặc "Giải mã" để thực hiện thao tác

✅ Kết quả sẽ được hiển thị trên giao diện

🛠️ Công nghệ sử dụng

🐍 Python: Ngôn ngữ lập trình back-end

🌶️ Flask: Framework web để xây dựng ứng dụng

🎨 Bootstrap: Tạo giao diện responsive

📜 JavaScript: Xử lý mã hóa/giải mã phía client

🔒 Bảo mật

🔐 Quá trình mã hóa/giải mã có thể được thực hiện ở phía server hoặc phía client tùy vào cấu hình
🚫 Không lưu trữ dữ liệu người dùng hoặc khóa mã hóa sau khi xử lý
🔐 Sử dụng HTTPS để bảo vệ dữ liệu trong quá trình truyền tải (khi triển khai)
👁️ Mã nguồn mở, có thể kiểm tra tính toàn vẹn của ứng dụng

📞 Liên hệ
Ngoc Anh - @ngocanh616
Link dự án: https://github.com/ngocanh616/BMTT_AES

📂 **CẤU TRÚC DỰ ÁN BMTT_AES**


BMTT_AES/
│
├── app.py                # Entry point của ứng dụng Flask
├── templates/            # Thư mục chứa các template HTML
│   ├── index.html        # Trang chính
│   ├── base.html         # Template cơ sở cho giao diện
│   ├── error.html        # Trang hiển thị lỗi
│   └── result.html       # Trang hiển thị kết quả
│
├── static/               # Thư mục chứa các file tĩnh
│   └── style.css         # Stylesheet và Bootstrap
│
├── aes/                  # Các module chức năng
│   ├── decryption.py     # Module xử lý giải mã AES
│   ├── encryption.py     # Module xử lý mã hóa AES
│   └── utils.py          # Các hàm tiện ích
│
├── requirements.txt      # Danh sách các dependency
└── README.md             # Tài liệu hướng dẫn
