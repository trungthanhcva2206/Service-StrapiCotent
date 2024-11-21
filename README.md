# Service-StrapiCotent
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Service dùng để tạo, chỉnh sửa, xóa các bảng trong cơ sở dữ liệu. Từ cơ sở dữ liệu sẽ sinh ra tự động các API BackEnd để cung cấp dữ liệu từ cơ sở dữ liệu đến các service khác.

Nền tảng công nghệ LCDP sử dụng: **Strapi**

## Changelog

### v1.0
- Sinh ra tự động các API BackEnd để cung cấp dữ liệu từ cơ sở dữ liệu đến các service khác. 

## Hướng dẫn cài đặt
### 1. Yêu cầu hệ thống
- **Strapi**: Phiên bản >=5.0

### 2. Cài đặt dữ án
#### Bước 1: Tải mã nguồn từ bản phát hành
1. Truy cập trang phát hành chính thức tại: [Releases](https://github.com/trungthanhcva2206/Service-StrapiCotent/releases).
2. Chọn phiên bản phù hợp với nhu cầu của bạn.
3. Trong phần **Assets**, tải tệp:
   - `export_20241120202453.tar.gz`

#### Bước 2: Import vô Strapi
```bash
# Truy cập đến Strapi rồi thực hiện lệnh bên dưới để import vô Strapi
# /path/to/my/file: Phần này là đường dẫn đến tệp mà vừa tải ở bước 1.
npm run strapi import -- -f /path/to/my/file/export_20241120202453.tar.gz
```
## Tác giả
- Nguyễn Lê Trung Thành
- Trần Tuấn Anh
- Lê Văn Quang

# License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
