# Night Ride Story — Final V5

Bản V5 giữ nguyên toàn bộ ảnh nhúng trực tiếp trong `index.html`, nên không phụ thuộc thư mục assets và phù hợp với GitHub → Vercel.

## Thay đổi chính

- Font bài báo: serif nghiêm túc, ưu tiên Cambria / Noto Serif / Georgia / Times New Roman, hỗ trợ tiếng Việt tốt.
- Font giao diện: system UI (`Segoe UI`, Roboto, Arial...) để ổn định trên Windows, Android, iPhone và không cần tải font ngoài.
- Mobile tối ưu lại landing, caption, controls, modal bài báo, safe-area iPhone và chế độ landscape.
- Trên điện thoại: chạm khách lần 1 xem thẻ thông tin nhanh, chạm lần 2 mở bài báo.
- Giữ nguyên điều kiện phải xem bài báo trước khi nút `Trả khách` xuất hiện.
- Toàn bộ ảnh vẫn nhúng trực tiếp trong `index.html` để tránh lỗi Vercel không tải được ảnh.

## Deploy

Upload 3 file này vào root repository GitHub:

- `index.html`
- `vercel.json`
- `README.md`

Vercel: Framework Preset = Other, không cần Build Command hoặc Output Directory.
