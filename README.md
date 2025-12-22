# KTPM_N5
# Bài tập lớn môn Kiểm Thử Phần Mềm

**Nhóm sinh viên:**
* Nguyễn Ngọc Sơn
* Đỗ Đức Anh 
* Nguyễn Mạnh Quân
* Bùi Thanh Minh
* Trần Hồng Sơn

**Giảng viên hướng dẫn:** Nguyễn Thị Thanh Huyển

---

## Nội dung đề tài

Kiểm thử Website Bán kính mắt


## Hướng dẫn cài đặt & Chạy

### 1. Chạy code tự động Kiểm thử trong Pycharm/VisualStudioCode

Phần này dành cho việc chạy các script kiểm thử viết bằng ngôn ngữ Python (sử dụng thư viện Selenium WebDriver)

Bước 1:Chạy lệnh sau trong terminal 
```bash
pip install selenium pytest
```
Bước 2: Chạy các file .py trong folder CodeTuDong.

### 2. Chạy code tự động Kiểm thử trong FireFox bằng SeleniumIDE

Phần này hướng dẫn sử dụng công cụ Selenium IDE (Extension) trên trình duyệt Firefox để chạy các file kịch bản .side.

Bước 1: Tải và cài đặt Extension
Tải Selenium IDE cho Firefox

[(https://addons.mozilla.org/en-US/firefox/addon/selenium-ide/)]

Nhấn nút Add to Firefox (Thêm vào Firefox).


Bước 2: Mở và Chạy dự án (File .side)
Nhấn vào biểu tượng Selenium IDE (hình máy quay phim) trên thanh công cụ của Firefox để mở ứng dụng.

Tại màn hình chính, chọn dòng: "Open an existing project".

Chọn file dự án có đuôi .side nằm trong thư mục FileSeleniumIDE.

Giao diện dự án hiện ra, chọn Test Case bạn muốn chạy ở cột danh sách bên trái.

Nhấn nút Run all tests (Biểu tượng tam giác Play ▶) trên thanh menu để bắt đầu chạy kiểm thử tự động.
