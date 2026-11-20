# Mẫu trang web AcelatwoReel (GitHub Pages)

Đưa toàn bộ file lên repo public `<username>.github.io`, rồi bật Settings → Pages (nhánh main, thư mục root).

## Sửa trước khi dùng
| File | Sửa gì |
|---|---|
| tất cả `.html` | Thay `TEN-BAN` bằng username GitHub của bạn; `email-cua-ban@gmail.com` bằng email liên hệ |
| `index.html`, `privacy.html`, `terms.html` | Tên app/thương hiệu nếu không dùng "AcelatwoReel", tên kênh, ngày cập nhật |
| `tiktok.html` | `DAN_CLIENT_KEY_TIKTOK` → Client key của app TikTok (Sandbox hoặc Production) |
| `tiktok-callback.html` | Link tới workflow "Kết nối TikTok" trong repo mã nguồn của bạn |
| thêm file | `icon-512.png` và `icon-1024.png` (logo của bạn, 512×512 và 1024×1024) |
| thêm file | File xác minh `tiktok....txt` do TikTok cấp (đặt ở gốc repo) |

`quanly/index.html` là trang quản lý có mật khẩu. File `quanly/data.json` sẽ do GitHub Actions của repo mã nguồn tự tạo
(cần secrets `SITE_TOKEN`, `DASH_PASSWORD` và variables `SITE_URL`, `SITE_REPO`; xem HUONG_DAN_DUNG_LAI.md).
