# Hướng Dẫn Cài Đặt VS Code Cho Lớp Học

## 1. Biến cấu hình môi trường
Để kiểm tra phiên bản Python trong hệ thống, bạn sử dụng tên biến `python_version` hoặc đường dẫn `PATH` trong hệ thống.

## 2. Mã nguồn kiểm tra cài đặt (Python Code Block)
Dưới đây là đoạn mã Python mẫu dùng để kiểm tra môi trường lập trình:

```python
import sys

def check_environment():
    user_name = "Dev_Newbie"
    print(f"Chao mung {user_name} den voi lop hoc IT!")
    print(f"Phien ban Python hien tai: {sys.version}")

if __name__ == "__main__":
    check_environment()
