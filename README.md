# VHG – Living Furniture (GitHub Pages)

## Triển khai
1. Copy toàn bộ nội dung thư mục này vào repo `livingfurniture` (nhánh `main`).
2. Settings → Pages → Source: Deploy from a branch → `main` / `(root)`.
3. Site chạy tại `https://<tài khoản>.github.io/livingfurniture/`.

## Ảnh cần bỏ vào `assets/img/`
| File | Vị trí | Tỷ lệ | Rộng gợi ý | Nội dung |
|---|---|---|---|---|
| hero-kitchen.jpg | Hero 1 | 16:9 | 2400px | Bếp hiện đại, cabinetry rõ nét |
| hero-vanity.jpg | Hero 2 | 16:9 | 2400px | Phòng tắm cao cấp, tủ lavabo nổi bật |
| hero-home.jpg | Hero 3 | 16:9 | 2400px | Phòng khách/nội thất hiện đại |
| about-development.jpg | About | 4:5 | 1200px | Mẫu gỗ, vật liệu, phát triển sản phẩm |
| cat-kitchen.jpg | Kitchen Cabinet | 4:3 | 1600px | Tủ bếp trong không gian thực |
| cat-vanity.jpg | Bathroom Vanity | 3:4 | 1400px | Tủ lavabo hoàn thiện |
| cat-home.jpg | Home Furniture | 4:3 | 1400px | Living/bedroom/dining |
| cat-outdoor.jpg | Outdoor Furniture | 4:3 | 1400px | Patio, terrace, resort |

### Ảnh bổ sung (gallery và dải ảnh)
| File | Vị trí | Tỷ lệ | Nội dung |
|---|---|---|---|
| gal-kitchen-dark.jpg, gal-dining.jpg | Gallery "Applications" | 4:5 | Tủ bếp, phòng ăn |
| gal-vanity-green.jpg, gal-kitchen-wood.jpg | Gallery | 1:1 | Tủ lavabo, bếp |
| gal-bedroom.jpg, gal-patio.jpg | Gallery | 4:3 | Phòng ngủ, ngoài trời |
| band-workshop.jpg | Dải ảnh trước "Năng lực cốt lõi" | 21:9 | Xưởng sản xuất |
| band-port.jpg | Nền phần "Đối tác" | 21:9 | Cảng / logistics |

Ảnh hiện tại là ảnh minh họa từ Unsplash, xem nguồn trong `CREDITS.md`. Thay bằng ảnh VHG cùng tên file khi có.

Chỉ dùng ảnh VHG sở hữu hoặc ảnh stock có giấy phép (Unsplash/Pexels). Ảnh nhà máy tham khảo phải ghi chú là ảnh minh họa.
Đổi tên hoặc thêm ảnh: sửa đối tượng `IMG` ở đầu `js/main.js`.

## Nhận diện thương hiệu
Logo nằm trong `assets/img/brand/`:
- `logo-vhg-lf.png`: logo đầy đủ, đã cắt sát. Chữ màu trắng, chỉ đặt trên nền tối.
- `mark.png`, `favicon-64.png`, `apple-touch-icon.png`: khối lục giác dùng làm favicon và icon trên điện thoại.
- `logo-vhg-lf-original.png`: file gốc.

Bảng màu lấy từ logo (khai báo ở đầu `css/style.css`):

| Biến | Màu | Dùng cho |
|---|---|---|
| `--green` | `#1C4A48` teal đậm | Header, nền tối, nút chính |
| `--sand` | `#6CCCCC` teal sáng | Điểm nhấn trên nền tối, nút trên hero |
| `--mg` | `#26736F` teal vừa | Chữ nhấn và icon trên nền sáng |
| `--bg` | `#FFFFFF` trắng | Nền trang (luôn sáng, không tự chuyển chế độ tối) |
| `--grad` | Gradient teal `#1C4A48 → #6CCCCC` | Header khi cuộn, nút chính, khối nổi bật, footer |
| `--char` | `#17302F` | Chữ chính, phần Đối tác |
