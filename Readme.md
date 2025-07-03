# Bloom Haven - WordPress Plant Shop

Bloom Haven là website bán hàng trực tuyến chuyên về cây cảnh, hoa, chậu cây và phụ kiện trang trí cây xanh. Dự án sử dụng nền tảng WordPress với WooCommerce để cung cấp trải nghiệm mua sắm hiện đại, tiện lợi và thân thiện với người dùng.

## Tính năng chính

- **Giao diện hiện đại, responsive**: Sử dụng theme Flatsome tối ưu cho cửa hàng online.
- **Quản lý sản phẩm**: Thêm, sửa, xóa, phân loại sản phẩm cây cảnh, hoa, chậu cây, phụ kiện.
- **Giỏ hàng & Thanh toán**: Hỗ trợ đặt hàng, thanh toán trực tuyến, quản lý đơn hàng.
- **Danh sách yêu thích (Wishlist)**: Khách hàng có thể lưu lại sản phẩm yêu thích, chia sẻ với bạn bè/người thân.
- **Tìm kiếm & Lọc sản phẩm**: Dễ dàng tìm kiếm, lọc theo loại, giá, v.v.
- **Liên hệ & Hỗ trợ**: Tích hợp form liên hệ (Contact Form 7).
- **Kết nối quảng cáo Google**: Hỗ trợ Google Listings and Ads.
- **Đăng nhập bằng Facebook**: Hỗ trợ Nextend Facebook Connect.

## Công nghệ sử dụng

- **WordPress** (core)
- **WooCommerce** (plugin thương mại điện tử)
- **YITH WooCommerce Wishlist** (plugin wishlist)
- **Contact Form 7** (plugin form liên hệ)
- **Google Listings and Ads** (plugin quảng cáo)
- **Nextend Facebook Connect** (plugin đăng nhập mạng xã hội)
- **Flatsome Theme** (giao diện cửa hàng)
- **Docker Compose** (triển khai môi trường phát triển)

## Khởi động dự án

1. Cài đặt Docker & Docker Compose.
2. Tạo file `.env` từ `.env.example` và cập nhật thông tin database nếu cần.
3. Chạy lệnh:
   ```sh
   docker-compose up -d
   ```
4. Truy cập website tại: http://localhost:8080
5. Truy cập phpMyAdmin tại: http://localhost:8081

## Thư mục chính

- `wordpress/` - Mã nguồn WordPress và các plugin, theme.
- `uploads/` - Thư mục chứa ảnh sản phẩm, media upload.
- `Products/`, `Bloom Haven/`, `blog/` - Thư mục chứa hình ảnh sản phẩm, bài viết, banner...

## Thông tin liên hệ

- Website: [Bloom Haven]
- Email: [sontr.dev@gmail.com]

---

Bloom Haven - Mang thiên nhiên đến không gian sống của bạn!
