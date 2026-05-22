# 📄 CV Dashboard - Phạm Đức Long

Kho lưu trữ CV tương tác cá nhân, được xây dựng dưới dạng Single-Page Application (SPA) với HTML + CSS + JavaScript thuần.

## 🌟 Tính năng

- **Đăng nhập bảo mật** - Chỉ admin mới truy cập được dashboard
- **Dashboard quản lý CV** - Tổng hợp, tìm kiếm, lọc các bản CV
- **Chỉnh sửa trực tiếp (Inline Edit)** - Nhấp vào bất kỳ ô văn bản nào để chỉnh sửa ngay
- **Thêm/Xóa nội dung** - Thêm kinh nghiệm, dự án, kỹ năng, học vấn
- **Upload ảnh đại diện** - Hỗ trợ ảnh 3x4 chuẩn
- **Lọc thế mạnh** - Bộ lọc Code/Dev | Quản lý | Vận hành
- **Xuất PDF** - In CV ra PDF qua trình duyệt (text-based, tương thích ATS)
- **Xuất HTML độc lập** - Tải file HTML ready-to-deploy lên Netlify
- **Backup/Restore** - Xuất/nhập toàn bộ database CV dạng JSON
- **Đa thiết bị** - Lưu trữ trên localStorage, hỗ trợ import/export để đồng bộ

## 🚀 Deploy lên Netlify

1. Push repo này lên GitHub
2. Vào [netlify.com](https://netlify.com) → New site from Git
3. Chọn repo này, Netlify tự động deploy
4. Truy cập link được cấp

## 🔐 Đăng nhập

- **Email:** `duclongg9@gmail.com`
- **Mật khẩu:** `Long@123`

## 💻 Chạy cục bộ

```bash
# Dùng http-server (Node.js)
npx http-server . -p 3000

# Hoặc mở trực tiếp file index.html trong trình duyệt
```

## 📁 Cấu trúc

```
CV/
├── index.html      # Toàn bộ ứng dụng (SPA)
├── netlify.toml    # Cấu hình Netlify SPA routing
└── README.md       # Tài liệu này
```

---

*Được xây dựng với HTML + Tailwind CSS + Vanilla JavaScript*
