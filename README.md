# 🚲 Bicycle E-Commerce Platform - Java Spring Boot + SQL Server

Trang web bán xe đạp thương mại điện tử, được phát triển bằng **Java Spring Boot**, **SQL Server**, sử dụng **AngularJS + Bootstrap** cho giao diện người dùng. 
Hệ thống cung cấp đầy đủ tính năng mua sắm, quản lý đơn hàng và trang quản trị.

---

## 🎯 Tính năng chính

### 👥 Người dùng
- Đăng ký, đăng nhập, xác thực JWT
- Quản lý tài khoản cá nhân
- Giỏ hàng, danh sách yêu thích
- Đặt hàng, xem lịch sử mua hàng 🧾
- Tìm kiếm, lọc sản phẩm
- Gửi liên hệ qua email

---

## 🎯 Tính năng chính

### 👥 Người dùng
- Đăng ký, đăng nhập, xác thực JWT
- Quản lý tài khoản cá nhân
- Giỏ hàng, danh sách yêu thích
- Đặt hàng, xem lịch sử mua hàng 🧾
- Tìm kiếm, lọc sản phẩm
- Gửi liên hệ qua email

### 🔐 Xác thực & phân quyền
- Spring Security + JWT
- Role-based: `USER`, `ADMIN`, `STAFF`

### 🧑‍💼 Quản trị viên (Admin Panel)
(Theo hình ảnh giao diện bạn gửi)

- 📊 **Bảng điều khiển**
- 👤 **Quản lý tài khoản**
- 🚲 **Quản lý sản phẩm**
- 📝 **Quản lý bài viết (tin tức, blog)**
- 📂 **Danh mục sản phẩm**
- 🎟️ **Mã giảm giá**
- 🎨 **Màu sắc sản phẩm**
- 🌟 **Thương hiệu xe**
- 📏 **Kích thước khung, bánh**
- 🛍️ **Đơn hàng**
- 📈 **Thống kê doanh thu**

---

## 🛠️ Công nghệ sử dụng

| Layer            | Công nghệ                    |
|------------------|------------------------------|
| Backend          | Java Spring Boot 2.5.0       |
| ORM              | Spring Data JPA              |
| Database         | SQL Server                   |
| Security         | Spring Security + JWT        |
| UI Framework     | Bootstrap 4, AngularJS       |
| Template Engine  | Thymeleaf                    |
| Mail Service     | SMTP                         |

---

## 🗂️ Thư viện đã sử dụng

**Tự động cài qua Maven:**
- `spring-boot-starter-web`, `data-jpa`, `security`, `thymeleaf`, `mail`, `validation`
- `mssql-jdbc`, `lombok`, `devtools`
- `org.apache.poi` (Excel xuất nhập)
- `commons-io`, `commons-lang3`

**⚠️ Cần cài đặt thủ công (frontend hoặc download ngoài Maven):**
- ✅ Java JDK 11 hoặc mới hơn
- ✅ Maven 3.6+
- ✅ Eclipse IDE hoặc IntelliJ
- ✅ SQL Server
- ✅ Project Lombok (cài bằng file `lombok.jar`)

---


