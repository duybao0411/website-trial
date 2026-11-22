# Học từ vựng tiếng Trung

## GitHub Pages và tên miền riêng

1. Đẩy các tệp trong thư mục này lên nhánh `main` của `duybao0411/website-trial`.
2. Trong repo GitHub, vào **Settings → Pages** và chọn **Deploy from a branch**, nhánh `main`, thư mục `/ (root)`. Nếu đang dùng workflow GitHub Actions, giữ workflow đó.
3. Trong phần **Custom domain**, nhập `tuhoctiengtrung.io.vn` rồi lưu.
4. Tại nhà cung cấp DNS cho tên miền, tạo bốn bản ghi `A` cho host `@`, lần lượt trỏ tới `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`.
5. Chờ DNS cập nhật; sau đó bật **Enforce HTTPS** trong Settings → Pages khi tùy chọn xuất hiện.

Tùy chọn: tạo bản ghi `CNAME` cho host `www` trỏ tới `duybao0411.github.io` để hỗ trợ `www.tuhoctiengtrung.io.vn`.
