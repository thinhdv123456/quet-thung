# Quét Serial Thùng

Web app quét mã QR thùng bằng camera iPhone, tự tách serial thành cột Thùng 1, Thùng 2… và xuất Excel. Chạy được khi không có mạng sau lần mở đầu tiên.

## Đưa lên GitHub Pages

1. Đăng nhập https://github.com, bấm **New repository**, đặt tên `quet-thung`, chọn **Public**, bấm **Create repository**.
2. Bấm **uploading an existing file**, kéo toàn bộ file vào, bấm **Commit changes**.
3. Vào **Settings → Pages**. Ở mục Branch chọn `main`, thư mục `/ (root)`, bấm **Save**.
4. Đợi 1–2 phút, link sẽ là: `https://<tên-tài-khoản>.github.io/quet-thung/`

## Cài lên iPhone

Mở link bằng **Safari** → bấm **Chia sẻ** → **Thêm vào MH chính** → **Thêm**.

## Cập nhật bản mới

Tải file mới lên đè file cũ, rồi sửa dòng `VERSION` trong `sw.js` (ví dụ `quet-thung-v2`) để iPhone nhận bản mới.

Thư viện dùng (tải từ jsDelivr, lưu offline sau lần mở đầu): jsQR, ZXing-js, SheetJS — đều theo giấy phép Apache-2.0.
