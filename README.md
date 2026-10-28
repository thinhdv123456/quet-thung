# Kho Oanh Ninh Bình

Công cụ của thủ kho Nguyễn Thị Kim Oanh (Ninh Bình).

Web app 2 chức năng, chạy được khi không có mạng sau lần mở đầu tiên:

- **Quét thùng**: quét mã QR / PDF417 trên tem thùng bằng camera iPhone, tách serial thành cột Thùng 1, Thùng 2… và xuất Excel.
- **Phân bổ hàng** (dùng trên máy tính): đọc file tồn kho BCCS (sheet Chi tiết NV), nhập nhiều mặt hàng cùng lúc (tổng số lượng, quy cách thùng, định mức tồn), chia cho huyện rồi cho nhân viên theo thùng + lẻ, xuất ra sheet "chot" theo file mẫu đặt hàng.

## Đưa lên GitHub Pages

1. Đăng nhập https://github.com, bấm **New repository**, đặt tên `quet-thung`, chọn **Public**, bấm **Create repository**.
2. Bấm **uploading an existing file**, kéo toàn bộ file vào, bấm **Commit changes**.
3. Vào **Settings → Pages**. Ở mục Branch chọn `main`, thư mục `/ (root)`, bấm **Save**.
4. Đợi 1–2 phút, link sẽ là: `https://<tên-tài-khoản>.github.io/quet-thung/`

## Cài lên iPhone

Mở link bằng **Safari** → bấm **Chia sẻ** → **Thêm vào MH chính** → **Thêm**.

## Cập nhật bản mới

Tải file mới lên đè file cũ, rồi sửa dòng `VERSION` trong `sw.js` (ví dụ `quet-thung-v2`) để iPhone nhận bản mới.

Thư viện dùng (tải từ jsDelivr, lưu offline sau lần mở đầu): jsQR, ZXing-C++ (zxing-wasm), SheetJS, ExcelJS (MIT) — đều theo giấy phép Apache-2.0.
