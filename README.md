# 🌟 Dự Án Quản Lý Tuyển Dụng

## 1. Giới Thiệu  
Dự án Quản Lý Tuyển Dụng là một hệ thống giúp quản trị viên dễ dàng quản lý các quá trình tuyển dụng, trong khi ứng viên có thể tìm kiếm, nộp hồ sơ ứng tuyển trực tuyến, nhận thông báo qua email và theo dõi tình trạng ứng tuyển.

## 2. Công Nghệ Sử Dụng  
- **Backend:** Laravel (PHP)  
- **Frontend:** Blade Template, HTML, CSS, JavaScript  
- **Cơ sở dữ liệu:** MySQL  
- **Gửi email:** Laravel Mail  

## 3. Chức Năng Chính  
### 💼 **Dành cho Quản Trị Viên (Admin)**  
- Quản lý danh sách công việc tuyển dụng: **Thêm, sửa, xóa công việc tuyển dụng**  
- Quản lý hồ sơ ứng viên: Duyệt hồ sơ, phê duyệt hoặc từ chối ứng viên
- Gửi thông báo xác nhận qua email cho ứng viên 
- Quản lý tình trạng ứng tuyển của các ứng viên
- Quản lý thông tin các công ty tuyển dụng

### 💼 **Dành cho Ứng Viên**  
- Tìm kiếm công việc theo ngành nghề, địa điểm
- Nộp hồ sơ trực tuyến cho các công việc tuyển dụng
- Nhận email xác nhận hồ sơ đã được nộp
- Theo dõi tình trạng hồ sơ và nhận thông báo từ nhà tuyển dụng

---

## 🛠 4. Hướng Dẫn Cài Đặt & Chạy Dự Án  

### 📂 **1. Clone repository về máy**  
```sh  
git clone <repo_url>  
cd quanlytuyendung.com  
```

### 📂 **2. Cài đặt dependencies**  
```sh  
composer install  
```

### 📂 **3. Cấu hình môi trường**  
- Copy file **`.env.example`** thành **`.env`**  
- Chỉnh sửa thông tin kết nối **database** trong `.env`  
- Tạo APP_KEY bằng lệnh:  
```sh  
php artisan key:generate  
```

### 📂 **4. Tạo cơ sở dữ liệu**  
```sh  
php artisan migrate  
```

### 📂 **5. Chạy server**  
```sh  
php artisan serve  
```

### 📂 **6. Chạy Seeder để tạo tài khoản mặc định**  

📍 **Tạo tài khoản admin:**  
```sh  
php artisan db:seed
```
📅 **Tài khoản admin:**  
✉ **Email:** admin@example.com  
🔑 **Mật khẩu:** 123456  

---

## 🏁 7. Truy Cập Hệ Thống  
🌍 **Trang chủ:** Mở trình duyệt và truy cập `http://127.0.0.1:8000/`  
🔐 **Trang đăng nhập Admin:** **Thêm `/admin` vào URL**  

---


## 📧 Liên Hệ  
📩 Nếu có bất kỳ câu hỏi hoặc cần hỗ trợ, vui lòng liên hệ qua email: **[hoanganhh080703@gmail.com]**  

💡 **✨ Cảm ơn bạn đã sử dụng hệ thống! ✨** 🚀

