# 📒 TikiClawer
![GitHub repo size](https://img.shields.io/github/repo-size/QuachNgoc/TikiClawer?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/QuachNgoc/TikiClawer?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/QuachNgoc/TikiClawer?style=for-the-badge)
![GitHub open issues](https://img.shields.io/github/issues/QuachNgoc/TikiClawer?style=for-the-badge)

## Description
> #### "Creating a simple Tiki information gathering tool to export data into a CSV file that can be imported into Woocommerce.


## 🧐 Authors
**Author**: Quách Bảo Ngọc - 20520655
**Role**: Main Developer

## 👩‍💻🧑‍💻 Teams:
Trịnh Văn Hậu

Nguyễn Thể Phong

Nguyễn Thị Trà Giang

Đào Võ Trường Giang 

Lê Vũ Quốc Việt


## 🖼️ Giao diện

### 1. Main.exe
![3](https://user-images.githubusercontent.com/80575560/232669725-52e87e5e-8b8a-4b56-8fe7-527d34693527.png)

### 2. Khi chạy app
![4](https://user-images.githubusercontent.com/80575560/232669727-ef8e6435-f2b2-41c6-a52e-281929e5eec1.png)

### 3. Import thành công
![1](https://user-images.githubusercontent.com/80575560/232669709-e297f8e0-e47b-48a1-b166-4144a4da9792.png)

### 4. Các sản phẩm đã import
![2](https://user-images.githubusercontent.com/80575560/232669718-aa018399-9503-447d-b25a-114fccae62b0.png)

## ⚙️ Hướng dẫn sử dụng
<b>C1: Sử dụng Python để chạy</b>
- Chạy file requirements.txt <code> pip install -r requirements.txt </code>
- Chạy file main.py <code> python main.py </code>


<b>C2: Sử dụng exe </b>
- Truy cập folder *dist*, chạy main.exe


<b>HƯỚNG DẪN CHI TIẾT</b>
PHẦN 1: TIKI CLAWER
    1. Người dùng nhập cách từ khóa cần claw và số trang cần claw ( mỗi trang tương ứng 50 sản phẩm * số trang = tổng sản phẩm )
    2. Xuất hiện 2 file:
      2.1 data.txt: Lưu các thông tin thành các dictionary để dễ xem thông tin
      2.2 import_csv.csv: File được tạo từ data.txt để import lên Wordpress


PHẦN 2: WOOCOMMERCE DASHBOARD
ĐỌC HƯỚNG DẪN TRÊN MÀN HÌNH APP.
  
## 🥲 Chức năng tương lai
TODO: 
  1. Hỗ trợ tạo Coupons, Report
  2. Upload hình ảnh lên Woo

## License
This project is licensed under the ISC License.
