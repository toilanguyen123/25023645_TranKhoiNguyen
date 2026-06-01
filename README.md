# 📁 Cấu trúc thư mục Portfolio

```
portfolio/
├── index.html       ← File web chính (KHÔNG cần sửa)
├── config.js        ← ⭐ CHỈ SỬA FILE NÀY để thay đổi nội dung
├── avatar.jpg       ← Ảnh đại diện (thay bằng ảnh của bạn)
├── nhac-nen.mp3     ← Nhạc nền (thêm file MP3 vào đây)
├── anh-nen.jpg      ← Ảnh nền trang (tuỳ chọn)
└── README.md        ← File hướng dẫn này
```

## ✏️ Cách thay đổi nội dung

### Thay ảnh đại diện
1. Đổi tên ảnh mới thành `avatar.jpg`
2. Đặt vào thư mục này (đè lên file cũ)

### Thay nhạc nền
1. Đặt file MP3 vào thư mục (vd: `nhac-nen.mp3`)
2. Mở `config.js`, sửa dòng: `nhac: "nhac-nen.mp3"`

### Thay màu chủ đạo
Mở `config.js`, sửa dòng `mauChu`:
- Xanh lá: `"#1D9E75"`
- Xanh dương: `"#2563EB"`
- Tím: `"#7C3AED"`

### Thêm ảnh nền
1. Đặt file ảnh vào thư mục (vd: `anh-nen.jpg`)
2. Mở `config.js`, sửa dòng: `anhNen: "anh-nen.jpg"`

## 🚀 Upload lên GitHub Pages
Chọn tất cả file trong thư mục này → upload lên repo GitHub
