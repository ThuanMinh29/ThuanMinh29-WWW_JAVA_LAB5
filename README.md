# 21034811_NguyenMinhThuan_DHKTPM17A

**Họ tên:** Nguyễn Minh Thuận  
**Mã số sinh viên:** 21034811  
**Lớp:** DHKTPM17A  
**Giáo viên hướng dẫn:** Võ Văn Hải  

---

## Giới Thiệu

Dự án này là một ứng dụng web được thiết kế để quản lý thông tin ứng viên và công ty trong lĩnh vực tuyển dụng.  
Ứng dụng được xây dựng bằng **Spring Boot**, tích hợp với **MariaDB** để quản lý dữ liệu và sử dụng **Bootstrap** nhằm đảm bảo giao diện thân thiện với người dùng.  
Hệ thống tuân theo kiến trúc **MVC**, tận dụng **Thymeleaf** để hiển thị nội dung động và **Spring Data JPA** để tương tác hiệu quả với cơ sở dữ liệu.

---

## Các Chức Năng

### Quản Lý Công Ty

- Thêm mới, chỉnh sửa và cập nhật thông tin công ty.  
- Xem danh sách các công ty.  

### Quản Lý Công Việc

- Tạo mới và chỉnh sửa các công việc.  
- Liên kết công việc với các công ty liên quan.  
- Quản lý danh sách ứng viên phù hợp với từng công việc.  

### Quản Lý Ứng Viên

- Thêm mới và chỉnh sửa hồ sơ ứng viên.  
- Gợi ý công việc phù hợp cho ứng viên.  
- Đề xuất các kỹ năng ứng viên cần cải thiện.  
- Gửi thư mời phỏng vấn qua email.  

### Hiển Thị Dữ Liệu

- Hiển thị dữ liệu có hoặc không phân trang để nâng cao trải nghiệm người dùng.  

---

## Mục Tiêu Dự Án

Ứng dụng nhằm:  

- Tối ưu hóa trải nghiệm người dùng với giao diện trực quan và các tính năng thông minh.  
- Kết nối hiệu quả giữa ứng viên và nhà tuyển dụng.  
- Cung cấp các tính năng như gửi email tự động và gợi ý kỹ năng/công việc để tăng tính tương tác.  
- Đảm bảo bảo mật dữ liệu cao và hỗ trợ SEO để cải thiện khả năng tiếp cận.  

---

## Công Nghệ Sử Dụng

- **Spring Boot**  
  - Spring Data JPA  
  - Spring Security  
- **Thymeleaf**  
- **MariaDB**  
- **Bootstrap**  

---

## Kiến Trúc Hệ Thống

Ứng dụng được xây dựng theo mô hình **MVC**:

- **Model**: Xử lý dữ liệu và tương tác với cơ sở dữ liệu.  
- **View**: Sử dụng **Thymeleaf** để hiển thị nội dung động.  
- **Controller**: Quản lý luồng ứng dụng và các tương tác của người dùng.  

---

## Các Giao Diện Chính

### 1. **Giao Diện Chính**  
Tổng quan bảng điều khiển.  
![image](https://github.com/user-attachments/assets/57a63802-a473-455a-b9a1-c58c317b69b7)

---

### 2. **Quản Lý Ứng Viên**  
#### - Danh sách ứng viên  
![image](https://github.com/user-attachments/assets/379c93de-5d06-46d3-98c1-d12c6e427578)

#### - Thêm thông tin ứng viên  
![image](https://github.com/user-attachments/assets/2f5def27-5a18-4fc8-b8d6-4ff0af783495)


#### - Chỉnh sửa thông tin ứng viên  
![image](https://github.com/user-attachments/assets/d1d874b4-be28-4593-8b41-73189ced9dd7)


#### - Gợi ý công việc và kỹ năng  
![image](https://github.com/user-attachments/assets/c02a9a1e-fb21-4503-8c71-68c054a550ef)

#### - Danh sách ứng viên không phân trang  
![image](https://github.com/user-attachments/assets/5a0bc716-0821-4f83-9fba-1e3ef39fb32e)

---

### 3. **Quản Lý Công Ty**  
#### - Danh sách công ty  
![image](https://github.com/user-attachments/assets/bcf58f6d-3224-4101-b02d-565a13704840)


#### - Thêm thông tin công ty  
![image](https://github.com/user-attachments/assets/0248a9fe-8753-4130-866b-0f321495febf)

#### - Chỉnh sửa thông tin công ty  
![image](https://github.com/user-attachments/assets/b54b65ef-4c57-44f6-9d14-3a3474f1a9a6)

---

### 4. **Quản Lý Công Việc**  
#### - Danh sách công việc  
![image](https://github.com/user-attachments/assets/c7e3823d-ed5e-4c95-acce-ebf377176147)

#### - Liên kết công việc với các công ty  
![image](https://github.com/user-attachments/assets/86db4111-29da-432a-b7f9-cc76d3ceeba2)


#### - Xem danh sách ứng viên phù hợp  
![image](https://github.com/user-attachments/assets/6dbdbc64-f954-4aec-b6e0-42f2679d0e3a)

---

### 5. **Gửi Email**  
Gửi thư mời phỏng vấn tự động cho ứng viên.  
![image](https://github.com/user-attachments/assets/b6483c00-92af-43ea-9b2a-e3ad03369534)


---

## Định Hướng Phát Triển

- Cải thiện giao diện người dùng bằng các framework frontend hiện đại.  
- Tích hợp các công cụ phân tích và báo cáo nâng cao.  
- Nâng cao bảo mật với xác thực hai lớp (2FA) hoặc OAuth2.  
- Ứng dụng trí tuệ nhân tạo (AI) để gợi ý công việc và kỹ năng tốt hơn.
