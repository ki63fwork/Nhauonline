# Đại Chiến 50 Tướng — 6v6

Game HTML/CSS/JavaScript thuần, không cần cài đặt hay build.

## Chạy thử
- Mở `index.html` bằng trình duyệt hiện đại.
- Giữ nguyên thư mục `assets/` cạnh `index.html` để tải ảnh chiến trường mặc định.

## Đưa lên GitHub Pages
1. Tạo repository mới trên GitHub.
2. Upload `index.html`, thư mục `assets/` và file README này lên thư mục gốc.
3. Vào **Settings → Pages**.
4. Chọn **Deploy from a branch**, branch `main`, folder `/ (root)`, rồi Save.
5. Đợi GitHub Pages xuất bản và mở URL được cung cấp.

## Tính năng
- 50 tướng, đội hình 6v6, triệu hồi, nâng cấp và chiến đấu theo lượt.
- Tùy chỉnh hình ảnh chân dung, ảnh tiến hóa, GIF/video và âm thanh tướng.
- Xưởng thiết kế 4 kỹ năng riêng cho từng tướng: tên, hệ số, loại, hiệu ứng, màu, chuyển động, GIF và âm thanh.
- Chọn kỹ năng theo từng tướng trước khi ra lệnh.
- Hiệu ứng hạt và âm thanh tổng hợp bằng Web Audio API khi không tải âm thanh riêng.
- Lưu tiến trình và media trong localStorage của trình duyệt.

## Lưu ý
- Đây là bản game chạy cục bộ phía trình duyệt; chưa có tài khoản, máy chủ, đồng bộ thiết bị hay PvP online.
- Dữ liệu localStorage không tự chuyển sang thiết bị khác. Dùng chức năng xuất dữ liệu để sao lưu thông số; ảnh/âm thanh tải lên có giới hạn dung lượng trình duyệt.
- Hiệu ứng chiến trường mặc định nằm tại `assets/battlefield.webp`.
