# Bé Cá Store — Nước hoa chính hãng Cần Thơ

Web bán nước hoa Bé Cá Store — Thiện Hoàng, Cần Thơ.

- Zalo / Hotline: 0838989567 — https://zalo.me/0838989567
- Facebook: https://www.facebook.com/share/17tcD3VWrf/
- Địa chỉ: Đường Ngô Đức Kế, Phường Ninh Kiều, TP. Cần Thơ
- Giờ mở cửa: 08:30 - 21:30 hàng ngày

## Có gì trong web

- Trang chủ: hero, danh mục (Nam / Nữ / Unisex / Chiết / Set quà tặng), lọc giá, tìm kiếm, 8 sản phẩm giá cố định.
- Trang chi tiết: chọn dung tích, tháp hương Đầu / Giữa / Cuối, giỏ hàng, đặt hàng qua Zalo (đơn được lưu lại).
- Admin: đăng nhập, 4 tab Tổng quan / Sản phẩm / Đơn hàng qua Zalo / Cài đặt shop. Đăng / sửa / xóa / ẩn sản phẩm, chọn ảnh từ máy (xem trước, nén 800px), đổi mật khẩu admin, sửa thông tin shop.
- Không có Blog / Quiz / Reviews / FAQ.

## Chạy

Mở `index.html` bằng trình duyệt, hoặc deploy lên Vercel (auto-deploy khi push lên nhánh `main`).

Dữ liệu sản phẩm / đơn / cài đặt lưu trong localStorage của trình duyệt (key `becastore_products_v2`, `becastore_orders_v2`, `becastore_settings_v1`). Lần đầu mở Admin, mật khẩu bạn nhập (từ 6 ký tự) sẽ trở thành mật khẩu quản trị — file này không còn mật khẩu mặc định nào, nên đẩy lên GitHub công khai cũng không lộ mật khẩu. Ảnh 5 sản phẩm đã lưu sẵn trong `assets/` (không còn link tạm của Stitch); 3 ảnh Unsplash vẫn dùng link ngoài.

## Nguồn

- Bảng giá / sản phẩm chuẩn: `../beca-store/source-table.md` (trong máy của chủ shop, không push lên repo).
- Bản Stitch v3 đã kiểm chứng: 8 sản phẩm, tổng giá 25.349.000đ, không có đơn giả mẫu.
