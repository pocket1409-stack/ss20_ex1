


### 1. Ký tự lạ & cơ chế đánh lừa

-   **Không rõ ký tự:** (chữ có dấu sắc, mã Unicode ) thay cho chữ chuẩn ASCII.  **`ú`**`u``U+00FA`**`u`**
    
-   **Lý do bị lừa:** Đây là kỹ thuật **Homograph attack** – dùng ký tự Unicodegiống chữ cái bình thường để lừa mắt người dùng đang ngụy.
    

### 2. Quy trình kiểm tra URL nhanh chóng

1.  **Trình quản lý mật khẩu :** If Bitwarden/1Password **không tự động điền (Auto-fill)** tài khoản, 99% đó là trang web giả lừa. 
2.  **Soi tên miền bằng mắt:** Nhìn kỹ phần trước đuôi `.com`. Đảm bảo chính xác từng ký tự là `github.com`(không dấu, không thêm thông báo hoặc sai chính tả).
    
3.  **Quét công cụ:** Sao chép URL dán vào *VirusTotal.com* để kiểm tra toàn bộ dữ liệu trước khi đăng nhập.
