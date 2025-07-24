# Hướng dẫn cài đặt và kết nối MongoDB trên Windows

## Giới thiệu
MongoDB là một cơ sở dữ liệu NoSQL phổ biến, lưu trữ dữ liệu dưới dạng tài liệu BSON (Binary JSON). Dưới đây là hướng dẫn cài đặt MongoDB và kết nối với cơ sở dữ liệu MongoDB trên hệ điều hành Windows.

## Cài đặt MongoDB trên Windows

### 1. **Tải và cài đặt MongoDB**:
- Truy cập [MongoDB Download Center](https://www.mongodb.com/try/download/community).
- Chọn phiên bản MongoDB phù hợp với hệ điều hành Windows (chọn MSI Package).
- Chạy file `.msi` để cài đặt MongoDB.
- Trong quá trình cài đặt, đảm bảo rằng bạn chọn "Install MongoDB as a Service" để MongoDB tự động khởi động khi hệ thống Windows khởi động.

### 2. **Kiểm tra MongoDB**:
Sau khi cài đặt, mở **Command Prompt** và kiểm tra phiên bản MongoDB:
```bash
mongo --version
